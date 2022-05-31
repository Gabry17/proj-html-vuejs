<template>
  <div>
      <div class="contact">{{ addressObj.contact }}</div>
  </div>
</template>

<script>
export default {
    name: 'AppFooterAddress',
    props: {
        addressObj: Object
    }
}
</script>

<style lang="scss" scoped>
@import '../style/variable';
.contact{
    margin: 0.5em 0;
    color: $gray-chateau-color;
}
</style>