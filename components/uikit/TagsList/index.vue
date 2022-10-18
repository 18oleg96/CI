<template>
  <div class="tagsList">
    <span v-for="item in list" :key="item" class="listItem">{{item}}</span>
  </div>
</template>

<script>
export default {
  props: {
    list: {
      type: Array,
      default: []
    }
  },
}
</script>

<style lang="scss">
  @import './styles';
</style>
