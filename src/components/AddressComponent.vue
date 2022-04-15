<template>
  <section class="px-4 my-5 py-5">
    <div class="container-fluid">
      <div class="row justify-content-between pt-5">
        <div class="col-lg-5">
          <div class="wrapper">
            <div class="pe-0 pe-lg-5">
              <h2 class="fw-normal fs-2 text-border-top fw-bold mb-5">
                Simpla SA
              </h2>
              <div class="address mb-5">
                <p class="fs-5 mb-0">Akshya Nagar</p>
                <p class="fs-5 mb-0">1st Block 1st Cross</p>
                <p class="fs-5 mb-0">Rammurthy nagar, Bangalore-560016</p>
              </div>
              <div class="contact">
                <p class="fs-6 mb-0 text-fade-black-1">test@example.com</p>
                <p class="fs-5">+62 896 5057 4913</p>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-3">
          <div class="wrapper d-flex align-items-end h-100">
            <route-link to="#">
              <i class="fas fa-arrow-up fs-2 text-end w-100 text-fade-black-1"></i>
            </route-link>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "AddressComponent",
}
</script>