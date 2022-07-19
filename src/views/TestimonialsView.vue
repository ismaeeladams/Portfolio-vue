<template>
  <NavBar />
  <div>
    <!-- 
      <div class="section-header">
        <h3>These are Testimonials</h3>
      </div>
      <carousel class="tes-container">
        <div class="owl-carousel">
          <div class="p-3">
            <div class="bg-dark text-white p-3">
              <div class="tes">
                <div class="tes-header">
                  <div class="tes-img">
                    <img
                      src="https://github.com/ismaeeladams/Portfolio-vue/blob/main/src/assets/Images/tes-1.jpg?raw=true"
                      style="height: 50px"
                    />
                  </div>
                  <div class="tes-authour">
                    <h5>Mika Rinquest</h5>
                    <h6>Colleage</h6>
                  </div>
                </div>
                <div class="tes-body">
                  <p>
                    Isma'eel usually keeps to himself, so people often don't
                    notice him. However, he has a good understanding of the work
                    he does and helps others when they need it.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class="p-3">
            <div class="bg-dark text-white p-3">
              <div class="tes">
                <div class="tes-header">
                  <div class="tes-img">
                    <img
                      src="https://github.com/ismaeeladams/Portfolio-vue/blob/main/src/assets/Images/tes-2.jpg?raw=true"
                      style="height: 50px"
                    />
                  </div>
                  <div class="tes-authour">
                    <h5>Jason Wandrag</h5>
                    <h6>Lecturer</h6>
                  </div>
                </div>
                <div class="tes-body">
                  <p>
                    Isma'eel has a great personality and he brightens up the day
                    of the people around him. He motivates those around him
                    whilst maintaining a positive environment. Isma'eel is also
                    very dedicated to his work and has steadily improved in the
                    short time that I have known him. I know that he will go far
                    on his journey.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class="p-3">
            <div class="bg-dark text-white p-3">
              <div class="tes">
                <div class="tes-header">
                  <div class="tes-img">
                    <img
                      src="https://picsum.photos/200/300?random=10"
                      style="height: 50px"
                    />
                  </div>
                  <div class="tes-authour">
                    <h5>Milo</h5>
                    <h6>Head of Nothing</h6>
                  </div>
                </div>
                <div class="tes-body">
                  <p>
                    Lorem ipsum dolor sit, amet consectetur adipisicing elit.
                    Sit modi harum veniam assumenda dicta odio, repudiandae
                    culpa iusto provident nesciunt!
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class="p-3">
            <div class="bg-dark text-white p-3">
              <div class="tes">
                <div class="tes-header">
                  <div class="tes-img">
                    <img
                      src="https://picsum.photos/200/300?random=11"
                      style="height: 50px"
                    />
                  </div>
                  <div class="tes-authour">
                    <h5>Milo</h5>
                    <h6>Head of Nothing</h6>
                  </div>
                </div>
                <div class="tes-body">
                  <p>
                    Lorem ipsum dolor sit, amet consectetur adipisicing elit.
                    Sit modi harum veniam assumenda dicta odio, repudiandae
                    culpa iusto provident nesciunt!
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </carousel>
    </section> -->
    <div
      id="carouselExampleCaptions"
      class="carousel slide"
      data-bs-ride="carousel"
    >
      <div class="carousel-indicators">
        <button
          type="button"
          data-bs-target="#carouselExampleCaptions"
          data-bs-slide-to="0"
          class="active"
          aria-current="true"
          aria-label="Slide 1"
        ></button>
        <button
          type="button"
          data-bs-target="#carouselExampleCaptions"
          data-bs-slide-to="1"
          aria-label="Slide 2"
        ></button>
        <button
          type="button"
          data-bs-target="#carouselExampleCaptions"
          data-bs-slide-to="2"
          aria-label="Slide 3"
        ></button>
      </div>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <div>
            <img
              src="https://github.com/ismaeeladams/Portfolio-vue/blob/main/src/assets/Images/tes-1.jpg?raw=true"
              class="d-block w-100"
              alt="..."
            />
          </div>
          <div class="carousel-caption d-none d-md-block">
            <h5>Mika Rinquest</h5>
            <h6>Colleage</h6>
            <p>
              Isma'eel usually keeps to himself, so people often don't notice
              him. However, he has a good understanding of the work he does and
              helps others when they need it.
            </p>
          </div>
        </div>
        <div class="carousel-item">
          <div>
            <img
              src="https://github.com/ismaeeladams/Portfolio-vue/blob/main/src/assets/Images/tes-2.jpg?raw=true"
              class="d-block w-100"
              alt="..."
            />
          </div>
          <div class="carousel-caption d-none d-md-block">
            <h5>Jason Wandrag</h5>
            <h6>Lecturer</h6>
            <p>
              Isma'eel has a great personality and he brightens up the day of
              the people around him. He motivates those around him whilst
              maintaining a positive environment. Isma'eel is also very
              dedicated to his work and has steadily improved in the short time
              that I have known him. I know that he will go far on his journey.
            </p>
          </div>
        </div>
        <div class="carousel-item">
          <div>
            <img
              src="https://picsum.photos/200/300?random=10"
              class="d-block w-100"
              alt="..."
            />
          </div>
          <div class="carousel-caption d-none d-md-block">
            <h5>Third slide label</h5>
            <p>Some representative placeholder content for the third slide.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
  <Footer />
</template>
<script>
import NavBar from "@/components/NavBar.vue";
import Footer from "@/components/Footer.vue";
import carousel from "vue-owl-carousel";

export default {
  components: {
    carousel,
    NavBar,
    Footer,
  },
  methods: {},
};
</script>
<style scoped>
#testimonial {
  /* height: 59vh; */
  padding: 5% 10%;
  background-color: #18182f;
}
.tes-img {
  /* width: 50px;
  height: 50px; */
  border-radius: 50%;
}
.owl-carousel button.owl-dot {
  background: white;
  background: 0 0;
  color: inherit;
  border: none;
  padding: 0 !important;
  font: inherit;
  background: white;
  width: 10px;
  border-radius: 50%;
  height: 10px;
}
.owl-dots {
  background: black;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 10px;
  gap: 10px;
}
button.owl-dot.active {
  background: aqua;
}
.carousel-item {
  height: 100vh;
}
img {
  height: 47rem;
  /* width: 80% !important; */
  object-fit: scale-down;
  background-color: black;
}
/* .carousel-caption {
  background-color: black;
} */
</style>
