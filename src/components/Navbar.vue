
<template>
  <div id="app">
    <nav class="navigation navbar navbar-expand-lg navbar-light">
      <div class="container px-1">
        <a class="navbar-brand" href="#">
          <img src="../assets/svg/niagahoster-logo.png" width="250" alt srcset />
        </a>
        <button
          class="navbar-toggler"
          type="button"
          data-toggle="collapse"
          data-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav menu ml-auto align-self-center">
            <li v-for="tag in tags" :key="tag" class="nav-item active align-self-center">
              <a class="nav-link" href="#">{{tag.menu}}</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      tags: [
        { menu: "Hosting" },
        { menu: "Domain" },
        { menu: "Server" },
        { menu: "Website" },
        { menu: "Afiliasi" },
        { menu: "Promo" },
        { menu: "Pembayaran" },
        { menu: "Review" },
        { menu: "Kontak" },
        { menu: "Blog" },
      ],
    };
  },
};
</script>

<style >
.font10 {
  font-size: 10px;
}

.font12 {
  font-size: 12px;
}

.navigation {
  border-bottom: 1px solid #d3d3d3;
  height: 90px;
}
.menu li a {
  font-size: 17px;
}
</style>
