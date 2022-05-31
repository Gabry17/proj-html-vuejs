<template>
  <div>
      <div class="information">{{ informationObj.information }}</div>
  </div>
</template>

<script>
export default {
    name: 'AppFooterInformation',
    props: {
        informationObj: Object
    }
}
</script>

<style lang="scss" scoped>
@import '../style/variable';

.information{
    color: $gray-chateau-color;
}
</style>