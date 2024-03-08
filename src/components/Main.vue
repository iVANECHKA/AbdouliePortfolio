<script setup>
import Intro from "./Intro.vue";
import MainAdv from "./MainAdv.vue";
import About from "./About.vue";
import Experience from "./Experience.vue";
import Philosophy from "./Philosophy.vue";
</script>

<template>
  <main>
    <Intro />
    <MainAdv />
    <About />
    <h2 class="title">Опыт работы</h2>
    <Experience />
    <h2 class="title">Моя философия</h2>
    <Philosophy />
  </main>
</template>

<style scoped>
.title {
  font-family: "Days", sans-serif;
  font-weight: 400;
  font-size: 60px;
  text-transform: uppercase;
  margin: 0 0 60px;
}
</style>
