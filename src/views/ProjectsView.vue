<template>
  <NavBar />
  <div>
    <section id="project" class="project">
      <div class="container container-fluid">
        <div class="section-header"><h1>Projects</h1></div>
        <div class="project-hold">
          <div v-for="project in projects" :key="project.id" class="project">
            <div
              class="project-content row justify-content-between align-items-between flex-md-row flex-sm-column"
            >
              <div class="project-section container-fluid col-md-4">
                <div class="project-card-pro">
                  <div class="card" style="width: 100%">
                    <img :src="project.image" class="img-top" alt="Pic" />
                    <div class="card-body">
                      <h5 class="card-title">{{ project.title }}</h5>
                      <a
                        :href="project.githubLink"
                        target="_blank"
                        class="btn btn-primary"
                        >GitHub</a
                      >
                      <a
                        :href="project.liveLink"
                        target="_blank"
                        class="btn btn-primary"
                        >Live</a
                      >
                    </div>
                  </div>
                </div>
                <!-- <div class="project-card-pro">
              <div class="card" style="width: 100%">
                <img
                  src="https://picsum.photos/200/300?random=2"
                  class="card-img-top"
                  alt="Pic"
                />
                <div class="card-body">
                  <h5 class="card-title">Holiday-Destination</h5>

                  <a
                    href="https://github.com/ismaeeladams/Holiday-Destination.git"
                    target="_blank"
                    class="btn btn-primary"
                    >GitHub</a
                  >
                  <a
                    href="https://voluble-tulumba-cf4224.netlify.app"
                    target="_blank"
                    class="btn btn-primary"
                    >Live</a
                  >
                </div>
              </div>
            </div>
          </div>
          <div class="project-section container-fluid col-md-4">
            <div class="project-card-pro">
              <div class="card" style="width: 100%">
                <img
                  src="https://picsum.photos/200/300?random=3"
                  class="card-img-top"
                  alt="Pic"
                />
                <div class="card-body">
                  <h5 class="card-title">Portfolio</h5>

                  <a
                    href="https://github.com/ismaeeladams/portfolio.git"
                    target="_blank"
                    class="btn btn-primary"
                    >GitHub</a
                  >
                  <a
                    href="https://grand-praline-11396e.netlify.app"
                    target="_blank"
                    class="btn btn-primary"
                    >Live</a
                  >
                </div>
              </div>
            </div>
            <div class="project-card-pro">
              <div class="card" style="width: 100%">
                <img
                  src="https://picsum.photos/200/300?random=4"
                  class="card-img-top"
                  alt="Pic"
                />
                <div class="card-body">
                  <h5 class="card-title">Mock</h5>

                  <a
                    href="https://github.com/ismaeeladams/mock.git"
                    target="_blank"
                    class="btn btn-primary"
                    >GitHub</a
                  >
                  <a
                    href="https://clinquant-figolla-c9ddff.netlify.app"
                    target="_blank"
                    class="btn btn-primary"
                    >Live</a
                  >
                </div>
              </div>
            </div>
          </div>
          <div class="project-section container-fluid col-md-4">
            <div class="project-card-pro">
              <div class="card" style="width: 100%">
                <img
                  src="https://picsum.photos/200/300?random=3"
                  class="card-img-top"
                  alt="Pic"
                />
                <div class="card-body">
                  <h5 class="card-title">Portfolio</h5>

                  <a
                    href="https://github.com/ismaeeladams/portfolio.git"
                    target="_blank"
                    class="btn btn-primary"
                    >GitHub</a
                  >
                  <a
                    href="https://grand-praline-11396e.netlify.app"
                    target="_blank"
                    class="btn btn-primary"
                    >Live</a
                  >
                </div>
              </div>
            </div>
            <div class="project-card-pro">
              <div class="card" style="width: 100%">
                <img
                  src="https://picsum.photos/200/300?random=4"
                  class="card-img-top"
                  alt="Pic"
                />
                <div class="card-body">
                  <h5 class="card-title">Mock</h5>

                  <a
                    href="https://github.com/ismaeeladams/mock.git"
                    target="_blank"
                    class="btn btn-primary"
                    >GitHub</a
                  >
                  <a
                    href="https://clinquant-figolla-c9ddff.netlify.app"
                    target="_blank"
                    class="btn btn-primary"
                    >Live</a
                  >
                </div>
              </div>
            </div>
          </div> -->
              </div>
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
    return {
      projects: [
        {
          id: "1",
          image: "https://i.postimg.cc/cCXpjGd2/project-4.png",
          title: "Calculater",
          githubLink: "https://github.com/ismaeeladams/Calculater.git",
          liveLink: "https://zesty-mermaid-080100.netlify.app",
        },
        {
          id: "2",
          image: "https://i.postimg.cc/sxkY3vfh/project-5.png",
          title: "Holiday Destination",
          githubLink: "https://github.com/ismaeeladams/Holiday-Destination.git",
          liveLink: "https://voluble-tulumba-cf4224.netlify.app",
        },
        {
          id: "3",
          image: "https://i.postimg.cc/Ghz306Mc/project-3.png",
          title: "temp-converter",
          githubLink: "https://github.com/ismaeeladams/temp-converter",
          liveLink: "https://musical-quokka-790f68.netlify.app",
        },
        {
          id: "4",
          image: "https://i.postimg.cc/L5K5Xff2/project-2.png",
          title: "To-Do-Challenge",
          githubLink: "https://github.com/ismaeeladams/To-Do-Challenge",
          liveLink: "https://magnificent-torrone-b95f6c.netlify.app",
        },
        {
          id: "5",
          image: "",
          title: "Property Listing",
          githubLink: "https://github.com/ismaeeladams/Property-List",
          liveLink: "https://property-list-ismaeel.netlify.app",
        },
        {
          id: "6",
          image: "https://i.postimg.cc/MKgRBMSM/project-1.png",
          title: "BMI Calculater",
          githubLink: "https://github.com/ismaeeladams/BMI-Calculater",
          liveLink: "https://magical-wisp-056b44.netlify.app",
        },
      ],
    };
  },
};
</script>
<style scoped>
* {
  margin: 0;
  /* padding: 0; */
  box-sizing: border-box;
  scroll-behavior: smooth;
  color: white;
}
#project {
  /* height: 102vh; */
  padding: 5% 10%;
  background-color: #121231;
}
.card-title {
  color: black;
}

.project-hold {
  display: flex;
  flex-wrap: wrap;
  width: 100vw !important;
}

/* .project {
  width: 30%;
} */

.project-card-pro {
  margin-bottom: 10px;
  padding-bottom: 1.5rem;
  background-color: #121231;
  box-shadow: #141327;
  width: 24vw !important;
}
.card-body > a {
  margin-right: 10px;
}
img {
  width: 100%;
  height: 30vh;
  border: 2px solid black;
  /* border-radius: 25%;
  aspect-ratio: 1; */
}

.row > * {
  padding-right: 1.5rem;
}
@media screen and (max-width: 860px) {
  .project-hold {
    width: 100vw !important;
  }
  .project-card-pro {
    width: 33vw !important;
  }
}
@media screen and (max-width: 625px) {
  .project-hold {
    width: 100vw !important;
  }
  .project-card-pro {
    width: 45vw !important;
  }
}
</style>
