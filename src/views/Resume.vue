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
            <div class="card-res flipcard" style="width: 28rem">
              <div class="card-body flipcard-inner">
                <div class="flipcard-front">
                  <h5 class="card-title">Life Choices</h5>
                  <h6 class="card-subtitle mb-2 text-muted">
                    Wed development and programming bootcamp
                  </h6>
                  <h6 class="card-subtitle mb-2 text-muted">2022-Present</h6>
                </div>
                <div class="flipcard-back">
                  <h1>HELLO</h1>
                </div>
              </div>
            </div>
            <div class="card-res flipcard" style="width: 28rem">
              <div class="card-body flipcard-inner">
                <div class="flipcard-front">
                  <h5 class="card-title">Oracle Academy High School</h5>
                  <h6 class="card-subtitle mb-2 text-muted">Matric</h6>
                  <h6 class="card-subtitle mb-2 text-muted">2021</h6>
                </div>
                <div class="flipcard-back">
                  <h1>HELLO</h1>
                </div>
              </div>
            </div>
          </div>
          <div class="experience-cotainer col-md-6">
            <h4>Experience</h4>
            <div class="card-res flipcard" style="width: 28rem">
              <div class="card-body flipcard-inner">
                <div class="flipcard-front">
                  <h5 class="card-title">FK Adams construction</h5>
                  <h6 class="card-subtitle mb-2 text-muted">Laborer</h6>
                  <h6 class="card-subtitle mb-2 text-muted">2021-Present</h6>
                </div>
                <div class="flipcard-back">
                  <h1>HELLO</h1>
                </div>
              </div>
            </div>
            <div class="card-res flipcard" style="width: 28rem">
              <div class="card-body flipcard-inner">
                <div class="flipcard-front">
                  <h5 class="card-title">FK Adams construction</h5>
                  <h6 class="card-subtitle mb-2 text-muted">Laborer</h6>
                  <h6 class="card-subtitle mb-2 text-muted">2021-Present</h6>
                </div>
                <div class="flipcard-back">
                  <h1>HELLO</h1>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="skills-container">
        <div class="row">
          <div class="card-skills bootstrap col-md-6" style="width: 18rem">
            <div class="card-body">
              <h5 class="card-title" style="color: #121231">Bootstrap</h5>
              <p class="card-text">
                <i class="fa-brands fa-bootstrap"></i>
              </p>
            </div>
          </div>
          <div class="card-skills html col-md-6" style="width: 18rem">
            <div class="card-body">
              <h5 class="card-title" style="color: #121231">HTML</h5>
              <p class="card-text">
                <i class="fa-brands fa-html5"></i>
              </p>
            </div>
          </div>
          <div class="card-skills css col-md-6" style="width: 18rem">
            <div class="card-body">
              <h5 class="card-title" style="color: #121231">CSS</h5>
              <p class="card-text">
                <i class="fa-brands fa-css3"></i>
              </p>
            </div>
          </div>
          <div class="card-skills js col-md-6" style="width: 18rem">
            <div class="card-body">
              <h5 class="card-title" style="color: #121231">Javascript</h5>
              <p class="card-text">
                <i class="fa-brands fa-js-square"></i>
              </p>
            </div>
          </div>
          <div class="card-skills vue col-md-6" style="width: 18rem">
            <div class="card-body">
              <h5 class="card-title" style="color: #121231">Vue</h5>
              <p class="card-text">
                <i class="fa-brands fa-vuejs"></i>
              </p>
            </div>
          </div>
          <div class="card-skills mysql col-md-6" style="width: 18rem">
            <div class="card-body">
              <h5 class="card-title" style="color: #121231">MySQL</h5>
              <p class="card-text">
                <i class="fa-solid fa-database"></i>
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
.card-skills:hover {
  background-color: white;
}

.card-text {
  display: flex;
  justify-content: center;
}
i {
  font-size: 5rem;
  display: flex;
  justify-content: center;
}

.bootstrap:hover .fa-bootstrap {
  color: #563d7c;
}
.bootstrap:hover .card-title {
  color: #000000;
}
.html:hover .fa-html5 {
  color: #e34c26;
}
.html:hover .card-title {
  color: #000000;
}
.css:hover .fa-css3 {
  color: #264de4;
}
.css:hover .card-title {
  color: #000000;
}
.js:hover .fa-js-square {
  color: #f0db4f;
}
.js:hover .card-title {
  color: #000000;
}
.vue:hover .fa-vuejs {
  color: #42b883;
  /* color: #35495e; */
}
.vue:hover .card-title {
  color: #000000;
}
.mysql:hover .fa-database {
  color: #00758f;
  /* color: #f29111; */
}
.mysql:hover .card-title {
  color: #000000;
}
.col-md-6 {
  width: 37%;
}
/* filp-cards */
.flipcard {
  background-color: transparent;
  width: 20%;
  /* aspect-ratio: 1; */
  perspective: 1000px;
}
.flipcard-inner {
  position: relative;
  width: 100%;
  height: 100%;
  text-align: center;
  transition: transform 0.8s;
  transform-style: preserve-3d;
}
.flipcard:hover .flipcard-inner {
  transform: rotateY(180deg);
}
.flipcard-front,
.flipcard-back {
  position: absolute;
  width: 100%;
  height: 100%;
  backface-visibility: hidden;
}
.flipcard-front {
  color: black;
  /* display: flex;
  justify-content: center;
  align-items: center; */
}
.flipcard-back {
  background-color: #68626d;
  color: white;
  transform: rotateY(180deg);
}
</style>
