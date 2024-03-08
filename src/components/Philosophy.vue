<script setup></script>

<template>
  <section>
    <div class="wrapper left-wrapper">
      <div class="block block1">
        <img class="block1-img" src="../assets/speak-icon.svg" alt="" />
        <h4 class="title title1 special">Стили обучения</h4>
        <p class="text text1 special">
          Я использую различные стратегии обучения для удовлетворения
          разнообразных потребностей моих студентов
        </p>
      </div>
      <div class="block block2">
        <img src="../assets/star.svg" alt="" class="star star1" />
        <img src="../assets/star.svg" alt="" class="star star2" />
        <img src="../assets/star.svg" alt="" class="star star3" />
        <img src="../assets/star.svg" alt="" class="star star4" />
        <img src="../assets/star.svg" alt="" class="star star5" />
        <div class="block2-wrapper">
          <h4 class="title title2">Дружелюбная атмосфера</h4>
          <p class="text text2">
            Я стремлюсь создать культуру уважения, в которой все студенты
            чувствуют свою значимость и поддержку
          </p>
        </div>
      </div>
    </div>
    <div class="wrapper right-wrapper">
      <div class="block block3">
        <img class="spiral" src="../assets/spiral.png" alt="" />
        <h4 class="title title3">Ресурсы</h4>
        <div class="mini-block">
          <img src="../assets/lamp.svg" alt="" />
          <p class="text block3-text">
            <b>Книги</b>, с тщательно подобранными уровнями, которые
            соответствуют их целям
          </p>
        </div>
        <div class="mini-block">
          <img src="../assets/lamp.svg" alt="" />
          <p class="text block3-text">
            <b>Диалоги</b> с использованием ролей и без
          </p>
        </div>
        <div class="mini-block">
          <img src="../assets/lamp.svg" alt="" />
          <p class="text block3-text">
            <b>Различные игры</b> (шарады, псевдонимы, quicktionary, табу и тд.)
          </p>
        </div>
      </div>
      <div class="block block4">
        <h4 class="title title4">Цель</h4>
        <p class="text block4-text">
          В целом моя философия преподавания направлена на то, чтобы помочь
          студентам развить знания и навыки, необходимые для успешного общения и
          обучения на протяжении всей жизни
        </p>
      </div>
    </div>
  </section>
</template>

<style scoped>
section {
  display: flex;
  margin-top: 60px;
  gap: 16px;
}

.title {
  font-family: "Inter", sans-serif;
  font-weight: 600;
  font-size: 40px;
  color: #141414;
}

h4 {
  margin: 0;
}

.text {
  font-family: "Inter", sans-serif;
  font-weight: 400;
  font-size: 24px;
  color: #141414;
}

.wrapper {
  width: 680px;
}

.block {
  border-radius: 63px;
}

.block1 {
  background-color: #212121;
  margin-bottom: 16px;
  height: 368px;
}

.block1-img {
  margin: 48px 0 0 48px;
}

.title1 {
  margin: 32px 0 28px 48px;
}

.text1 {
  margin: 0 0 0 48px;
}

.special {
  color: white;
}

.block2 {
  background-color: white;
  height: 516px;
  position: relative;
}

.block2-wrapper {
  padding: 276px 0 0 48px;
}

.text2 {
  max-width: 471px;
  margin: 28px 0 0;
}

.star {
  position: absolute;
}

.star1 {
  top: 43px;
  left: 48px;
  animation: star-animation1 1s infinite alternate-reverse ease-in-out;
}

.star2 {
  top: 190px;
  left: 220px;
  width: 21px;
  height: 21px;
}

.star3 {
  width: 21px;
  height: 21px;
  top: 43px;
  left: 308px;
}

.star4 {
  width: 55px;
  height: 55px;
  top: 125px;
  left: 352px;
  animation: star-animation3 1s infinite alternate ease-in-out;
}

.star5 {
  width: 82px;
  height: 82px;
  top: 43px;
  left: 524px;
  animation: star-animation2 1s infinite alternate-reverse ease-in-out;
}

.block3 {
  background-color: #dbded7;
  overflow: hidden;
  height: 545px;
  margin-bottom: 16px;
}

.spiral {
  padding-left: 185px;
}

.title3 {
  padding: 71px 0 28px 48px;
}

.mini-block {
  display: flex;
  max-width: 519px;
  gap: 17.58px;
  padding-left: 48px;
  padding-bottom: 16px;
  align-items: start;
}

.block3-text {
  margin: 0;
}

.block4 {
  background-color: #a1d56e;
  height: 339px;
}

.title4 {
  padding: 70px 0 28px 48px;
}

.block4-text {
  max-width: 544px;
  padding-left: 48px;
  margin: 0;
}

@keyframes star-animation1 {
  from {
    width: 122px;
    height: 122px;
  }
  to {
    width: 137px;
    height: 137px;
  }
}

@keyframes star-animation2 {
  from {
    width: 82px;
    height: 82px;
  }
  to {
    width: 90px;
    height: 90px;
  }
}

@keyframes star-animation3 {
  from {
    width: 55px;
    height: 55px;
  }
  to {
    width: 68px;
    height: 68px;
  }
}
</style>
