<template>
  <div id="app">
    <NavbarPromotion />
    <Navbar />
    <Feature />
    <Technologies />
    <Price />
    <Performance />
  </div>
</template>

<script>
import Performance from "@/components/Performance.vue";
import Price from "@/components/Price.vue";
import Technologies from "@/components/Technologies.vue";
import Feature from "@/components/Feature.vue";
import Navbar from "@/components/Navbar.vue";
import NavbarPromotion from "@/components/NavbarPromotion.vue";
export default {
  name: "App",
  components: {
    NavbarPromotion,
    Navbar,
    Feature,
    Technologies,
    Price,
    Performance,
  },
};
</script>

<style>
.nav-link {
  font-size: 10px;
}

.discount p {
  font-size: 12px;
}
</style>
