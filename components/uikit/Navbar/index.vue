<template>
  <div class="navbar" :class="`${color ? color : 'primary'}`">
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
        <a href="/contacts">
          <li class="navListPoint">
            <Drum>
              Контакты
            </Drum>
          </li>
        </a>
      </ul>
      <div @click="openedSidebar = true; openBurger()" class="navBurger">
        <Drum>
          <img 
            src="~/assets/images/burger.png" 
            alt="burger" 
            class="navBurger"
          >
        </Drum>
      </div>
    </div>

    <div class="sidebar" :class="{opened: this.openedSidebar}">
      <div class="sidebarBlock">
        <div class="navLogo">
          <Logo />
        </div>
        <div @click="openedSidebar = false; closeBurger()" class="navBurger">
          <Drum>
            <img 
              src="~/assets/images/burger.png" 
              alt="burger" 
              class="navBurger"
            >
          </Drum>
        </div>
      </div>
      <div class="sidebarBlockList">
        <ul class="navList">
          <li class="navListPoint">
            <Drum>
              О Компании
            </Drum>
          </li>
          <li class="navListPoint">
            <Drum>
              Цены
            </Drum>
          </li>
          <a href="/job">
            <li class="navListPoint">
              <Drum>
                Вакансии
              </Drum>
            </li>
          </a>
        </ul>
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
  props: {
    color: String
  },
  data() {
    return {
      openedSidebar: false
    }
  },
  methods: {
    openBurger: () => {
      document.querySelector("body").classList.add("disableScroll");
    },
    closeBurger: () => {
      document.querySelector("body").classList.remove("disableScroll");
    },
  },
}
</script>

<style lang="scss">
  @import '~/components/uikit/Navbar/style';
</style>
