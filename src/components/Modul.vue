<template>
  <section class="mt-5 section-popular" id="popular">
    <div class="container">
      <div class="row">
        <div class="content col align-self-center">
          <div class="text-center mb-5">
            <h4>Modul Lengkap untuk Menjalankan Aplikasi PHP Anda</h4>
          </div>
          <div class="row d-flex justify-content-around">
            <div>
              <ul class="lists p-0" style="list-style-type:none;">
                <li v-for="modul in modules" :key="modul" class="align-self-center">
                  <a class="text-dark">{{modul.menu}}</a>
                </li>
              </ul>
            </div>
            <div>
              <ul class="lists p-0" style="list-style-type:none;">
                <li v-for="modul in modules" :key="modul" class="align-self-center">
                  <a class="text-dark">{{modul.menu}}</a>
                </li>
              </ul>
            </div>
            <div>
              <ul class="lists p-0" style="list-style-type:none;">
                <li v-for="modul in modules" :key="modul" class="align-self-center">
                  <a class="text-dark">{{modul.menu}}</a>
                </li>
              </ul>
            </div>
            <div>
              <ul class="lists p-0" style="list-style-type:none;">
                <li v-for="modul in modules" :key="modul" class="align-self-center">
                  <a class="text-dark">{{modul.menu}}</a>
                </li>
              </ul>
            </div>
          </div>
          <div class="text-center my-4">
            <button
              type="button"
              class="text-dark font-weight-bolder btn outline btn-outline-secondary"
            >Selengkapnya</button>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      modules: [
        { menu: "IcePHP" },
        { menu: "apc" },
        { menu: "apcu" },
        { menu: "apm" },
        { menu: "ares" },
        { menu: "bcmath" },
        { menu: "bcompiler" },
        { menu: "big_int" },
        { menu: "bitset" },
        { menu: "Bloomy" },
        { menu: "Bz2_filter" },
        { menu: "clamav" },
        { menu: "coin_acceptor" },
        { menu: "crack" },
        { menu: "dba" },
      ],
    };
  },
};
</script>


<style scoped>
.outline {
  outline: #d3d3d3;
  border: 1px solid;
  border-radius: 20px;
  width: 200px;
}
</style>