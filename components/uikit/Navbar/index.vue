<template>
  <div class="navbar">
    <div class="navLogo">
      <Logo />
    </div>
    <div class="navRight">
      <ul class="navList">
        <li class="navListPoint">
          Услуги
        </li>
        <li class="navListPoint">
          Кейсы
        </li>
        <li class="navListPoint">
          Контакты
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

export default {
  components: {
      Logo,
  },
}
</script>

<style lang="scss">
  @import '~/components/uikit/Navbar/style';
</style>
