<script>
export default {
  name: "FaqComponenet",
  components: {},
};
</script>

<template>
  <section id="preguntas" class="text-center py-24">
    <div class="container mx-auto px-4">
      <h2 class="text-3xl font-bold mb-8">Preguntas frecuentes</h2>
      <!-- Acordeón -->
      <div class="accordion">
        <div class="accordion-item">
          <input type="checkbox" id="item-1" name="accordion" hidden />
          <label for="item-1" class="accordion-title"
            >¿Quién desarrolla el código de los productos</label
          >
          <div class="accordion-content">
            <p>
              Los productos son desarrollados tanto por elfundador, como por el
              equipo que se ha ido incorporando mediante el Discord
            </p>
          </div>
        </div>
        <div class="accordion-item">
          <input type="checkbox" id="item-2" name="accordion" hidden />
          <label for="item-2" class="accordion-title"
            >¿Los productos son gratis?</label
          >
          <div class="accordion-content">
            <p>
              Tienes a tu disposición una variedad de productos gratuitos y de
              pago.
            </p>
          </div>
        </div>
        <div class="accordion-item">
          <input type="checkbox" id="item-2" name="accordion" hidden />
          <label for="item-2" class="accordion-title"
            >¿Qué productos puedo encontrar?</label
          >
          <div class="accordion-content">
            <p>
              Algunos de los productos que tienes a tu disposición son: cartas
              de ventas, estructuras de proyectos def ront y de back, módulos de
              backend ya pre-desarrollados, tutoriales de ChatGPT y mucho más
            </p>
          </div>
        </div>
        <div class="accordion-item">
          <input type="checkbox" id="item-2" name="accordion" hidden />
          <label for="item-2" class="accordion-title"
            >¿Puedo ganar dinero con DevAndGain?</label
          >
          <div class="accordion-content">
            <p>
              Sí, en el caso de que formes parte del equipo de desarrollo de DAG
              y alguno de los productos que has desarrollado o has ayudado a
              desarrollar se vende, obtienes tu comisión como desarrollador
            </p>
          </div>
        </div>
        <!-- Más preguntas y respuestas aquí -->
      </div>
    </div>
  </section>
</template>
