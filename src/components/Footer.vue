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
  background-color: #18182f;
}
.footer-container {
  display: flex;
  justify-content: space-around;
}
</style>
