<template>
  <Container>
    <div class="numbers">
      <div class="numbersBlockOne">
        <h2 class="numbersBlockOneNomber">
          <div class="qwerty">
            <VueJsCounter start="0" end="460" duration="5000" thousand="" decimal=""></VueJsCounter>
          </div>
          <span>+</span>
        </h2>
        <p class="numbersBlockOneText">
          проектов реализовано
        </p>
      </div>
      <div class="numbersBlockTwo">
        <div class="numbersBlockTwoUp">
          <div class="blockTwo">
            <span class="blockTwoNumber">
              <VueJsCounter start="0" end="23" duration="5000" thousand="" decimal=""></VueJsCounter>
            </span>
            <p class="blockTwoText">
              года на рынке
            </p>
          </div>
          <div class="blockTwo">
            <span class="blockTwoNumber">
              <VueJsCounter start="0" end="1250" duration="5000" thousand="" decimal=""></VueJsCounter>
            </span>
            <p class="blockTwoText">
              консультаций
            </p>
          </div>
        </div>
        <div class="numbersBlockTwoBottom">
          <div class="blockTwo">
            <span class="blockTwoNumber">
              <VueJsCounter start="0" end="250" duration="5000" thousand="" decimal=""></VueJsCounter>
            </span>
            <p class="blockTwoText">
              сайтов
            </p>
          </div>
          <div class="blockTwo">
            <span class="blockTwoNumber">
              <VueJsCounter start="0" end="20" duration="5000" thousand="" decimal=""></VueJsCounter>
            </span>
            <p class="blockTwoText">
              социальных проектов
            </p>
          </div>
        </div>
      </div>
    </div>
  </Container>
</template>

<script>
import Container from '~/components/uikit/Container';
import VueJsCounter from 'vue-js-counter'

  export default {
    components: {
      Container,
      VueJsCounter 
    }
  };
</script>

<style lang="scss">
  @import '~/components/indexPage/Numbers/styles';
</style>