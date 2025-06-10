<script setup>
  import Portfolio from './views/Portfolio.vue';
  import Navbar from './components/Navbar.vue';
  import Footer from './components/Footer.vue';
</script>

<template>
  <div class="min-h-screen flex flex-col">
    <Navbar />
    <main class="flex-1 pt-20">
      <Portfolio />
    </main>
    <Footer />
  </div>
</template>

<style scoped>
  html {
    scroll-behavior: smooth;
  }
</style>
