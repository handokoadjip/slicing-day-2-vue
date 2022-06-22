<template>
  <header class="position-relative">
    <nav class="navbar fixed-top navbar-light px-4">
      <div class="container-fluid">
        <router-link class="navbar-brand text-center mp-0 fw-bolder fs-1 ff-karla ls--3px" to="#">
          Simplā
        </router-link>

        <button class="navbar-toggler ms-auto" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse mt-3" id="navbarNav">
          <ul class="navbar-nav text-uppercase ms-auto">
            <li class="nav-item px-0">
              <router-link class="nav-link text-end" aria-current="page" to="#">work</router-link>
            </li>
            <li class="nav-item px-0">
              <router-link class="nav-link text-end" to="#">home</router-link>
            </li>
            <li class="nav-item px-0">
              <router-link class="nav-link text-end" to="#">about</router-link>
            </li>
            <li class="nav-item px-0">
              <router-link class="nav-link text-end" to="#">contact</router-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <section class="px-4">
      <div class="container-fluid">
        <div class="row min-vh-70 pt-5">
          <div class="col-lg-9">
            <div class="wrapper d-flex align-items-end h-100">
              <div class="w-100">
                <h1 class="fw-normal fs-2 mp-0 text-border-top">
                  We help architects, interior designer and building answer to transform, renovate and create amazing
                  spaces, Simpla.
                </h1>
              </div>
            </div>
          </div>
          <div class="col-lg-3">
            <div class="wrapper d-flex align-items-end h-100">
              <router-link to="#">
                <i class="fas fa-arrow-down fs-2 text-end w-100 text-fade-black-1"></i>
              </router-link>
            </div>
          </div>
        </div>
      </div>
    </section>
  </header>
</template>

<script>
export default {
  name: "HeaderComponent",
}
</script>

