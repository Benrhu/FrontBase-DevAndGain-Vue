<script>
export default {
  name: "TestimonialComponenet",
  components: {},
};
</script>

<template>
    <div>
        <section id="testimonios" class="gradTestimonials text-center py-24 bg-gray-900">
      <div class=" mx-auto px-4">
        <h2 class="text-3xl font-bold text-white mb-8">Testimonios</h2>
        <div class="w-100 px-40 justify-items-center grid md:grid-cols-2 gap-5">
          <!-- Tarjeta de testimonio -->
          <div class="justify-items-center bg-white rounded-lg shadow-lg p-6">
            <p class="text-gray-700 mb-4">"Trabajar con Rubén es sencillo y rápido. Es un gran profesional y muy
              metodico en todo lo que lleva a cabo. Seguramente que encargue la App a su equipo.
            </p>
            <div class="flex items-center justify-between">
              <img src="@/assets/img/face1.jpg" alt="" class="h-12 w-12 rounded-full mr-4">
              <div class="text-gray-800">
                <h4 class="font-bold mb-1">Juan Pérez</h4>
                <p class="text-sm">Empresario de la automoción</p>
              </div>
            </div>
          </div>
          <!-- Tarjeta de testimonio -->
          <div class="bg-white rounded-lg shadow-lg p-6">
            <p class="text-gray-700 mb-4">"Rubén me dijo que iba a crear una web para ayudar a otros "devs" a conseguir
              clientes entregando calidad. No sé que tiene entre manos, pero estoy segura de que será de alta calidad,
              viniendo de él.
            </p>
            <div class="flex items-center justify-between">
              <img src="@/assets/img/face2.jpg" alt="" class="h-12 w-12 rounded-full mr-4">
              <div class="text-gray-800">
                <h4 class="font-bold mb-1">Olaya Santos</h4>
                <p class="text-sm">Empresaria de la Comunicación y el sector de la Belleza</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    </div>
</template>