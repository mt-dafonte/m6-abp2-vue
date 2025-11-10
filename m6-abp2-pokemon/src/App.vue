<script>
import Personajes from './components/Personajes.vue'

export default {
  name: 'App',
  components: { Personajes }
}
</script>

<template>
  <div class="container py-5">
    <h1 class="text-center text-primary mb-4 fw-bold">
      Tabla de Personajes Pokémon
    </h1>
    <Personajes />

  </div>
</template>