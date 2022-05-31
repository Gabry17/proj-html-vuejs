<template>
  <div>
  <span>{{ menuObj.header }} <i class="fas fa-angle-down"></i></span>
  </div>
</template>

<script>
export default {
  name: "AppHeaderMenu",
  props: {
      menuObj: Object
  }
};
</script>

<style lang="scss" scoped>
span {
  margin-right: 0.5em;
  i {
    vertical-align: middle;
    font-size: 0.7em;
  }
}
</style>
