<script>
export default {
  data() {
    return {
      show1: false,
      show2: false,
      show3: false,
      show4: false,
    };
  },
};
</script>

<template>
  <section>
    <h3 class="title">
      КОРПОРАТИВНЫЙ ПРЕПОДАВАТЕЛЬ ESL EGO-УНИВЕРСИТЕТА ЛУКОЙЛ И РОСАТОМ
    </h3>
    <div id="wrapper" class="wrapper">
      <div class="subwrapper">
        <h4 class="sub-title">Lukoil</h4>
        <p class="sm-text">Корпоративный преподаватель</p>
      </div>
      <img
        src="../assets/plus.svg"
        alt="Plus"
        class="plus"
        @click="show1 = !show1"
        :class="{ animatedPlus: show1 }"
      />
    </div>
    <div class="text-wrapper">
      <p class="text" :class="{ animated: show1 }">
        Текущие обязанности и достижения: Отвечал за преодоление языкового
        барьера у студентов и оказание им помощи в совершенствовании
        коммуникативных навыков. Разрабатывал соответствующие учебные планы и
        программы, отвечающие требованиям компании и учитывающие уровень
        подготовки студентов. Разрабатывал творческие и интерактивные планы
        уроков и материалы курсов, включающие настольные игры и мозговые штурмы,
        которые носят как образовательный, так и развлекательный характер.
        Выявлял и предлагал дополнительные ресурсы для учащихся в зависимости от
        их уровня и интересов. - Оформлял отчеты и досье об успеваемости
        учащихся. Проводил уроки, включающие в себя методы развития навыков с
        акцентом на ораторское мастерство. Планировал групповую работу для
        развития навыков командообразования как на интенсивных, так и на обычных
        курсах. В течение 12 месяцев провел 20 интенсивных занятий по
        корпоративному английскому языку в Центре корпоративного обучения
        Лукойла. Обучено 200 слушателей как онлайн, так и в Центре
        корпоративного обучения "Лукойл".
      </p>
    </div>
    <div class="line"></div>
    <div class="wrapper">
      <div class="subwrapper">
        <h4 class="sub-title">Rosatom</h4>
        <p class="sm-text">Корпоративный преподаватель</p>
      </div>
      <img
        src="../assets/plus.svg"
        alt=""
        class="plus"
        @click="show2 = !show2"
        :class="{ animatedPlus: show2 }"
      />
    </div>
    <div class="text-wrapper">
      <p class="text" :class="{ animated: show2 }">
        РОСАТОМ 2018 - текущая Ведение списков посещаемости и предоставление
        периодических отчетов об успеваемости студентов. Оценивал студентов и
        оформлял отчеты по окончании каждого курса. Модерировал более 5
        разговорных клубов в различных филиалах Госкорпорации "Росатом" как
        онлайн, так и офлайн. Тренировал 6 индивидуальных и более 10 групповых
        курсов. Обеспечивал оптимальное обучение и поддержку студентов.
      </p>
    </div>
    <div class="line"></div>
    <div class="wrapper">
      <div class="subwrapper">
        <h4 class="sub-title">Yandex Practicum</h4>
        <p class="sm-text">Преподаватель, наставник</p>
      </div>
      <img
        src="../assets/plus.svg"
        alt=""
        class="plus"
        @click="show3 = !show3"
        :class="{ animatedPlus: show3 }"
      />
    </div>
    <div class="text-wrapper">
      <p class="text" :class="{ animated: show3 }">
        Работал со студентами разных уровней над развитием навыков разговорной
        речи. Помогала студентам преодолевать языковой барьер и развивать
        уверенность в себе. Проводил тщательную оценку студентов и давал
        конструктивные отзывы в конце каждого занятия. Провел более 5000 занятий
        по ораторскому искусству
      </p>
    </div>
    <div class="line"></div>
    <div class="wrapper">
      <div class="subwrapper">
        <h4 class="sub-title">Самостоятельная занятость</h4>
        <p class="sm-text">Преподаватель</p>
      </div>
      <img
        src="../assets/plus.svg"
        alt=""
        class="plus"
        @click="show4 = !show4"
        :class="{ animatedPlus: show4 }"
      />
    </div>
    <div class="text-wrapper">
      <p class="text" :class="{ animated: show4 }">
        Работал со студентами разных уровней над развитием навыков разговорной
        речи. Помогала студентам преодолевать языковой барьер и развивать
        уверенность в себе. Проводил тщательную оценку студентов и давал
        конструктивные отзывы в конце каждого занятия. Провел более 5000 занятий
        по ораторскому искусству
      </p>
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

.text-wrapper {
  overflow: hidden;
}

.text {
  margin-top: -150px;
  transition: 1s ease;
}

.animated {
  margin-top: 10px;
  transition: 1s ease;
}

.animatedPlus {
  rotate: 45deg;
  transition: 0.6s ease;
}

.animatedPlusBack {
  rotate: -45deg;
  transition: 0.6s ease;
}

.plus {
  transition: 0.6s ease;
}
</style>
