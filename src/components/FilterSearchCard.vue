<script setup>
import { ChevronDown } from "lucide-vue-next";
import { Building } from "lucide-vue-next";
import { MapPin } from "lucide-vue-next";
import { Loader } from "lucide-vue-next";
import { House } from "lucide-vue-next";
</script>

<template>
  <article
    class="absolute bottom-[10%] translate-y-1/2 left-1/2 -translate-x-1/2 flex items-center gap-12 bg-white/20 backdrop-blur-md border border-white/30 px-6 py-3 rounded-full z-30"
  >
    <button
      class="flex items-center gap-3 w-full whitespace-nowrap rounded-full border border-amber-600 px-4 py-3"
    >
      <Building class="shrink-0" />
      <span class="font-jakarta text-base">Resident Types</span>
      <ChevronDown class="shrink-0" />
    </button>
    <button
      class="flex items-center gap-3 w-full whitespace-nowrap rounded-full border border-amber-600 px-4 py-3"
    >
      <MapPin class="shrink-0" />
      <span class="font-jakarta text-base">Locations</span>
      <ChevronDown class="shrink-0" />
    </button>
    <button
      class="flex items-center gap-3 w-full whitespace-nowrap rounded-full border border-amber-600 px-4 py-3"
    >
      <Loader class="shrink-0" />
      <span class="font-jakarta text-base">Status</span>
      <ChevronDown class="shrink-0" />
    </button>
    <button
      class="flex items-center gap-3 w-full whitespace-nowrap rounded-full border border-amber-600 px-4 py-3"
    >
      <House class="shrink-0" />
      <span class="font-jakarta text-base">Unit Types</span>
      <ChevronDown class="shrink-0" />
    </button>

    <button
      class="font-jakarta text-slate-900 text-lg w-full whitespace-nowrap rounded-full bg-amber-600 px-6 py-3"
    >
      Find Property
    </button>
  </article>
</template>
