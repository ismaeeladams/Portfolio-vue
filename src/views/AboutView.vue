<template>
  <NavBar />
  <section id="about" class="about">
    <div class="container-p container-fliud" id="container-p">
      <div class="row">
        <div class="col-xl-6">
          <div class="img-a border d-flex justify-content-center">
            <img class="img" src="https://picsum.photos/200/300?random=6" />
          </div>
        </div>
        <div class="col-xl-6">
          <div class="about-content">
            <h2 class="h2">Nice to meet you</h2>
            <h3 class="h3">Aspiring Full Stack Developer</h3>
            <p class="p">
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Laboriosam corporis autem excepturi necessitatibus iste quidem vel
              possimus atque sequi officia?
            </p>
            <p class="p">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptas,
              quaerat magni cum delectus magnam nemo beatae assumenda
              aspernatur? Illum, magni deleniti sit quod deserunt labore vel eos
              cumque excepturi molestiae quae maxime, quos impedit tempora
              maiores. Ipsam nemo iure quas saepe, obcaecati modi dolores ad.
            </p>
            <div class="content-details">
              <div class="details-left">
                <ul class="list-unstyled">
                  <li><span class="fw-bold">.D.O.B:</span>2002/09/28</li>
                  <li>
                    <span class="fw-bold">.Address:</span>25 Linda Road Grassy
                    Park
                  </li>
                </ul>
              </div>
              <div class="details-right">
                <ul class="list-unstyled">
                  <li><span class="fw-bold">.Criminal Record:</span>No</li>
                  <li><span class="fw-bold">.Drivers license:</span>No</li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import NavBar from "@/components/NavBar.vue";
export default {
  components: {
    NavBar,
  },
};
</script>

<style scoped>
#about {
  /* height: 86vh; */
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
  width: 50%;
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
</style>
