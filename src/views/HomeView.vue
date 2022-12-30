<script>
import HeaderSection from "@/components/HeaderSection.vue";
import NewsComponent from "@/components/NewsComponent.vue";
import NavComponent from "@/components/NavComponent.vue";
import TestimonialComponent from "@/components/TestimonialsComponent.vue"
import FaqComponent from "@/components/FaqComponent.vue";
import "@/assets/css/styles.css";

export default {
  name: "HomePage",
  components: {
    HeaderSection,
    NewsComponent,
    NavComponent,
    TestimonialComponent,
    FaqComponent
  },
};
</script>

<template>
  <HeaderSection></HeaderSection>
  <NewsComponent></NewsComponent>
  <NavComponent></NavComponent>
  <TestimonialComponent></TestimonialComponent>
  <FaqComponent></FaqComponent>
</template>
