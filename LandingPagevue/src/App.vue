<script setup lang="ts">
import AboutComponent from './components/AboutComponent.vue'
import ArticleComponent from './components/ArticleComponent.vue'
import FooterComponent from './components/FooterComponent.vue'
import HeroComponent from './components/HeroComponent.vue'
import SubscribeComponent from './components/SubscribeComponent.vue'
const toTopButton = document.getElementById("to-top-button");
</script>

<template>
  <header>
    <HeroComponent />
  </header>
  <main>
    <section id="article"><ArticleComponent /></section>
    <section id="about"><AboutComponent /></section>
    <section id="subscribe"><SubscribeComponent /></section>
  </main>
  <footer>
    <FooterComponent />
  </footer>
</template>
