<template>
  <div class="navbar">
    <div class="navLogo">
      <Logo />
    </div>
    <div class="navRight">
      <ul class="navList">
        <li class="navListPoint">
          <Drum>
            Услуги
          </Drum>
        </li>
        <li class="navListPoint">
          <Drum>
            Кейсы
          </Drum>
        </li>
        <li class="navListPoint">
          <Drum>
            Контакты
          </Drum>
        </li>
      </ul>
      <div class="navBurger">
        <img src="~/assets/images/burger.png" alt="burger" class="navBurger">
      </div>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/uikit/Logo';
import Drum from '~/components/uikit/Drum';

export default {
  components: {
      Logo,
      Drum
  },
}
</script>

<style lang="scss">
  @import '~/components/uikit/Navbar/style';
</style>
