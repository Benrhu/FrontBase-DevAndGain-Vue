<script>
import NavComponent from "@/components/NavComponent.vue";
import ContactComponent from "@/components/ContactComponent.vue";
import "@/assets/css/styles.css";

export default {
  name: "ContactPage",
  components: {
    NavComponent,
    ContactComponent
  },
}
</script>

<template>
  <NavComponent></NavComponent>
  <ContactComponent></ContactComponent>
  
</template>
