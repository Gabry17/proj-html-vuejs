<template>
  <header>
    <div class="container">
      <div class="logo">
        <img src="../assets/img/dark-logo.png" alt="" />
      </div>
      <div class="list-menu">
        <AppHeaderMenu
          v-for="(item, index) in menu"
          :key="index"
          :menuObj="item"
        />
        <i class="fas fa-shopping-cart"></i>
        <i class="fas fa-user-circle"></i>
        <div class="input">
          <input id="search" type="text" placeholder="Search..." />
          <label for="search" id="search"><i class="fas fa-search"></i></label>
        </div>
      </div>
    </div>
    <!-- banner -->
    <AppBanner />
    <!-- /banner -->
  </header>
</template>

<script>
import AppBanner from "./AppBanner";
import AppHeaderMenu from "./AppHeaderMenu";

export default {
  name: "AppHeader",
  components: {
    AppBanner,
    AppHeaderMenu,
  },
  props: {
    headerObj: Object,
  },
  data() {
    return {
      menu: [
        {
          header: "Home",
        },
        {
          header: "Pages",
        },
        {
          header: "Courses",
        },
        {
          header: "Features",
        },
        {
          header: "Blog",
        },
        {
          header: "Shop",
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
@import "../style/variable";
header {
  background-color: $port-gore-color;
  color: $white-color;
  padding: 1em 0;
  .container {
    max-width: 1200px;
    display: flex;
    justify-content: space-between;
    line-height: 30px;
    width: $project-width;
    margin: $project-margin;
    .logo{
      width: 20%;
      height: 30px;
      img{
        width: 100%;
      }
    }
    .list-menu {
      display: flex;
      width: 70%;
      & > i {
        line-height: 30px;
        margin-right: 0.5em;
      }
      .input {
        background-color: $white-color;
        border-radius: 5px;
        padding: 0 .5em;
        input {
          border: none;
        }
        label {
          color: $mountain-meadow-color;
        }
      }
    }
  }
}
</style>
