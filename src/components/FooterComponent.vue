<template>
  <footer class="py-5">
    <div class="container border-top-fade-black-1-2px">
      <div class="row w-100 pt-5">
        <div class="col-lg-3 mb-5 mb-lg-0">
          <div class="wrapper text-center text-lg-start text-uppercase">
            <h3 class="fs-6 mb-4">proccess</h3>
          </div>
        </div>
        <div class="col-lg-3 mb-5 mb-lg-0">
          <div class="wrapper text-center text-lg-start">
            <nav class="text-uppercase">
              <router-link class="text-fade-1 text-decoration-none mb-1 d-block" to="#">project</router-link>
              <router-link class="text-fade-1 text-decoration-none mb-1 d-block" to="#">services</router-link>
              <router-link class="text-fade-1 text-decoration-none mb-1 d-block" to="#">about</router-link>
              <router-link class="text-fade-1 text-decoration-none mb-1 d-block" to="#">proccess</router-link>
              <router-link class="text-fade-1 text-decoration-none mb-1 d-block" to="#">news</router-link>
              <router-link class="text-fade-1 text-decoration-none mb-1 d-block" to="#">contact</router-link>
            </nav>
          </div>
        </div>
        <div class="col-lg-3 mb-5 mb-lg-0">
          <div class="wrapper text-center text-lg-start">
            <nav class="text-uppercase">
              <router-link class="text-fade-1 text-decoration-none mb-1 d-block" to="#">lorem</router-link>
              <router-link class="text-fade-1 text-decoration-none mb-1 d-block" to="#">ipsum</router-link>
              <router-link class="text-fade-1 text-decoration-none mb-1 d-block" to="#">dolor</router-link>
              <router-link class="text-fade-1 text-decoration-none mb-1 d-block" to="#">sit</router-link>
            </nav>
          </div>
        </div>
        <div class="col-lg-3 mb-5 mb-lg-0">
          <router-link class="text-fade-1 text-decoration-none mb-1 d-block text-center text-lg-start" to="#">Lorem ipsum dolor
            sit amet.</router-link>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "FooterComponent",
}
</script>