<template>
  <div class="navbar">
    <button
      class="btn btn-primary"
      type="button"
      data-bs-toggle="offcanvas"
      data-bs-target="#nav"
      aria-controls="nav"
    >
      <i class="fa-solid fa-bars-staggered"></i>
    </button>
    <div
      class="offcanvas offcanvas-end"
      data-bs-scroll="true"
      data-bs-backdrop="false"
      tabindex="-1"
      id="nav"
      aria-labelledby="navLabel"
    >
      <div class="offcanvas-header">
        <h5 class="offcanvas-title" id="navLabel"></h5>
        <button
          type="button"
          class="btn-close text-reset"
          data-bs-dismiss="offcanvas"
          aria-label="Close"
        ></button>
      </div>
      <div class="offcanvas-body">
        <nav>
          <router-link to="/" class="links">Home</router-link>
          <router-link to="/about" class="links">About Me</router-link>
          <router-link to="/projects" class="links">Projects</router-link>
          <router-link to="/resume" class="links">Resume</router-link>
          <router-link to="/testimonials" class="links"
            >Testimonials</router-link
          >
          <router-link to="/contact" class="links">Contact</router-link>
        </nav>
        <router-view />
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "NavBar",
};
</script>
<style scoped>
.navbar {
  position: fixed;
  top: 0;
  width: 100%;
  z-index: 1000;
  display: flex;
  padding: 1% 10%;
  align-items: center;
  justify-content: space-between;
  /* overflow-y: hidden; */
}
nav > * {
  display: flex;
  flex-direction: column;
  text-decoration: none;
  justify-content: center;
  font-size: 136%;
}
/* .offcanvas-body {
  height: 100%;
} */
nav {
  height: 100%;
}
.links {
  height: 17%;
  /* border: 2px solid black; */
}
.links:hover {
  background-color: #8f4c87;
  border-radius: 15%;
}
/* router-link {
  height: 31%;
} */
.offcanvas {
  background-color: white;
}
</style>
