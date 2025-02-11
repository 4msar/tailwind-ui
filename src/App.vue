<script setup lang="ts">
import { ArrowDown } from 'lucide-vue-next';
import CurvedImage from './components/CurvedImage.vue'
import StickyTitle from './components/StickyTitle.vue'
import AnimatedImage from './components/AnimatedImage.vue'
</script>

<template>
  <main class="flex flex-col gap-y-8 divide-y divide-slate-300">
    <header class="h-screen w-full flex flex-col border-b border-slate-300 justify-center items-center">
      <h1 class="container mx-auto text-dynamic p-4 font-bold mb-8 text-center text-slate-700">
        Tailwind UIs with Vite + Vue 3 + TypeScript
      </h1>
      <ArrowDown class="w-12 h-12 mt-8 text-slate-700 animate-bounce" />
    </header>

    <!-- Main Component Lists -->
    <section class="h-screen">
      <CurvedImage class="container mx-auto" />
    </section>
    <section class="h-screen">
      <AnimatedImage class="container mx-auto" />
    </section>
    <section class="h-screen">
      <StickyTitle class="container mx-auto" />
    </section>
  </main>


</template>
