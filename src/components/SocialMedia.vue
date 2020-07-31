<template>
  <div id="app">
    <div class="py-3 background border-bottom navbar py-1 navbar-expand-lg navbar-light">
      <div class="container">
        <div class="d-flex">
          <a class="navbar-brand d-flex py-0" href="#">
            <p class="text-dark mb-0 my-auto font16">Bagikan jika Anda menyukai halaman ini</p>
          </a>
        </div>
        <div class="collapse navbar-collapse justify-content-around" id="navbarSupportedContent">
          <ul class="navbar-nav">
            <li class="nav-item d-flex align-items-center px-3">
              <img src="../assets/images/facebook.svg" width="30" height="50" />
              <a class="nav-link font12 mb-0" href="#">80</a>
            </li>
            <li class="nav-item d-flex align-items-center px-3">
              <img src="../assets/images/twitter.svg" width="30" height="50" />
              <a class="nav-link font12 mb-0" href="#">450</a>
            </li>
            <li class="nav-item d-flex align-items-center px-3">
              <img src="../assets/images/google-plus.svg" width="30" height="50" />
              <a class="nav-link font12 mb-0" href="#">1900</a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
  components: {},
};
</script>

<style >
.background {
  background-color: #f1f0f0;
}
.font16 {
  font-size: 16px;
}

.font12 {
  font-size: 12px;
  border: 1px solid #d3d3d3;
}
</style>
