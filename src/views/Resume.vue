<template>
  <NavBar />
  <div>
    <section id="resume" class="resume">
      <div class="section-header">
        <h2>My Resume</h2>
      </div>
      <div class="container-fluid container-res">
        <div class="container row flex-md-row flex-sm-column">
          <div class="education-container col-md-6">
            <h4>Education</h4>
            <div class="card-res" style="width: 28rem">
              <div class="card-body">
                <h5 class="card-title">Life Choices</h5>
                <h6 class="card-subtitle mb-2 text-muted">
                  Wed development and programming bootcamp
                </h6>
                <h6 class="card-subtitle mb-2 text-muted">2022-Present</h6>
              </div>
            </div>
            <div class="card-res" style="width: 28rem">
              <div class="card-body">
                <h5 class="card-title">Oracle Academy High School</h5>
                <h6 class="card-subtitle mb-2 text-muted">Matric</h6>
                <h6 class="card-subtitle mb-2 text-muted">2021</h6>
              </div>
            </div>
          </div>
          <div class="experience-cotainer col-md-6">
            <h4>Experience</h4>
            <div class="card-res" style="width: 28rem">
              <div class="card-body">
                <h5 class="card-title">FK Adams constrution</h5>
                <h6 class="card-subtitle mb-2 text-muted">Labourer</h6>
                <h6 class="card-subtitle mb-2 text-muted">2021-Present</h6>
              </div>
            </div>
            <div class="card-res" style="width: 28rem">
              <div class="card-body">
                <h5 class="card-title">FK Adams constrution</h5>
                <h6 class="card-subtitle mb-2 text-muted">Labourer</h6>
                <h6 class="card-subtitle mb-2 text-muted">2021-Present</h6>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="skills-container">
        <div class="row">
          <div class="card-skills col-md-6" style="width: 18rem">
            <div class="card-body">
              <h5 class="card-title">Bootstrap</h5>
              <p class="card-text">
                <i class="fa-brands fa-bootstrap"></i>
              </p>
            </div>
          </div>
          <div class="card-skills col-md-6" style="width: 18rem">
            <div class="card-body">
              <h5 class="card-title">HTML</h5>
              <p class="card-text">
                <i class="fa-brands fa-html5"></i>
              </p>
            </div>
          </div>
          <div class="card-skills col-md-6" style="width: 18rem">
            <div class="card-body">
              <h5 class="card-title">CSS</h5>
              <p class="card-text">
                <i class="fa-brands fa-css3"></i>
              </p>
            </div>
          </div>
          <div class="card-skills col-md-6" style="width: 18rem">
            <div class="card-body">
              <h5 class="card-title">CSS</h5>
              <p class="card-text">
                <i class="fa-brands fa-css3"></i>
              </p>
            </div>
          </div>
          <div class="card-skills col-md-6" style="width: 18rem">
            <div class="card-body">
              <h5 class="card-title">CSS</h5>
              <p class="card-text">
                <i class="fa-brands fa-css3"></i>
              </p>
            </div>
          </div>
          <div class="card-skills col-md-6" style="width: 18rem">
            <div class="card-body">
              <h5 class="card-title">CSS</h5>
              <p class="card-text">
                <i class="fa-brands fa-css3"></i>
              </p>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
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
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  scroll-behavior: smooth;
  color: white;
}
#resume {
  /* height: 137vh; */
  padding: 5% 10%;
  background-color: #121231;
}
.container-res {
  display: flex;
  justify-content: space-between;
}
.card-res {
  width: 600px;
  padding: 30px;
  max-width: 95%;
  min-height: 300px;
  margin-bottom: 20px;
  border: solid;
  border-top-right-radius: 10px;
  border-bottom-right-radius: 10px;
}

.container {
  justify-content: space-between;
}

.skills-container {
  padding-top: 28px;
}
.row {
  display: flex;
  justify-content: space-between;
}
.card-skills {
  margin-right: 20px;
  border: solid;
  padding: 10px;
  margin-bottom: 25px;
  width: 35%;
}

.card-text {
  display: flex;
  justify-content: center;
}
.fa-brands {
  font-size: 5rem;
  display: flex;
  justify-content: center;
}
.col-md-6 {
  width: 37%;
}
</style>
