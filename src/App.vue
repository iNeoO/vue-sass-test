<template>
  <div>
    {{ color }}
  </div>
</template>

<script>
import colors from './assets/_colors.scss';

export default {
  name: 'App',
  computed: {
    color() {
      return colors.white;
    },
  },
};
</script>

<style lang="scss">
</style>
