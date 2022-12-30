<script>
export default {
  name: "LoginComponent",
  components: {},
  methods: {
    async login() {
      // Obtener los datos del formulario
      const formData = new FormData(this.$refs.formRef.currentTarget);
      // Enviar la solicitud al servidor
      const response = await fetch("/login", {
        method: "POST",
        body: formData,
      });
      const data = await response.json()
      this. message = data.message
    },
  },
};
</script>

<template>
  <div>
    <section id="login" class="py-24 text-center">
      <h2 class="text-3xl font-bold mb-8">Login</h2>
      <form @submit.prevent="login" class="mx-auto py-10 w-1/3">
        <input
          class="block w-full py-2 px-3"
          type="text"
          name="Email"
          placeholder="Email"
        />
        <input
          class="block w-full py-2 px-3"
          type="text"
          name="Contraseña"
          placeholder="password"
        />
        <button type="submit" class="block w-full py-2 px-3">Enviar</button>
      </form>
    </section>
  </div>
</template>
