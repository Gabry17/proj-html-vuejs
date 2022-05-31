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

.info {
  width: calc(100% / 2);
}
</style>
