<template>
  <nav class="navbar">
    <button
      class="btn btn-primary"
      type="button"
      data-bs-toggle="offcanvas"
      data-bs-target="#nav"
      aria-controls="nav"
    >
      <!-- <i class="fa-solid fa-bars-staggered"></i> -->
      ==
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
        <h5 class="offcanvas-title" id="navLabel">Navbar</h5>
        <button
          type="button"
          class="btn-close text-reset"
          data-bs-dismiss="offcanvas"
          aria-label="Close"
        ></button>
      </div>
      <div class="offcanvas-body">
        <nav>
          <router-link to="/">Home</router-link> |
          <router-link to="/about">About Me</router-link> |
          <router-link to="/projects">Projects</router-link> |
          <router-link to="/resume">Resume</router-link> |
          <router-link to="/testimonials">Testimonials</router-link> |
          <router-link to="/contact">Contact</router-link> |
        </nav>
        <router-view />
      </div>
    </div>
  </nav>
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
nav {
  display: flex;
  flex-direction: column;
}
</style>
