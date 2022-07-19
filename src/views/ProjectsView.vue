<template>
  <NavBar />
  <div>
    <section id="project" class="project">
      <div class="container">
        <div class="section-header"><h1>Projects</h1></div>
        <div
          class="project-content row justify-content-between align-items-between flex-md-row flex-sm-column"
        >
          <div class="project-section container-fluid col-md-4">
            <div class="project-card-pro">
              <div class="card" style="width: 100%">
                <img
                  src="https://picsum.photos/200/300?random=5"
                  class="card-img-top"
                  alt="Pic"
                />
                <div class="card-body">
                  <h5 class="card-title">Calculater</h5>

                  <a
                    href="https://github.com/ismaeeladams/Calculater.git"
                    target="_blank"
                    class="btn btn-primary"
                    >GitHub</a
                  >
                  <a
                    href="https://zesty-mermaid-080100.netlify.app"
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

.project-card-pro {
  margin-bottom: 10px;
  padding-bottom: 1.5rem;
  background-color: #121231;
  box-shadow: #141327;
}
.card-body > a {
  margin-right: 10px;
}
img {
  width: 100%;
  height: 30vh;
}
.row > * {
  padding-right: 1.5rem;
}
</style>
