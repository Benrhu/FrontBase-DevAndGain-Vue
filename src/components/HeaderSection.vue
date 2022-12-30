<script>
export default {
  name: "HeaderSection",
  components: {
  },
};
</script>

<template>
  <div>
    <section id="inicio" class="bg-gray-900 py-24 text-center gradInit">
      <div class="container mx-auto px-4">
        <h1 class="text-4xl font-bold text-white mb-8">
          Bienvenido a tu centro de recursos Dev
        </h1>
        <p class="text-lg text-white mb-8">
          Tienes a tu disposición cartas de ventas, plantillas Front y Back,
          estructuras de proyectos, <br />
          tips diarios y muchos más recursos para mejorar tu calidad <br />y tu
          servicio como profesionalde la programción.
        </p>
        <a
          href="#productos"
          class="bg-white font-bold py-2 px-4 rounded-full shadow-md hover:shadow-lg"
          >Ver productos</a
        >
      </div>
    </section>
  </div>
</template>
