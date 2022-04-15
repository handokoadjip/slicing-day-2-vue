<template>
  <JumbotronComponent />
  <RenovationComponent />
  <TurnKeyComponent />
  <AddressComponent />
  <MapsComponent />
</template>

<script>
import JumbotronComponent from "@/components/JumbotronComponent.vue";
import RenovationComponent from "@/components/RenovationComponent.vue";
import TurnKeyComponent from "@/components/TurnKeyComponent.vue";
import AddressComponent from "@/components/AddressComponent.vue";
import MapsComponent from "@/components/MapsComponent.vue";

export default {
  name: "HomePage",
  components: {
    JumbotronComponent,
    RenovationComponent,
    TurnKeyComponent,
    AddressComponent,
    MapsComponent,
  },
  mounted() {
    document.title = "Behance | Simplā"
  }
}
</script>
