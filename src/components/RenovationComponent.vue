<template>
  <section class="px-4 my-5 py-5">
    <div class="container-fluid">
      <div class="row">
        <div class="col-lg-7 mb-5 pb-5 mb-lg-0 pb-lg-0">
          <div class="wrapper">
            <div class="pe-0 pe-lg-5">
              <h2 class="fs-2 text-border-top fw-bold mb-5">
                Renovation made Simpla
              </h2>
              <p class="fs-5 mb-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet facere delectus
                provident sit quod quos expedita suscipit magni debitis ipsam.</p>
              <p class="fs-5">
                Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quos dignissimos vitae ipsa quod. Eius
                accusamus corrupti quos ducimus id, molestiae minima ut quia cum, commodi voluptatum hic quae
                perferendis modi ipsam omnis sed distinctio atque unde facere voluptatibus excepturi adipisci.
              </p>
            </div>
          </div>
        </div>
        <div class="col-lg-5">
          <div class="wrapper">
            <div class="pe-0 pe-lg-5">
              <h2 class="fs-2 text-border-top fw-bold mb-5">
                Areas of expertise
              </h2>
              <div v-for="(list, index) in lists" :key="index">
                <p class="fs-5 list-text">{{list}}</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "RenovationComponent",
  data() {
    return {
      lists: [
        "Interior finishing",
        "Glass finishing",
        "Lighting",
        "Financial audit",
        "Design & application",
      ]
    }
  }
}
</script>