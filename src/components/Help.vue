<template>
  <div id="app">
    <div class="py-4 color navbar py-1 navbar-expand-lg navbar-light">
      <div class="container">
        <div class="d-flex">
          <a class="navbar-brand d-flex py-0" href="#">
            <p class="text-white mb-0 my-auto font25">
              Perlu
              <b>BANTUAN?</b>
              Hubungi Kami :
              <b>0274-5305505</b>
            </p>
          </a>
        </div>
        <div class="collapse navbar-collapse justify-content-around" id="navbarSupportedContent">
          <button
            type="button "
            class="change w-50 text-center btn rounded-pill font-weight-bold text-light btn-outline-light btn-lg"
          >
            <img class="chat mr-auto" src="../assets/images/conversation.svg" alt srcset /> Live Chat
          </button>
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
.color {
  background-color: #007bff;
}
.font25 {
  font-size: 25px;
}

.font15 {
  font-size: 15px;
}

.chat {
  height: 36px;
  width: auto;
}
</style>
