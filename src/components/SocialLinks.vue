<script setup lang="ts">
const socialLinks = [
  { name: 'Whatsapp', url: 'https://w.app/5kzcmq', icon: '/img/whatsapp.png' },
  { name: 'Cardápio', url: '/docs/Cardapio_Ricake.pdf', icon: '/img/cardapio.png' },
  { name: 'Instagram', url: 'https://www.instagram.com/ricake.oficial/', icon: '/img/instagram.png' },
  { name: 'Facebook', url: 'https://www.facebook.com/profile.php?id=61573172783708', icon: '/img/facebook.png' },
  { name: 'Tiktok', url: 'https://www.tiktok.com/@ricake.oficial', icon: '/img/tiktok.png' },
]
</script>

<template>
  <div class="social-links">
    <a v-for="link in socialLinks" :key="link.name" :href="link.url" class="social-link" target="_blank"
      rel="noopener noreferrer">
      <img :src="link.icon" :alt="link.name" class="icon" />
      {{ link.name }}
    </a>
  </div>
</template>

<style scoped>
.social-links {
  display: flex;
  flex-direction: column;
  gap: 1rem;
  margin: 2rem 0;
}

.social-link {
  display: flex;
  align-items: center;
  gap: 0.5rem;
  padding: 0.8rem 2rem;
  background-color: #fff;
  border-radius: 25px;
  color: #4a4a4a;
  text-decoration: none;
  font-weight: 500;
  transition: all 0.3s ease;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
}

.social-link:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
  background-color: #f8e6e6;
}

.icon {
  width: 30px;
  height: 30px;
}
</style>
