<template>
  <NavBar />
  <section id="contact" class="contact">
    <div class="sec-header">
      <h2>Questions</h2>
      <h3 class="cursive">Let's get in touch</h3>
    </div>
    <div class="form-and-details-container-fliud">
      <div class="row">
        <div class="details-container col-md-6">
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Repudiandae
            corporis, adipisci autem earum esse fugiat!
          </p>
          <ul class="list-unstyled">
            <li>
              <i class="fa-solid fa-location-dot"></i>Grassy Park, Cape Town
            </li>
            <li>
              <a href="tel:072 840 1187"
                ><i class="fa-solid fa-mobile-button"></i
              ></a>
              072 840 1187
            </li>
            <li>
              <a href="mailto:adamsismaeel@gmail.com">
                <i class="fa-solid fa-paper-plane"></i
              ></a>
              adamsismaeel@gmail.com
            </li>
          </ul>
          <div class="details-links">
            <ul class="list-unstyled bi">
              <li class="m">
                <a
                  class="btn i"
                  href="https://www.linkedin.com/in/isma-eel-adams-910a83237/"
                  target="_blank"
                  role="button"
                  ><i class="fa-brands fa-linkedin rounded-circle"></i
                ></a>
              </li>
              <li class="m">
                <a
                  class="btn i"
                  href="https://github.com/ismaeeladams"
                  target="_blank"
                  role="button"
                >
                  <i class="fa-brands fa-github rounded-circle"></i>
                </a>
              </li>
            </ul>
          </div>
        </div>
        <div class="form-container col-md-6">
          <form action="https://formspree.io/f/xeqnvqby" method="post">
            <div class="mb-3 y">
              <input
                required
                name="name"
                type="text"
                class="form-details"
                id="name"
                placeholder="Name"
              />
              <input
                required
                name="number"
                type="tell"
                class="form-details"
                id="phone"
                placeholder="Contact No"
              />
              <input
                required
                type="email"
                class="form-details"
                id="email"
                placeholder="Email"
              />
            </div>
            <div class="mb-3">
              <textarea
                required
                class="form-control"
                id="message"
                rows="3"
                placeholder="Message"
              ></textarea>
              <button
                name="submit form button"
                class="button btn o"
                type="submit"
              >
                Submit Info
              </button>
            </div>
          </form>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
import NavBar from "@/components/NavBar.vue";
export default {
  components: {
    NavBar,
  },
};
</script>
<style>
#contact {
  /* height: 60vh; */
  padding: 5% 10%;
  background-color: #121231;
}
.form-and-details-container-fliud {
  display: flex;
}
.form-container {
  padding: 12px;
}

form {
  border: solid;
  padding: 10px;
}

input {
  border: none;
  border-bottom: solid black;
  background-color: transparent;
  margin: 5px;
}

textarea.form-control {
  border: none;
  border-bottom: solid;
  margin-bottom: 10px;
}
.owl-carousel .owl-item img {
  border-radius: 50%;
}

.bi {
  display: flex;
  align-items: center;
}
.i {
  border: solid 5px;
  border-radius: 50%;
}
.rounded-circle {
  height: 27px;
  width: 18px;
  font-size: 31px;
}
.m:hover {
  background: #0a55c3;
}
li.m {
  border-radius: 50%;
}
.o {
  background-color: #0d6efd;
}
.y {
  display: flex;
  flex-direction: column;
}
</style>
