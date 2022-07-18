<template>
  <NavBar />
  <div>
    <section id="testimonial" class="testimonial">
      <div class="section-header">
        <h3>These are Testimonials</h3>
      </div>
      <div class="tes-container">
        <div class="owl-carousel">
          <div class="p-3">
            <div class="bg-dark text-white p-3">
              <div class="tes">
                <div class="tes-header">
                  <div class="tes-img">
                    <img src="tes-1.jpg" style="height: 50px" />
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
                    <img src="tes-2.jpg" style="height: 50px" />
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
  methods:{
    
  }
};
</script>
<style></style>
