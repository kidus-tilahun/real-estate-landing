<script setup>
import logo from "@/assets/logo.svg";
</script>

<template>
  <div
    class="mx-auto flex items-center justify-between max-w-7xl px-4 sm:px-6 lg:px-8 h-20"
  >
    <div class="">
      <RouterLink to="/" aria-label="Home">
        <img :src="logo" alt="Noah Real Estate" class="w-52 h-20" />
      </RouterLink>
    </div>

    <nav
      class="flex justify-center items-center px-4 py-6 rounded-full bg-white/10 backdrop-blur-md border border-white/20"
    >
      <ul class="flex items-center gap-6">
        <li>
          <RouterLink to="" class="nav-link">Home</RouterLink>
        </li>
        <li>
          <RouterLink to="" class="nav-link">About</RouterLink>
        </li>
        <li>
          <RouterLink to="" class="nav-link">Properties</RouterLink>
        </li>
        <li>
          <RouterLink to="" class="nav-link">News</RouterLink>
        </li>
        <li>
          <RouterLink to="" class="nav-link">Contact</RouterLink>
        </li>
      </ul>
    </nav>

    <div class="flex justify-center items-center gap-3">
      <button
        class="font-jakarta bg-amber-500 px-5 py-2 rounded-2xl hover:bg-amber-600/90 transition-colors duration-300 ease-in-out text-slate-900"
      >
        Login
      </button>
      <button
        class="font-jakarta px-5 py-2 rounded-2xl border-2 border-amber-500 text-white hover:text-black hover:bg-amber-500 transition-colors ease-in-out duration-300"
      >
        Sign in
      </button>
    </div>
  </div>
</template>
