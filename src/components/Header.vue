<script setup></script>

<template>
  <header>
    <h2 class="logo">Abdoulie</h2>
    <nav class="nav">
      <p class="nav-item">Обо мне</p>
      <p class="nav-item">Моя философия</p>
      <p class="nav-item">Методы преподавания</p>
      <p class="nav-item">Навыки</p>
      <p class="nav-item">Вопрос - Ответ</p>
    </nav>
    <button class="button">Связаться</button>
  </header>
</template>

<style scoped>
header {
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: white;
  color: #2f2f2f;
  border-radius: 30px;
  margin: 55px 0 20px;
  padding: 16px;
}

.button {
  background-color: #a1d56e;
  border-radius: 18px;
  padding: 10px 18px;
  color: white;
  border: none;
  font-family: "Inter", sans-serif;
  font-size: 24px;
  font-weight: 700;
}

.nav {
  display: flex;
  font-family: "Inter", sans-serif;
  font-weight: 400;
  font-size: 24px;
}

.nav-item {
  margin: 0 29px 0 0;
}

.logo {
  font-family: "Rostov", sans-serif;
  font-weight: 400;
  line-height: 40px;
  font-size: 40px;
  color: #a1d56e;
  margin: -4px 29px 0 0;
}
</style>
