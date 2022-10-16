<template>
  <div class="hero">
    <span class="heroNumber">
      #1
    </span>
    <div>
      <h1 class="heroHeading">
        Мы делаем сайты хорошо
      </h1>
      <p class="heroText">
        разрабатываем функциональные сайты и сервисы, делаем продвижение 
        и интернет рекламу, раскручиваем проекты в социальных сетях
      </p>
      <p class="heroProblems">
        Решаем проблем клиентов и справляемся с задачами бизнеса
      </p>
      <div>
        <Button>
          Заполнить бриф
        </Button> 
      </div> 
    </div>
  </div>
</template>

<script>
import Button from '~/components/uikit/Button';

export default {
  components: {
      Button,
  },
}
</script>

<style lang="scss">
  @import '~/components/indexPage/Hero/styles';
</style>