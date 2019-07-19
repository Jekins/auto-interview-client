<script>
  // import HelloWorld from '@/components/HelloWorld.vue'

  export default {
    name: 'view-sign-up',

    components: {
    }
  }
</script>

<template>
  <div class="view-sign-up">
    <main class="view-sign-up__content">
      <h1 class="view-sign-up__title">
        Автоматическое тестирование
      </h1>

      <div class="view-sign-up__lead">
        <p>
          Это автоматическое тестирование по знаниям JavaScript, HTML и CSS.
          <br>
          На решения <b>всех заданий</b> выделено <b>20 минут</b>.
          Вы сами выбираете сколько времени потратить на решение той или иной задачи.
          Как только время иссякнет, ваш ответ будет автоматически отправлен и тестированые закончится.
        </p>
        <p>
          <b>Желаем удачи!</b>
        </p>
      </div>
    </main>
  </div>
</template>

<style lang="scss">
  @import '../styles/views/view-sign-up';
</style>
