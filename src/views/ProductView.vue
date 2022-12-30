<script>
import HeaderSection from "@/components/HeaderSection.vue";
import NavComponent from "@/components/NavComponent.vue";
import ProductComponent from "@/components/ProductComponent.vue"

import "@/assets/css/styles.css";

export default {
  name: "HomePage",
  components: {
    HeaderSection,
    NavComponent,
    ProductComponent
  },
};
</script>

<template>
  <HeaderSection></HeaderSection>
  <NavComponent></NavComponent>
  <ProductComponent></ProductComponent>
</template>
