<template>
  <div>
    <footer class="footer">
      <div class="footer-container container-fluid">
        <div class="design">
          <p>
            Designed and developed by
            <span class="fw-bold">Isma'eel Adams</span>
          </p>
        </div>
        <div class="copyright">
          <p>Copyright © 2022. All Rights Reserved</p>
        </div>
      </div>
    </footer>
  </div>
</template>
<script>
export default {
  name: "Footer",
};
</script>
<style>
footer {
  /* background-color: #18182f; */
  /* background-color: transparent; */
    background-image: linear-gradient(to bottom, #0d0651, #002f75, #005390, #0076a2, #0098af, #00a7b2, #00b6af, #2bc4a8, #00c395, #00c17f, #00be64, #24bb45);

}
.footer-container {
  display: flex;
  justify-content: space-around;
}
</style>
