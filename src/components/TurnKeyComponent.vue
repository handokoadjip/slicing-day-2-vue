<template>
  <section class="px-4 my-5 py-5 bg-color-gray">
    <div class="container-fluid">
      <div class="row pt-5">
        <div class="col-lg-7 mb-5 pb-5 mb-lg-0 pb-lg-0">
          <div class="wrapper">
            <div class="pe-0 pe-lg-5">
              <h2 class="fs-2 text-border-top fw-bold mb-5">
                Turn-key solutions
              </h2>
              <p class="fs-5 mb-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet facere delectus
                provident sit quod quos expedita suscipit magni debitis ipsam.</p>
              <p class="fs-5 mb-4">
                Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quos dignissimos vitae ipsa quod. Eius
                accusamus corrupti quos ducimus id, molestiae minima ut quia cum, commodi voluptatum hic quae
                perferendis modi ipsam omnis sed distinctio atque unde facere voluptatibus excepturi adipisci.
              </p>
              <p class="fs-5">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Minus eveniet, ad voluptates
                vero tempore facilis eos harum dolorem quae aliquam fugit saepe labore placeat cum accusamus.
                Repudiandae odit qui recusandae enim quam, voluptate, porro quod optio ratione animi fugiat, cumque
                mollitia autem neque dicta. Voluptatum commodi officiis temporibus? Natus, possimus?</p>
            </div>
          </div>
        </div>
        <div class="col-lg-5">
          <div class="wrapper">
            <div class="pe-0 pe-lg-5">
              <h2 class="fs-2 text-border-top fw-bold mb-5">
                Installation
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
  name: "TurnKeyComponent",
  data() {
    return {
      lists: [
        "Easy and fast",
        "Noise free",
        "Dust free",
        "Lorem",
        "Flexible",
        "dolor sit amet",
        "Lightweight & thin",
        "Fast repair & reposition",
      ]
    }
  }
}
</script>