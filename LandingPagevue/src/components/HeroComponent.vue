<template>
  <div
    class="h-screen bg-[url('https://images.unsplash.com/photo-1604762524889-3e2fcc145683?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1yZWxhdGVkfDExfHx8ZW58MHx8fHx8&w=1000&q=80')] bg-cover"
  >
    <nav>
      <NavbarComponent />
    </nav>
    <div class="flex flex-col mt-40 items-center h-full gap-10">
      <h1 class="text-4xl font-bold">LOMBOK</h1>
      <h3 class="text-2xl">
        HOLISTIC HEALTH
      </h3>
      <div class="bg-gray-900 w-16 h-2 rounded-full"></div>
    </div>
  </div>
</template>

<script setup lang="ts">
import NavbarComponent from './NavbarComponent.vue'
</script>
