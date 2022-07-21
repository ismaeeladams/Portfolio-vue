<template>
  <NavBar />
  <div id="testimonial">
    <div class="container-fluid container col-md-6">
      <div v-for="testimonial in testimonials" :key="testimonial.id">
        <div class="card-res flipcard">
          <div class="card-body flipcard-inner">
            <div class="flipcard-front">
              <!-- <h5 class="card-title">Life Choices</h5>
          <h6 class="card-subtitle mb-2 text-muted">
            Wed development and programming bootcamp
          </h6>
          <h6 class="card-subtitle mb-2 text-muted">2022-Present</h6> -->
              <img :src="testimonial.image" />
            </div>
            <div class="flipcard-back">
              <h5>{{ testimonial.name }}</h5>
              <h6>{{ testimonial.role }}</h6>
              <p>
                {{ testimonial.description }}
              </p>
            </div>
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
  data() {
    return {
      testimonials: [
        {
          id: "1",
          name: "Mika Rinquest",
          role: "College",
          description:
            "Isma'eel usually keeps to himself, so people often don't notice him. However, he has a good understanding of the work he does and helps others when they need it.",
          image:
            "https://github.com/ismaeeladams/Portfolio-vue/blob/main/src/assets/Images/tes-1.jpg?raw=true",
        },
        {
          id: "2",
          name: "Jason Wandrag",
          role: "Lecturer",
          description:
            "Isma'eel has a great personality and he brightens up the day of the people around him. He motivates those around him whilst maintaining a positive environment. Isma'eel is also very dedicated to his work and has steadily improved in the short time that I have known him. I know that he will go far on his journey.",
          image:
            "https://github.com/ismaeeladams/Portfolio-vue/blob/main/src/assets/Images/tes-2.jpg?raw=true",
        },
      ],
    };
  },
};
</script>
<style scoped>
#testimonial {
  /* height: 94vh; */
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
  height: 22rem;
  /* width: 80% !important; */
  object-fit: scale-down;
  background-color: black;
}
/* .carousel-caption {
  background-color: black;
} */
.flipcard {
  background-color: transparent;
  width: 20%;
  aspect-ratio: 1;
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
  display: flex;
  justify-content: center;
  align-items: center;
}
.flipcard-back {
  background-color: transparent;
  color: white;
  transform: rotateY(180deg);
}
/* .container {
  display: flex;
} */
.card-res {
  width: 28rem;
  padding: 30px;
  max-width: 95%;
  min-height: 300px;
  margin-bottom: 20px;
  border: solid;
  border-top-right-radius: 10px;
  border-bottom-right-radius: 10px;
}
@media screen and (max-width: 500px) {
  .card-res {
    width: 18rem;
  }
}
</style>
