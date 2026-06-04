<script setup>
import { Bed } from "lucide-vue-next";
import { Bath } from "lucide-vue-next";
import { Ruler } from "lucide-vue-next";
</script>

<template>
  <article
    class="flex flex-col gap-5 rounded-2xl pb-6 group transition-all duration-300"
  >
    <div
      class="w-full aspect-video overflow-hidden rounded-2xl shadow-md bg-slate-100"
    >
      <img
        class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500 ease-out"
        src="https://images.unsplash.com/photo-1507089947368-19c1da9775ae?q=80&w=1752&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
        alt="Property 1"
        loading="lazy"
      />
    </div>

    <div class="flex flex-col gap-4 px-3">
      <h3
        class="font-inter text-xl md:text-2xl font-semibold text-slate-800 tracking-tight leading-snug"
      >
        DuneHaven Residences
      </h3>

      <div
        class="flex flex-wrap items-center gap-x-3 gap-y-1.5 text-slate-600 text-sm font-medium"
      >
        <div class="flex items-center gap-1.5">
          <Bed class="size-4 text-slate-400 shrink-0" /><span
            class="text-xs md:text-sm"
            >6 Beds</span
          >
        </div>

        <div
          class="h-4 w-px bg-slate-300 hidden sm:block"
          arial-hidden="true"
        ></div>

        <div class="flex items-center gap-1.5">
          <Bath class="size-4 text-slate-400 shrink-0" /><span
            class="text-xs md:text-sm"
            >2 Baths</span
          >
        </div>

        <div
          class="h-4 w-px bg-slate-300 hidden sm:block"
          arial-hidden="true"
        ></div>

        <div class="flex items-center gap-1.5">
          <Ruler class="size-4 text-slate-400 shrink-0" /><span
            class="text-xs md:text-sm"
            >75 m²</span
          >
        </div>
      </div>

      <div class="mt-2 flex items-baseline gap-2">
        <strong class="text-2xl font-extrabold text-slate-900 tracking-tight">
          $1,250,000
        </strong>
        <span
          class="text-xs font-semibold text-slate-400 uppercase tracking-wider"
          >USD</span
        >
      </div>
    </div>
  </article>
</template>
