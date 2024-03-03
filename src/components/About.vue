<script setup></script>

<template>
  <section>
    <img class="wave first-wave" src="../assets/wave-up.png" alt="" />
    <div class="wrapper">
      <h3 class="title">Обо мне</h3>
      <p class="text">
        Привет! Меня зовут Абдула, и я являюсь носителем, а также современным
        преподавателем английского языка с опытом более 7 лет. В основе моей
        философии преподавания лежит убеждение, что английский язык может
        открыть студентам мир. Я считаю, что преподавание - одна из самых
        благородных и приносящих удовольствие профессий
      </p>
      <button class="button">Смотреть резюме</button>
    </div>
    <img class="wave second-wave" src="../assets/wave-down.png" alt="" />
    <img class="photo" src="../assets/about-photo.png" alt="" />
  </section>
</template>

<style scoped>
section {
  background-color: white;
  border-radius: 69px;
  margin-top: 16px;
  padding: 48px;
  position: relative;
}

.wrapper {
  display: flex;
  flex-direction: column;
  align-items: left;
}

.title {
  font-family: "Days", sans-serif;
  font-weight: 400;
  font-size: 50px;
  line-height: 60px;
  text-transform: uppercase;
  margin: 44px 0 32px;
}

.text {
  font-family: "Inter", sans-serif;
  font-weight: 400;
  font-size: 24px;
  margin: 0 0 44px;
  max-width: 800px;
}

.button {
  font-family: "Inter", sans-serif;
  font-weight: 500;
  font-size: 28px;
  color: white;
  background-color: #212121;
  border-radius: 100px;
  padding: 12px 24px;
  border: none;
  max-width: 301px;
  margin-bottom: 44px;
}

.photo {
  position: absolute;
  top: 107px;
  left: 835px;
}
</style>
