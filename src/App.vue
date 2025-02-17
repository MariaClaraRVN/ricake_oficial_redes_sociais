<script setup lang="ts">
import PerfilUsuario from './components/PerfilUsuario.vue'
import SocialLinks from './components/SocialLinks.vue'
import Footer from './components/Footer.vue'
</script>

<template>
  <div class="container">
    <PerfilUsuario />
    <SocialLinks />
    <Footer />
  </div>
</template>

<style scoped>
.container {
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-between;
  padding: 2rem 1rem;
  background-color: #fdf6f6;
}

@media (max-width: 768px) {
  .container {
    padding: 1rem;
  }
}
</style>