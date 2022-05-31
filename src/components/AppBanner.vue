<template>
  <div class="banner">
      <div class="text">
          <h1>Learn At Your Own Pace!</h1>
      <p>Get teamed up with people of the same will.</p>
      <button>Get started for free</button>
      </div>
      <div class="image">
          <div class="left-img">
              <img src="../assets/img/home-6-hero-left-person.png" alt="person">
          </div>
          <div class="right-img">
              <img class="poster-image" src="../assets/img/home-6-hero-poster-final.jpg" alt="meeting person">
              <img src="../assets/img/home-6-service-image-04.png" alt="person">
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name: "AppBanner"
}
</script>

<style lang="scss" scoped>
@import "../style/variable";
.banner{
    text-align: center;
    height: 600px;
    margin-bottom: 10rem;
    .text{
        margin: 6em;
    }
    .image{
        display: flex;
        justify-content: center;
        .poster-image{
            background-color: white;
            padding: 1em;
            border-radius: 10px;
            box-shadow: 0 18px 14px -14px $gray-chateau-color;
        }
    }
}
</style>