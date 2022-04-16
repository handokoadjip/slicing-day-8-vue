<template>
  <header>
    <nav class="navbar navbar-expand-lg fixed-top navbar-light">
      <div class="container d-flex justify-content-between">
        <router-link class="navbar-brand text-center text-uppercase mp-0" to="#">
          Proccess
        </router-link>

        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav text-uppercase ms-auto">
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-center" aria-current="page" to="#">project</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-center" to="#">servies</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-center" to="#">about</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-center" to="#">proccess</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-center" to="#">news</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-center" to="#">contact</router-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <div class="container">
      <div class="row min-vh-100 pt-5">
        <div class="col-lg-10">
          <div class="wrapper d-flex align-items-center h-100">
            <div class="w-100">
              <h1 class="text-navbar border-bottom-fade-black-1-2px pb-4 fw-normal">Proccess</h1>
              <div class="row">
                <div class="offset-lg-5 col-lg-7 p-3 p-lg-0">
                  <p class="ms-auto pt-4 fs-5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Officia
                    perspiciatis
                    at voluptas iure ipsa numquam sequi expedita laudantium dicta, pariatur modi voluptates earum, illum
                    facere quaerat. Tenetur neque similique dolorum aliquid. Voluptate iusto voluptates, eveniet sit id
                    quis
                    iste placeat illo commodi vero, eius incidunt? Eligendi explicabo dicta id reprehenderit.</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "HeaderComponent",
}
</script>

