<script setup>
import FilterSearchCard from '../components/FilterSearchCard.vue';

</script>

<template>
  <section class="relative min-h-screen w-full">
    <img
      src="https://images.unsplash.com/photo-1748228885250-49564b614db9?q=80&w=1740&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
      alt="Real Estate"
      class="absolute inset-0 h-[90%] w-full object-center"
    />

    <!-- overlay -->
    <div class="absolute inset-0 h-[90%] bg-black/30"></div>

    <div class="relative z-10 min-h-screen">
      <div
        class="max-w-7xl mx-auto min-h-screen flex flex-col gap-4 items-center justify-center -translate-y-16"
      >
        <h1 class="text-8xl font-outfit font-bold text-center text-slate-200">
          More Than a Home, Build Your Future
        </h1>
        <p class="text-3xl font-inter font-light max-w-2xl text-center text-slate-200">
          Discover your next sanctuary in the world’s most coveted
          neighborhoods.
        </p>
      </div>
    </div>
  </section>

  <FilterSearchCard />
</template>
