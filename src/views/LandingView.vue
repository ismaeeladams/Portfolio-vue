<template>
  <NavBar />
  <div class="home">
    <div class="landing">
      <div class="landing-content container-fluid row">
        <p>Hi, I'm Isma'eel Adams</p>
        <p>an</p>
        <h1>
          <span class="cursive">Aspiring</span> Full Stack
          <span>Developer</span>
        </h1>
      </div>
    </div>
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
.cursive {
  font-family: "Lobster", cursive;
}
.landing {
  /* max-width: 100%;
  height: auto; */
  height: 100vh;
  /* background-image: url("http://127.0.0.1:5500/src/assets/Images/Landing.jpg"); */
  /* background: #0e139a; */
  /* background: #121231; */
  background-image: linear-gradient(to bottom, #0d0651, #002f75, #005390, #0076a2, #0098af, #00a7b2, #00b6af, #2bc4a8, #00c395, #00c17f, #00be64, #24bb45);
  background-size: cover;
  background-position: center;
  position: relative;
  display: flex;
  flex-direction: column;
  justify-content: center;
}
/* .landing-content {
  padding-top: 300px;
} */
p {
  font-size: 24px;
  font-weight: bold;
}
h1 {
  font-size: 65px;
  font-weight: 900;
}
@media screen and (max-width: 290px) {
  h1 {
    font-size: 48px;
    font-weight: 900;
  }
}
</style>
