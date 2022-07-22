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
            <div v-for="resume in resume" :key="resume.id">
            <div class="card-res flipcard" style="width: 28rem">
              <div class="card-body flipcard-inner">
                <div class="flipcard-front">
                  <h5 class="card-title">{{resume.title}}</h5>
                  <h6 class="card-subtitle mb-2 text-muted">
                   {{resume.subtitle}}
                  </h6>
                  <h6 class="card-subtitle mb-2 text-muted">{{times}}</h6>
                </div>
                <div class="flipcard-back">
                  <h1>{{resume.description}}</h1>
                </div>
              </div>
            </div>
            </div>
            <!-- <div class="card-res flipcard" style="width: 28rem">
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
            </div> -->
          </div>
          <div class="experience-cotainer col-md-6">
            <h4>Experience</h4>
            <div v-for="resume2 in resume2" :key="resume2.id">
             <div class="card-res flipcard" style="width: 28rem">
              <div class="card-body flipcard-inner">
                <div class="flipcard-front">
                  <h5 class="card-title">{{resume2.title}}</h5>
                  <h6 class="card-subtitle mb-2 text-muted">{{resume2.subtitle}}</h6>
                  <h6 class="card-subtitle mb-2 text-muted">{{resume2.times}}</h6>
                </div>
                <div class="flipcard-back">
                  <h1>{{resume2.description}}</h1>
                </div>
              </div>
             </div>
            </div>
            <!-- <div class="card-res flipcard" style="width: 28rem">
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
            </div> -->
          </div>
        </div>
      </div>
      <div class="skills-container">
        <div class="row">
          <div class="card-skills bootstrap col-md-6" style="width: 18rem">
            <div class="card-body">
              <h5 class="card-title-skills" style="color: white">Bootstrap</h5>
              <p class="card-text">
                <i class="fa-brands fa-bootstrap"></i>
              </p>
            </div>
          </div>
          <div class="card-skills html col-md-6" style="width: 18rem">
            <div class="card-body">
              <h5 class="card-title-skills" style="color: white">HTML</h5>
              <p class="card-text">
                <i class="fa-brands fa-html5"></i>
              </p>
            </div>
          </div>
          <div class="card-skills css col-md-6" style="width: 18rem">
            <div class="card-body">
              <h5 class="card-title-skills" style="color: white">CSS</h5>
              <p class="card-text">
                <i class="fa-brands fa-css3"></i>
              </p>
            </div>
          </div>
          <div class="card-skills js col-md-6" style="width: 18rem">
            <div class="card-body">
              <h5 class="card-title-skills" style="color: white">Javascript</h5>
              <p class="card-text">
                <i class="fa-brands fa-js-square"></i>
              </p>
            </div>
          </div>
          <div class="card-skills vue col-md-6" style="width: 18rem">
            <div class="card-body">
              <h5 class="card-title-skills" style="color: white">Vue</h5>
              <p class="card-text">
                <i class="fa-brands fa-vuejs"></i>
              </p>
            </div>
          </div>
          <div class="card-skills mysql col-md-6" style="width: 18rem">
            <div class="card-body">
              <h5 class="card-title-skills" style="color: white">MySQL</h5>
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
  data() {
    return{
      resume: [
        {
          id: "1",
          title: "Life Choices",
          subtitle: "Wed development and programming bootcamp",
          times: "2022-Present",
          description: "Hello",
        },
        {
          id: "2",
          title: "Oracle Academy High School",
          subtitle: "Matric",
          times: "2021",
          description: "Hello",
        },
      ],
        resume2 : [
          {
              id: "1",
          title: "FK Adams construction",
          subtitle: "Laborer",
          times: "2021-Present",
          description: "Hello",
          }
        ]
    }
  }
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
  /* background-color: #121231; */
  /* background-color: #202020; */
  /* background-image: linear-gradient(to right top, #eee862, #ebbc37, #e58e1a, #d95d12, #c71b1b); */
  background-image: linear-gradient(to bottom, #0d0651, #002f75, #005390, #0076a2, #0098af, #00a7b2, #00b6af, #2bc4a8, #00c395, #00c17f, #00be64, #24bb45);
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

/* .card-title-skills {
  color: transparent ;
  color: black ;
} */
/* .card-skills > h5 {
  color: transparent;
} */


.bootstrap:hover .fa-bootstrap {
  color: #563d7c;
}
.bootstrap:hover .card-title {
  color: #27beb2c7;
}
.html:hover .fa-html5 {
  color: #e34c26;
}
.html:hover .card-title {
  color: #0a0909;
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
@media screen and (max-width: 540px) {
  .container {
    display: flex;
    flex-direction: column;
  }
  .col-md-6 {
    width: 100%;
  }
}
</style>
