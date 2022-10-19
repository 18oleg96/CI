<template>
  <div>
    <label v-if="showOnTop">
      <UIKitMiniHeading>
        <slot />
      </UIKitMiniHeading>
    </label>
    <div class="divider" />
    <label v-if="!showOnTop">
      <UIKitMiniHeading>
        <slot />
      </UIKitMiniHeading>
    </label>
  </div>
</template>

<script>
export default {
  props: {
    showOnTop: {
      type: Boolean,
      default: false,
    },
  },
}
</script>

<style lang="scss">
  @import './styles';
</style>
