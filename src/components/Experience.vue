<script setup></script>

<template>
  <section>
    <h3 class="title">
      КОРПОРАТИВНЫЙ ПРЕПОДАВАТЕЛЬ ESL EGO -УНИВЕРСИТЕТА ЛУКОЙЛ И РОСАТОМ
    </h3>
    <div class="wrapper">
      <div class="subwrapper">
        <h4 class="sub-title">Lukoil</h4>
        <p class="sm-text">Корпоративный преподаватель</p>
      </div>
      <img src="../assets/plus.svg" alt="" class="plus" />
    </div>
    <div class="line"></div>
    <div class="wrapper">
      <div class="subwrapper">
        <h4 class="sub-title">Rosatom</h4>
        <p class="sm-text">Корпоративный преподаватель</p>
      </div>
      <img src="../assets/plus.svg" alt="" class="plus" />
    </div>
    <div class="line"></div>
    <div class="wrapper">
      <div class="subwrapper">
        <h4 class="sub-title">Yandex Practicum</h4>
        <p class="sm-text">Преподаватель, наставник</p>
      </div>
      <img src="../assets/plus.svg" alt="" class="plus" />
    </div>
    <div class="line"></div>
    <div class="wrapper">
      <div class="subwrapper">
        <h4 class="sub-title">Самостоятельная занятость</h4>
        <p class="sm-text">Преподаватель</p>
      </div>
      <img src="../assets/plus.svg" alt="" class="plus" />
    </div>
  </section>
</template>

<style scoped>
section {
  background-color: #212121;
  border-radius: 69px;
  color: white;
  padding: 88px;
  font-family: "Inter", sans-serif;
}

.title {
  font-weight: 600;
  font-size: 48px;
  max-width: 1054px;
  margin: 0 0 60px;
}

.wrapper {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.subwrapper {
  display: flex;
  align-items: center;
}

.sub-title {
  opacity: 0.8;
  font-weight: 400;
  font-size: 40px;
  text-transform: uppercase;
  margin: 0 20px 0 0;
}

.sm-text {
  margin: 0;
  opacity: 0.5;
  font-weight: 400;
  font-size: 24px;
}

.line {
  max-width: 1200px;
  height: 1px;
  background-color: white;
  opacity: 0.5;
  margin: 32px 0;
}
</style>
