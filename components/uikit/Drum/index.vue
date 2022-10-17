<template>
  <span class="drum" :class="drumClass">
    <div class="containerDrum">
      <div class="wrapDrum">
        <span>
          <slot />
        </span>
        <span class="duplicateDrum">
          <slot />
        </span>
      </div>
    </div>
  </span>
</template>

<script>
export default {
  props: {
    decoration: {
      type: String,
      default: "line"
    }
  },
  computed: {
    drumClass: function() {
      return `${this.decoration ? this.decoration : 'line'}`;
    }
  },
}
</script>

<style lang="scss">
@import './styles';
</style>
