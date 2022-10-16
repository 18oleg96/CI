<template>
  <div class="partners">
    <carousel :itemsToShow="6" :itemsToScroll="1" :wrapAround="true" autoplay="0.1" transition="3500" class="carousel">
      <slide v-for="slide in slides" :key="slide.id">
        <div>
          <img :src="`/images/${slide.src}`">
        </div>
      </slide>
      <!-- <template #addons>
        <navigation />
        <pagination />
      </template> -->
    </carousel>
  </div>
</template>

<script>
import 'vue3-carousel/dist/carousel.css'
import { Carousel, Slide, Pagination, Navigation } from 'vue3-carousel'

  export default {
    components: {
      Carousel,
      Slide,
      Pagination,
      Navigation,
    },
    data() {
      return {
        slides: [
          { id: 1, src: "../assets/images/partners1.png" },
          { id: 2, src: "../assets/images/partners2.png" },
          { id: 3, src: "../assets/images/partners3.png" },
          { id: 4, src: "../assets/images/partners4.png" },
          { id: 5, src: "../assets/images/partners5.png" },
          { id: 6, src: "../assets/images/partners6.png" },
          { id: 7, src: "../assets/images/partners7.png" },
        ]
        
      }
  }
  };
</script>

<style lang="scss">
  @import '~/components/indexPage/Partners/styles';
</style>