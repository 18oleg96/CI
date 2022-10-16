<template>
  <div class="footer">
    <Container>
      <div class="footerBlockText">
        <p class="footerAddress">
          Ростов-на-Дону, Соколова 53, офис 313
        </p>
        <a href="mailto:manager@cinet.ru" class="footerMail">
          manager@cinet.ru
        </a>
        <a href="tel:+78692678537" class="footerTel">
          + 7 (863) 267-85-37
        </a>
      </div>
      <div class="footerLinks">
        <a href="#" class="footerLinksNetworks">
          <img src="~/assets/images/telegram.png" alt="Telegram" >
        </a>
        <a href="#" class="footerLinksNetworks">
          <img src="~/assets/images/vk.png" alt="VK"> 
        </a>
        <a href="#" class="footerLinksNetworks">
          <img src="~/assets/images/twitter.png" alt="Twitter">
        </a>
      </div>
      <p class="companyName">
        © 1999–2020, Центр-Интернет, Ростов-на-Дону
      </p>
      <p class="creatingWebsites">
        Создание и продвижение сайтов
      </p>
      <p class="politics">
        Политика конфиденциальности
      </p>
    </Container>
  </div>
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
  @import '~/components/uikit/Footer/styles';
</style>