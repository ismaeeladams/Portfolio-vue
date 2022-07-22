<template>
  <NavBar />
  <section id="about" class="about">
    <div class="container-p container-fliud" id="container-p">
      <div class="row">
        <div class="col-lg-6">
          <div class="img-a border d-flex justify-content-center">
            <div class="card img">
              <!-- style="width: 18rem" -->
              <img
                src="https://github.com/ismaeeladams/Portfolio-vue/blob/main/src/assets/Images/Ismaeel%20(1).JPG?raw=true"
                class="card-img-top"
                alt="..."
              />
            </div>
          </div>
        </div>
        <div class="col-lg-6">
          <div class="about-content">
            <h2 class="h2">Nice to meet you</h2>
            <!-- <h3 class="h3">Aspiring Full Stack Developer</h3> -->
            <p class="p">
              I am often told that I am charismatic, polite and hold good
              company. I'm energetic and eager to learn new skills, my
              inquisitive nature is put to good use in this regard.
            </p>
            <p class="p">
              I am dependable and very punctual, I truly believe in the 'early
              bird' senario. Honestiy and trustworthiness are two main qualities
              I base my enthusiasm and professional life on. My enthusiasm and
              creative approach to problem solving are continually developing.
            </p>
            <p>I go above and beyond of what is expected of me.</p>
            <!-- <div class="content-details">
              <div class="details-left">
                <ul class="list-unstyled">
                  <li><span class="fw-bold">D.O.B:</span>2002/09/28</li>
                  <li>
                    <span class="fw-bold">Address:</span>25 Linda Road Grassy
                    Park
                  </li>
                </ul>
              </div>
              <div class="details-right">
                <ul class="list-unstyled">
                  <li><span class="fw-bold">Drivers license:</span>Yes</li>
                </ul>
              </div>
            </div> -->
          </div>
        </div>
      </div>
    </div>
  </section>
  <Footer />
</template>

<script>
import NavBar from "@/components/NavBar.vue";
import Footer from "@/components/Footer.vue";
export default {
  components: {
    NavBar,
    Footer,
  },
};
</script>

<style scoped>
* {
  /* margin: 0;
  padding: 0; */
  box-sizing: border-box;
  scroll-behavior: smooth;
  color: white;
}
#about {
  /* height: 100vh; */
  padding: 5% 10%;
  background-color: #18182f;
}
.border {
  border-radius: 5px;
  padding: 25px;
  margin-right: 5%;
  background: #0e139a;
  box-shadow: inset 35px 35px 70px #0a55c3, inset -35px -35px 70px #1087ff;
  /* height: fit-content; */
  /* width: fit-content; */
  width: 64%;
}
.img {
  border-radius: 5px;
  height: 100%;
  width: 100%;
  object-fit: cover;
  overflow: hidden;
}

.container-p {
  display: flex;
}
.h2 {
  font-size: 50px;
  margin-bottom: 10px;
}
.h3 {
  font-size: 20px;
  margin-bottom: 30px;
}
.p {
  font-size: 18px;
  margin-bottom: 30px;
}
.content-details {
  display: flex;
}
.details-left {
  padding-right: 10px;
}
@media screen and (max-width: 1200px) {
  .row {
    display: flex;
    flex-wrap: wrap;
  }
  /* .img {
    height: 50rem;
  } */
}
</style>
