<template>
  <div id="app">
    <NavbarPromotion />
    <Navbar />
  </div>
</template>

<script>
import Navbar from "@/components/Navbar.vue";
import NavbarPromotion from "@/components/NavbarPromotion.vue";
export default {
  name: "App",
  components: { NavbarPromotion, Navbar },
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
