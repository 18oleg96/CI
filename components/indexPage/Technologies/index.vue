<template>
  <div class="technologies">
    <Container>
      <h4 class="technologiesHeading">
        Технологии
      </h4>
      <div class="technologiesList">
        <div class="technologiesBlock">
          <img src="~/assets/images/technologies1.png" alt="technologies" class="technologiesImg">
          <p class="technologiesText">
            Next.js
          </p>
        </div>
        <div class="technologiesBlock">
          <img src="~/assets/images/technologies2.png" alt="technologies" class="technologiesImg">
          <p class="technologiesText">
            Vue.js
          </p>
        </div>
        <div class="technologiesBlock">
          <img src="~/assets/images/technologies3.png" alt="technologies" class="technologiesImg">
          <p class="technologiesText">
            React.js
          </p>
        </div>
        <div class="technologiesBlock">
          <img src="~/assets/images/technologies4.png" alt="technologies" class="technologiesImg">
          <p class="technologiesText">
            Symfony
          </p>
        </div>
      </div>
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
  @import '~/components/indexPage/Technologies/styles';
</style>