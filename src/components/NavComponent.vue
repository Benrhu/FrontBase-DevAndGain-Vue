<script>
import "@/assets/css/tailwind.css";
import "@/assets/css/styles.css";

export default {
  name: "NavComponent",
  components: {},
};
</script>

<template>
  <nav class="fixed top-0 left-0 right-0 z-50">
    <div class="container mx-auto px-4 py-6 flex">
      <a href="/index.html" class="text-lg font-bold text-white">DevAndGain</a>
      <ul class="flex mx-auto">
        <li>
          <router-link to="/" class="px-3 py-2 font-semibold text-white rounded-full hover:bg-gray-800"
            >Inicio</router-link
          >
        </li>
        <li>
          <router-link to="/products" class="px-3 py-2 font-semibold text-white rounded-full hover:bg-gray-800"
            >Productos</router-link
          >
        </li>
        <li>
          <router-link to="/contact" class="px-3 py-2 font-semibold text-white rounded-full hover:bg-gray-800"
            >Contacto</router-link
          >
        </li>
      </ul>
      <div class="">
        <router-link to="/register" class="bg-white mr-3 font-bold py-3 px-4 rounded-full shadow-md hover:shadow-lg"
            >Registro</router-link
          >
          <router-link to="/login" class="bg-white mr-3 font-bold py-3 px-4 rounded-full shadow-md hover:shadow-lg"
            >Login</router-link
          >
      </div>
    </div>
  </nav>
</template>
