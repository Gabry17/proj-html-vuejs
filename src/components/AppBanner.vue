<template>
  <div class="banner">
    <div class="text">
      <h1>Learn At Your Own Pace!</h1>
      <p>Get teamed up with people of the same will.</p>
      <button>Get started for free</button>
    </div>
    <!-- <div class="image">
      <div class="left-image">
        <img src="../assets/img/home-6-hero-left-person.png" alt="person" />
      </div>
      <img
        class="poster-image"
        src="../assets/img/home-6-hero-poster-final.jpg"
        alt="meeting person"
      />
      <img
        class="img-play"
        src="../assets/img/icon-youtube-play.png"
        alt="play"
      />
      <div class="right-image">
        <img src="../assets/img/home-6-service-image-04.png" alt="person" />
      </div>
    </div> -->
  </div>
</template>

<script>
export default {
  name: "AppBanner",
};
</script>

<style lang="scss" scoped>
@import "../style/variable";
.banner {
  text-align: center;
  height: 450px;
  margin-bottom: 10rem;
  position: relative;
  .text {
    margin: 6em;
    p {
      color: $silver-color;
      margin: 1em 0;
    }
  }
//   .image {
//     display: flex;
//     justify-content: center;
//     position: relative;
//     .left-image{
//         position: absolute;
//         left: 5%;
//     }
//     .poster-image {
//       background-color: $white-color;
//       padding: 1em;
//       border-radius: 10px;
//       box-shadow: 0 18px 14px -14px $gray-chateau-color;
//       position: absolute;
//       top: 150%;
//       left: 50%;
//       transform: translate(-50%, -50%);
//     }
//     .right-image{
//         position: absolute;
//         right: 5%;
//     }
//     .img-play {
//       position: absolute;
//       left: 50%;
//       top: 50%;
//       transform: translate(-50%, -50%);
//     }
}
</style>
