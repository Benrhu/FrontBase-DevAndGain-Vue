<script>
import NavComponent from "@/components/NavComponent.vue";
import RegisterComponent from "@/components/RegisterComponent.vue";
import "@/assets/css/styles.css";

export default {
  name: "RegisterPage",
  components: {
    NavComponent,
    RegisterComponent,
  },
};
</script>

<template>
  <NavComponent></NavComponent>
  <RegisterComponent></RegisterComponent>
</template>
