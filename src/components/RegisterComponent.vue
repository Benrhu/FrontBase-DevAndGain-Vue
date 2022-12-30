<script>
export default {
  methods: {
    async onSubmit() {
      // Obtener los datos del formulario
      const formData = new FormData(this.$refs.formRef.currentTarget);
      // Enviar la solicitud al servidor
      const response = await fetch("/register", {
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
    <section id="register" class="py-24 text-center">
      <h2 class="text-3xl font-bold mb-8">Registro</h2>
      <form @submit.prevent="onSubmit" class="mx-auto py-10 w-1/3">
        <input
          class="block w-full py-2 px-3"
          type="text"
          name="Username"
          placeholder="Nombre de usuario"
        />
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
        <select class="block w-full py-2 px-3" id="dev-role">
          <option class="block w-full py-2 px-3" value="fullstack">
            Fullstack Developer
          </option>
          <option class="block w-full py-2 px-3" value="frontend">
            Frontend Developer
          </option>
          <option class="block w-full py-2 px-3" value="backend">
            Backend Developer
          </option>
        </select>
        <button type="submit" class="block w-full py-2 px-3">Enviar</button>
      </form>
    </section>
  </div>
</template>
