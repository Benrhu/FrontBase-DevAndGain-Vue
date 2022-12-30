<script>
import "@/assets/css/tailwind.css";

export default {
  name: "NewsComponent",
  components: {},
};
</script>

<template>
  <div>
    <section id="productos" class="py-24 text-center">
      <h2 class="text-3xl font-bold mb-8">Nuestras novedades</h2>

      <div class="w-100 px-40 justify-items-center flex gap-5">
        <!-- Tarjeta de producto -->
        <div class="text-center bg-white rounded-lg shadow-lg">
          <img
            src="@/assets/img/chatgpt-banner.jpg"
            alt=""
            class="h-60 w-full rounded-t-lg"
          />
          <div class="p-6">
            <h3 class="text-xl font-bold mb-4">Tutorial ChatGPT</h3>
            <p class="text-gray-700 mb-4">
              Te enseño ćomo usar desde 0 ChatGPT para desarrollar el proyecto
              que quieras.
            </p>
            <router-link to="/products" class="inline-block bg-indigo-500 text-white font-bold py-2 px-4 rounded-full hover:bg-indigo-600"
            >Ver más</router-link>
          </div>
        </div>
        <!-- Tarjeta de producto -->

        <div class="text-center bg-white rounded-lg shadow-lg">
          <img
            src="@/assets/img/restful-api.jpg"
            alt=""
            class="h-60 w-full rounded-t-lg"
          />
          <div class="p-6">
            <h3 class="text-xl font-bold mb-4">
              RESTFul API tutorial + código
            </h3>
            <p class="text-gray-700 mb-4">
              Te enseño cómo desarrollar una API senciilla con NodeJS, Express y
              MongoDB.
            </p>
            <router-link to="/products" class="inline-block bg-indigo-500 text-white font-bold py-2 px-4 rounded-full hover:bg-indigo-600"
            >Ver más</router-link>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>
