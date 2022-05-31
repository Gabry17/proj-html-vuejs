<template>
  <div class='info'>
      <div>{{ exploreObj.explore }}</div>
  </div>
</template>

<script>
export default {
  name: "AppFooterExplore",
  props:{
      exploreObj: Object
  }
};
</script>

<style lang="scss" scoped>
@import '../style/variable';

.info {
  width: calc(100% / 2);
  color: $gray-chateau-color;
}
</style>
