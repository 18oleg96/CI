<template>
  <Container>
    <div class="directions">
      <div class="directionsBlockOne">
        <p class="directionsBlockOneHeading">
          Направления
        </p>
      </div>
      <div class="directionsBlockTwo">
        <a href="https://cinet.ru/uslugi/sozdanie-sajtov" target="_blank" class="directionsLink">
          <span class="directionsLinkNumber">
            01
          </span>
          <p class="directionsLinkText">
            Создание и продвижение сайтов
          </p>
        </a>
        <a href="https://cinet.ru/czenyi/dizajn" target="_blank" class="directionsLink">
          <span class="directionsLinkNumber">
            02
          </span>
          <p class="directionsLinkText">
            Графический дизайн
          </p>
        </a>
        <a href="https://cinet.ru/uslugi/razrabotka-mobilnyix-prilozhenij" target="_blank" class="directionsLink">
          <span class="directionsLinkNumber">
            03
          </span>
          <p class="directionsLinkText">
            Разработка мобильный приложений
          </p>
        </a>
        <a href="https://cinet.ru/uslugi/call-czentryi" target="_blank" class="directionsLink">
          <span class="directionsLinkNumber">
            04
          </span>
          <p class="directionsLinkText">
            CALL-Центры
          </p>
        </a>
        <a href="https://cinet.ru/uslugi/kontekstnaya-reklama" target="_blank" class="directionsLink">
          <span class="directionsLinkNumber">
            05
          </span>
          <p class="directionsLinkText">
            Контекстная реклама
          </p>
        </a>
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
  @import '~/components/indexPage/Directions/styles';
</style>