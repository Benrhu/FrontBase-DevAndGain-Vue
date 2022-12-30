<script>
import "@/assets/css/tailwind.css";
import "@/assets/css/styles.css";

export default {
  name: "ContactComponent",
  components: {},
};
</script>

<template>
  <section id="contacto" class="text-center py-24">
    <div class="mx-auto w-50">
      <h2 class="text-3xl font-bold mb-8">Contacto</h2>
      <div class="container justify-items-center">
        <!-- Formulario de contacto -->
        <form action="https://formsubmit.co/your@email.com" method="POST" class="bg-white rounded-lg shadow-lg p-6">
          <div class="mb-4">
            <label for="nombre" class="text-gray-700 font-bold mb-2"
              >Nombre y apellido</label
            >
            <input
              type="text"
              name="nombreYapellido"
              class="py-2 px-3 rounded-lg shadow-sm"
              placeholder="Escribe tu nombre y tu primero apellido"
            />
          </div>
          <div class="mb-4">
            <label for="empresa" class="text-gray-700 font-bold mb-2"
              >Empresa</label
            >
            <input
              type="text"
              name="empresa"
              class="py-2 px-3 rounded-lg shadow-sm"
              placeholder="Escribe el nombre de tu empresa"
            />
          </div>
          <div class="mb-4">
            <label for="email" class="text-gray-700 font-bold mb-2"
              >Email</label
            >
            <input
              type="text"
              name="email"
              class="py-2 px-3 rounded-lg shadow-sm"
              placeholder="Escribe tu email"
            />
          </div>
          <div class="mb-4">
            <label for="mensaje" class="text-gray-700 font-bold mb-2"
              >Mensaje</label
            >
            <input
              type="text"
              name="mensaje"
              class="py-2 px-3 rounded-lg shadow-sm"
              placeholder="Escribe tu mensaje"
            />
          </div>
        </form>
      </div>
    </div>
  </section>
</template>
