<script setup lang="ts">
const currentYear = new Date().getFullYear()
</script>

<template>
  <footer class="footer">
    <p>&copy; {{ currentYear }} Ricake. Todos os direitos reservados.</p>
  </footer>
</template>

<style scoped>
.footer {
  text-align: center;
  padding: 2rem 0;
  color: #8a8a8a;
  font-size: 0.9rem;
}
</style>