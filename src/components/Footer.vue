<template>
  <!-- Site footer -->
  <footer class="site-footer">
    <div class="container">
      <div class="row">
        <div class="col-sm-3 col-md-3">
          <h6>HUBUNGI KAMI</h6>
          <ul class="footer-links">
            <li>
              <a>0274-5305505</a>
            </li>
            <li>
              <a>Senin - minggu</a>
            </li>
            <li>
              <a>24 jam nonstop</a>
            </li>
            <br />
            <li>
              <a>Jl. Selokan Matraman Monjali</a>
            </li>
            <li>
              <a>Karangjati MT I/304</a>
            </li>
            <li>
              <a>Sinduadi, Miati, Sleman</a>
            </li>
            <li>
              <a>Yogyakarta 55284</a>
            </li>
          </ul>
        </div>

        <div class="col-xs-3 col-md-3">
          <h6>LAYANAN</h6>
          <ul class="footer-links">
            <li>
              <a>Domain</a>
            </li>
            <li>
              <a>Shared Hosting</a>
            </li>
            <li>
              <a>Cloud VPS Hosting</a>
            </li>
            <li>
              <a>Managed VPS Hosting</a>
            </li>
            <li>
              <a>Web Builder</a>
            </li>
            <li>
              <a>Keamanan SSL / HTTPS</a>
            </li>
            <li>
              <a>Jasa Pembuatan Website</a>
            </li>
            <li>
              <a>Progam Afiliasi</a>
            </li>
          </ul>
        </div>

        <div class="col-xs-3 col-md-3">
          <h6>SERVICE HOSTING</h6>
          <ul class="footer-links">
            <li>
              <a>Hosting Murah</a>
            </li>
            <li>
              <a>Hosting Indonesia</a>
            </li>
            <li>
              <a>Hosting Singapura SG</a>
            </li>
            <li>
              <a>Hosting PHP</a>
            </li>
            <li>
              <a>Hosting Wordpress</a>
            </li>
            <li>
              <a>Hosting Laravel</a>
            </li>
          </ul>
        </div>

        <div class="col-xs-3 col-md-3">
          <h6>TUTORIAL</h6>
          <ul class="footer-links">
            <li>
              <a>Knowledgebase</a>
            </li>
            <li>
              <a>Blog</a>
            </li>
            <li>
              <a>Cara Pembayaran</a>
            </li>
          </ul>
        </div>
      </div>
      <div class="row">
        <div class="col-sm-3 col-md-3">
          <h6>TENTANG KAMI</h6>
          <ul class="footer-links">
            <li>
              <a>Tim Niagahoster</a>
            </li>
            <li>
              <a>Karir</a>
            </li>
            <li>
              <a>Events</a>
            </li>
            <li>
              <a>Penawaran & Promo Spesial</a>
            </li>
            <li>
              <a>Kontak kami</a>
            </li>
          </ul>
        </div>

        <div class="col-xs-3 col-md-3">
          <h6>KENAPA PILIH NIAGA HOSTER?</h6>
          <ul class="footer-links">
            <li>
              <a>Support Terbaik</a>
            </li>
            <li>
              <a>Garansi Harga Termurah</a>
            </li>
            <li>
              <a>Domain Gratis Selamanya</a>
            </li>
            <li>
              <a>Datacenter Hosting Terbaik</a>
            </li>
            <li>
              <a>Review Pelanggan</a>
            </li>
          </ul>
        </div>

        <div class="col-xs-3 col-md-3">
          <h6>NEWSLETTER</h6>
          <ul class="footer-links">
            <div class="input-group mb-3">
              <input
                type="text"
                class="form-control rounded-pill"
                placeholder="Email"
                aria-label="Recipient's username"
                aria-describedby="button-addon2"
              />
              <div class="input-group-append">
                <button
                  class="btn btn-outline-secondary rounded-pill"
                  type="button"
                  id="button-addon2"
                >Berlangganan</button>
              </div>
            </div>
            <li>
              <a>Dapatkan promo dan konten menarik dari penyedia hosting terbaik Anda</a>
            </li>
          </ul>
        </div>

        <div class="col-xs-3 col-md-3">
          <h6>Quick Links</h6>
          <ul class="footer-links"></ul>
        </div>
      </div>
      <hr />
    </div>
    <div class="container">
      <div class="row">
        <div class="col-md-8 col-sm-6 col-xs-12">
          <p class="copyright-text">Pembayaran</p>
          <button class="btn btn-primary btn-lg w-100"></button>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style>
.site-footer {
  background-color: #26272b;
  padding: 45px 0 20px;
  font-size: 15px;
  line-height: 24px;
  color: #737373;
}
.site-footer hr {
  opacity: 0.5;
}
.site-footer hr.small {
  margin: 20px 0;
}
.site-footer h6 {
  font-size: 16px;
  margin-top: 5px;
  letter-spacing: 2px;
}
.site-footer a {
  color: #737373;
}
.site-footer a:hover {
  color: #3366cc;
  text-decoration: none;
}
.footer-links {
  padding-left: 0;
  list-style: none;
}
.footer-links li {
  display: block;
}
.footer-links a {
  color: #737373;
}

.site-footer .social-icons {
  text-align: right;
}
.site-footer .social-icons a {
  width: 40px;
  height: 40px;
  line-height: 40px;
  margin-left: 6px;
  margin-right: 0;
  border-radius: 100%;
  background-color: #33353d;
}
.copyright-text {
  margin: 0;
}
@media (max-width: 991px) {
  .site-footer [class^="col-"] {
    margin-bottom: 30px;
  }
}
@media (max-width: 767px) {
  .site-footer {
    padding-bottom: 0;
  }
  .site-footer .copyright-text,
  .site-footer .social-icons {
    text-align: center;
  }
}
.social-icons {
  padding-left: 0;
  margin-bottom: 0;
  list-style: none;
}
.social-icons li {
  display: inline-block;
  margin-bottom: 4px;
}
.social-icons li.title {
  margin-right: 15px;
  text-transform: uppercase;
  color: #96a2b2;
  font-weight: 700;
  font-size: 13px;
}
.social-icons a {
  background-color: #eceeef;
  color: #818a91;
  font-size: 16px;
  display: inline-block;
  line-height: 44px;
  width: 44px;
  height: 44px;
  text-align: center;
  margin-right: 8px;
  border-radius: 100%;
  -webkit-transition: all 0.2s linear;
  -o-transition: all 0.2s linear;
  transition: all 0.2s linear;
}
.social-icons a:active,
.social-icons a:focus,
.social-icons a:hover {
  color: #fff;
  background-color: #29aafe;
}
.social-icons.size-sm a {
  line-height: 34px;
  height: 34px;
  width: 34px;
  font-size: 14px;
}
.social-icons a.facebook:hover {
  background-color: #3b5998;
}
.social-icons a.twitter:hover {
  background-color: #00aced;
}
.social-icons a.linkedin:hover {
  background-color: #007bb6;
}
.social-icons a.dribbble:hover {
  background-color: #ea4c89;
}
@media (max-width: 767px) {
  .social-icons li.title {
    display: block;
    margin-right: 0;
    font-weight: 600;
  }
}
</style>