<template>
  <section class="mt-5 section-popular" id="popular">
    <div class="container">
      <div class="row">
        <div class="content col align-self-center">
          <div class="text-center mb-5">
            <h4>Powerful dengan Limit PHP yang Lebih Besar</h4>
          </div>
          <div class="row d-flex justify-content-around">
            <div>
              <ul class="lists p-0" style="list-style-type:none;">
                <li class="d-flex px-5">
                  <i class="mr-5 mb-0">
                    <img src="../assets/svg/5f21c1fb83e94.png" height="50px" />
                  </i>
                  <p class="mb-0">max execution time 300s</p>
                </li>
                <li class="d-flex px-5">
                  <i class="mr-5 mb-0">
                    <img src="../assets/svg/5f21c1fb83e94.png" height="50px" />
                  </i>
                  <p class="mb-0">max execution time 300s</p>
                </li>
                <li class="d-flex px-5">
                  <i class="mr-5 mb-0">
                    <img src="../assets/svg/5f21c1fb83e94.png" height="50px" />
                  </i>
                  <p class="mb-0">php memory limit 1024 MB</p>
                </li>
              </ul>
            </div>
            <div>
              <ul class="lists p-0" style="list-style-type:none;">
                <li class="d-flex px-5">
                  <i class="mr-5 mb-0">
                    <img src="../assets/svg/5f21c1fb83e94.png" height="50px" />
                  </i>
                  <p class="mb-0">post max size 128 MB</p>
                </li>
                <li class="d-flex px-5">
                  <i class="mr-5 mb-0">
                    <img src="../assets/svg/5f21c1fb83e94.png" height="50px" />
                  </i>
                  <p class="mb-0">upload max filesize 128 MB</p>
                </li>
                <li class="d-flex px-5">
                  <i class="mr-5 mb-0">
                    <img src="../assets/svg/5f21c1fb83e94.png" height="50px" />
                  </i>
                  <p class="mb-0">max input vars 2500</p>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped>
ul {
  border: 1px solid #d3d3d3;
}

li p {
  font-size: 30px;
}

li:nth-child(odd) {
  background-color: #fff;
}

li:nth-child(even) {
  background-color: #ebebeb;
}
</style>