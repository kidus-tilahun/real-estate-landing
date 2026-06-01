<script setup>
import Navbar from "./components/Navbar.vue";
import Footer from "./components/Footer.vue";
</script>

<template>
  <div class="min-h-screen flex flex-col">
    <header class="absolute top-0 left-0 w-full z-50">
      <Navbar />
    </header>

    <main class="flex-1">
      <RouterView />
    </main>

    <footer>
      <Footer />
    </footer>
  </div>
</template>
