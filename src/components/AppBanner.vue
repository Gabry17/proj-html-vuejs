<template>
  <div class="banner">
    <div class="text">
      <div class="title">
        <h1>Learn At Your Own Pace!</h1>
        <p>Get teamed up with people of the same will.</p>
        <button>Get started for free</button>
      </div>
      <div class="icon bg-white">
        <i class="far fa-square"></i>
        <i class="far fa-life-ring"></i>
        <i class="fas fa-book"></i>
        <i class="fas fa-shopping-cart"></i>
      </div>
    </div>
    <div class="cont-image">
      <div class="image d-flex">
        <img src="../assets/img/home-6-hero-left-person.png" alt="person" />
        <div class="center-image">
          <img
            class="poster-image bg-white"
            src="../assets/img/home-6-hero-poster-final.jpg"
            alt="meeting person"
          />
          <img
            class="play"
            src="../assets/img/icon-youtube-play.png"
            alt="play"
          />
        </div>
      </div>
    </div>
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
    margin: 6em 0;
    position: relative;
    p {
      color: $silver-color;
      margin: 1em 0;
    }
    button:hover {
      background-color: $white-color;
      color: $mountain-meadow-color;
    }
    .icon {
      position: absolute;
      top: 60%;
      right: 0;
      transform: translate(0, -50%);
      border-top-left-radius: 5px;
      border-bottom-left-radius: 5px;
      i {
        display: block;
        color: black;
        padding: 0.5em;
      }
    }
  }
  .cont-image {
    position: relative;
    .image {
      position: absolute;
      left: 10%;
      transform: translate(-10%);
      .center-image {
        position: relative;
        .poster-image {
          padding: 1em;
          border-radius: 10px;
          box-shadow: 0 18px 14px -14px $gray-chateau-color;
        }
        .play {
          width: 100px;
          height: auto;
          position: absolute;
          top: 45%;
          left: 50%;
          transform: translate(-50%, -50%);
        }
      }
    }
  }
}
</style>
