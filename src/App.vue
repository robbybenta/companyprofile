<template>
  <div id="app">
    <NavbarPromotion />
    <Navbar />
    <Feature />
    <Technologies />
    <Price :prices="prices" />
    <Performance />
    <Package />
    <Support />
    <Modul />
    <Linux />
    <SocialMedia />
    <Help />
    <Footer />
  </div>
</template>

<script>
import axios from 'axios'
import Footer from '@/components/Footer.vue'
import Help from '@/components/Help.vue'
import SocialMedia from '@/components/SocialMedia.vue'
import Linux from '@/components/Linux.vue'
import Modul from '@/components/Modul.vue'
import Support from '@/components/Support.vue'
import Package from '@/components/Package.vue'
import Performance from '@/components/Performance.vue'
import Price from '@/components/Price.vue'
import Technologies from '@/components/Technologies.vue'
import Feature from '@/components/Feature.vue'
import Navbar from '@/components/Navbar.vue'
import NavbarPromotion from '@/components/NavbarPromotion.vue'
export default {
  name: 'App',
  data () {
    return {
      client_id: 864,
      product_id: 97771,
      prices: {
        price: []
      }
    }
  },
  components: {
    Footer,
    Help,
    SocialMedia,
    Linux,
    Modul,
    Support,
    NavbarPromotion,
    Navbar,
    Feature,
    Technologies,
    Price,
    Performance,
    Package
  },
  mounted () {
    axios
      .get('https://pricingapi.cleverbridge.com/prices', {
        params: {
          client_id: 864,
          product_id: 97771
        }
      })
      .then(res => (this.prices = res.data))
      .catch(err => console.log(err))
  }
}
</script>

<style>
body {
  overflow-x: hidden;
}
.nav-link {
  font-size: 10px;
}

.discount p {
  font-size: 12px;
}
</style>
