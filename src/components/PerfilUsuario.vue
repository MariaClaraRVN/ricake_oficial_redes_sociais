<script setup lang="ts">
</script>

<template>
  <div class="perfil">
    <div class="logo-perfil">
      <img src="/public/img/RICAKE (5).png" alt="Ricake Logo" class="logo" />
    </div>
    <h1 class="titulo">RICAKE</h1>
    <p class="subtitulo">Feito com amor para adoçar seu dia!</p>
  </div>
</template>

<style scoped>
.perfil {
  text-align: center;
  margin-bottom: 3rem;
}

.logo-perfil {
  margin-bottom: 2rem;
}

.logo {
  width: 200px;
  height: 200px;
  border-radius: 50%;
  box-shadow: 0 8px 24px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease;
}

.logo:hover {
  transform: scale(1.05);
}

.titulo {
  font-family: "Chewy", serif;
  color: #ff5e99;
  font-size: 3.5rem;
  margin-bottom: 1rem;
  text-shadow: 1px 1px 2px #67abed;
}

.subtitulo {
  color: #6a6a6a;
  font-size: 1.2rem;
  font-weight: 300;
  max-width: 600px;
  margin: 0 auto;
}

@media (max-width: 768px) {
  .logo {
    width: 150px;
    height: 150px;
  }

  .titulo {
    font-size: 2rem;
  }

  .subtitulo {
    font-size: 1rem;
  }
}
</style>