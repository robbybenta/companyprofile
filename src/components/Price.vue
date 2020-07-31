<template>
  <section class="mt-5 section-popular" id="popular">
    <div class="container">
      <div class="row">
        <div class="col text-center section-popular-heading">
          <h5>Paket Hosting Singapura yang Tepat</h5>
          <p>Diskon 40% Domain dan SSL Gratis Undtuk Anda</p>
          <div class="row justify-content-center">
            <div class="col-md-4">
              <div
                class="card border-secondary mb-3"
                style="max-width: 18rem;"
                v-for="(price, index) in prices"
                :key="index"
              >
                <div class="card-header">
                  <h3><b>Bayi</b></h3>
                </div>
                <div class="card-body text-secondary">
                  <ul class="list-group list-group-flush">
                    <li class="list-group-item">
                      <h2 class="card-title text-dark">
                        {{ price.price.gross.value }}/bln
                      </h2>
                    </li>
                    <li class="list-group-item">938 Pengguna terdaftar</li>
                    <li class="list-group-item">
                      <h5>
                        0.5X Resource Power Some quick example text to build on
                        the card title and make up the bulk of the card's
                        content.
                      </h5>
                    </li>
                  </ul>
                  <button
                    type="button"
                    class="btn btn-primary col-md-12 rounded-pill"
                  >
                    Primary
                  </button>
                </div>
              </div>
            </div>
            <div class="col-md-4">
              <div
                class="card border-secondary mb-3"
                style="max-width: 18rem;"
                v-for="(price, index) in prices"
                :key="index"
              >
                <div class="card-header">
                  <h3><b>Pelajar</b></h3>
                </div>
                <div class="card-body text-secondary">
                  <ul class="list-group list-group-flush">
                    <li class="list-group-item">
                      <h2 class="card-title text-dark">
                        {{ price.price.vat.value }}/bln
                      </h2>
                    </li>
                    <li class="list-group-item">938 Pengguna terdaftar</li>
                    <li class="list-group-item">
                      <h5>
                        0.5X Resource Power Some quick example text to build on
                        the card title and make up the bulk of the card's
                        content.
                      </h5>
                    </li>
                  </ul>
                  <button
                    type="button"
                    class="btn btn-primary col-md-12 rounded-pill"
                  >
                    Primary
                  </button>
                </div>
              </div>
            </div>
            <div class="col-md-4">
              <div
                class="card border-secondary mb-3"
                style="max-width: 18rem;"
                v-for="(price, index) in prices"
                :key="index"
              >
                <div class="card-header">
                  <h3><b>personal</b></h3>
                </div>
                <div class="card-body text-secondary">
                  <ul class="list-group list-group-flush">
                    <li class="list-group-item">
                      <h2 class="card-title text-dark">
                        {{ price.price.net.value }}/bln
                      </h2>
                    </li>
                    <li class="list-group-item">938 Pengguna terdaftar</li>
                    <li class="list-group-item">
                      <h5>
                        0.5X Resource Power Some quick example text to build on
                        the card title and make up the bulk of the card's
                        content.
                      </h5>
                    </li>
                  </ul>
                  <button
                    type="button"
                    class="btn btn-primary col-md-12 rounded-pill"
                  >
                    Primary
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default { props: ['prices'] }
</script>

<style></style>
