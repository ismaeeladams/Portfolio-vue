<template>
  <NavBar />
  <div class="home">
    <div class="landing">
      <div class="landing-content">
        <p>Hi, I'm Isma'eel Adams</p>
        <h1>
          <span class="cursive">Aspiring</span> Full Stack
          <span>Developer</span>
        </h1>
      </div>
    </div>
  </div>
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
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  scroll-behavior: smooth;
  color: white;
}
.landing {
  /* max-width: 100%;
  height: auto; */
  height: 100vh;
  background-image: url("http://127.0.0.1:5500/src/assets/Images/Landing.jpg");
  background-size: cover;
  background-position: center;
  position: relative;
}
.landing-content {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding-top: 300px;
}
p {
  font-size: 24px;
  font-weight: bold;
}
h1 {
  font-size: 80px;
  font-weight: 900;
}
</style>
