<script setup></script>

<template>
  <section>
    <div class="card first-card">
      <p class="text first-text">Уровень английского</p>
      <div class="line first-line"></div>
      <h3 class="title first-title">Носитель</h3>
    </div>
    <div class="card second-card">
      <p class="text second-text">Опыт работы</p>
      <div class="line"></div>
      <h3 class="title second-title">7 лет</h3>
    </div>
    <div class="card third-card">
      <p class="text third-text">Основной метод обучения</p>
      <div class="line"></div>
      <h3 class="title third-title">Общение</h3>
    </div>
  </section>
</template>

<style scoped>
section {
  margin: 16px auto 0;
  display: flex;
  gap: 16px;
  justify-content: center;
}

.card {
  width: 448px;
  border-radius: 62px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.first-card {
  background-image: url(../assets/card1bg.png);
  background-color: #212121;
  padding: 71px 0;
}

.second-card {
  background-image: url(../assets/card2bg.png);
  background-color: #a1d56e;
  padding: 71px 0;
}

.third-card {
  background-image: url(../assets/card3bg.png);
  background-color: #dbded7;
  padding: 52px 0;
}

.text {
  margin: 0;
  font-family: "Inter", sans-serif;
  color: #141414;
  font-weight: 400;
  font-size: 32px;
  max-width: 389px;
  text-align: center;
}

.first-text {
  color: white;
  opacity: 0.68;
  margin: 0 0 22px;
}

.second-text {
  margin: 0 0 22px;
}

.third-text {
  margin: 0 0 22px;
}

.line {
  background-color: #212121;
  width: 79px;
  height: 2px;
  border-radius: 2px;
}

.first-line {
  background-color: white;
}

.title {
  margin: 22px 0 0;
  color: #141414;
  font-family: "Days", sans-serif;
  font-weight: 400;
  font-size: 40px;
}

.first-title {
  color: white;
}
</style>
