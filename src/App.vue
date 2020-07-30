<template>
  <div id="app">
    <NavbarPromotion />
    <Navbar />
    <Feature />
    <Technologies />
    <Price />
    <Performance />
    <Package />
  </div>
</template>

<script>
import Package from "@/components/Package.vue";
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
    Package,
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

@media (min-width: 500px) {
  .wrapper {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    grid-gap: 16px;
  }
}

.card {
  display: flex; /* [1] */
  flex-direction: column; /* [2] */
}

.card__content {
  flex-grow: 1; /* [3] */
  display: flex; /* [4] */
  flex-direction: column;
}

.card__link {
  margin-top: auto; /* [5] */
}
</style>
