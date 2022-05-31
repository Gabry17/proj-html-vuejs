<template>
  <div>
      <div>{{ informationObj.information }}</div>
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

</style>