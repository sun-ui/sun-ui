<template>
  <button :class="$style.button">
    <slot></slot>
  </button>
</template>
<script>
export default {
  name: 'sun-button'
}
</script>

<style lang="scss" module>
  .button {
    border: none;
    padding: 5px 15px;
    background: #41B883;
    color: #fff;
  }
</style>
