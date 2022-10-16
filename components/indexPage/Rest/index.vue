<template>
  <Container>
    <div class="rest">
      <div class="restText">
        <h3 class="restTextHeading">
          Кто хорошо отдыхает, тот хорошо работает!
        </h3>
        <p class="restTextDescription"> 
          Уютный офис, гибкий график, поддержка в обучении и харизматичные коллеги
          — все это ждет вас по умолчанию. <br>
          А еще мы любим бурные корпоративы, душевные посиделки и экскурсии в интересные места.
        </p>
        <p class="restTextDescription">
          Обожаем караоке, пейнтбол и настолки, обсуждать книги и рубиться в приставку. 
          Всегда ищем новое, классное и интересное. С нами хорошо — и за работой, и вне ее. 
          Вливайся в команду!
        </p>
      </div>
      <div class="restImg">
        <img src="~/assets/images/rest.png" alt="rest" class="">
      </div>
    </div>
  </Container>
</template>

<script>
import Container from '~/components/uikit/Container';

export default {
  components: {
    Container
  },
}
</script>

<style lang="scss">
  @import '~/components/indexPage/Rest/styles';
</style>