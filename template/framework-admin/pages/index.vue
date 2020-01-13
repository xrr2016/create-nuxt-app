<template>
  <section class="index">
    <p>index</p>
    <nuxt-child></nuxt-child>
  </section>
</template>

<script>
export default {
  name: 'Index',
}
</script>

<style lang="less">
.index {
  position: relative;
  max-width: (@--min-width - 48px);
}
</style>
