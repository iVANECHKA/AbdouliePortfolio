<script setup>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
</script>

<template>
  <Header />
  <Main />
</template>

<style>
@font-face {
  font-family: "Rostov";
  src: local("Rostov"), url(./fonts/Rostov.woff2) format("woff2");
}

@font-face {
  font-family: "Days";
  src: local("Days"), url(./fonts/Days.woff2) format("woff2");
}
</style>
