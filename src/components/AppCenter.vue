<template>
  <div class="center bg-white">
    <div class="main dimension">
      <h2>Why People Talk About <span class="green">MaxCoach</span>?</h2>
      <div class="info d-flex">
        <img src="../assets/img/testimonial-avata-02.jpg" alt="freelancer" />
        <div class="text">
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Eligendi
            aperiam sequi dignissimos obcaecati sed dolores placeat, commodi ab
            quae illum quaerat officiis! Aperiam tempora sed beatae voluptate,
            optio maiores libero!
          </p>
          <p class="name">
            mina hollage <br />
            <span>/freelancer</span>
          </p>
        </div>
      </div>
      <div class="logo d-flex">
          <img src="../assets/img/client-logo-colored-01.png" alt="aqua">
          <img src="../assets/img/client-logo-colored-02.png" alt="adroll">
          <img src="../assets/img/client-logo-colored-03.png" alt="">
          <img src="../assets/img/client-logo-colored-04.png" alt="wooland">
          <img src="../assets/img/client-logo-colored-05.png" alt="bullfit">
          <img src="../assets/img/client-logo-colored-06.png" alt="sixbase">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AppCenter",
};
</script>

<style lang="scss" scoped>
@import "../style/variable";
.center {
  padding: 4em 0;
  .main {
    h2 {
      margin-bottom: 2em;
      text-align: center;
    }
    .info {
      align-items: center;
      justify-content: space-around;
      margin-bottom: 3em;
      img{
          border-radius: 50%;
          width: 20%;
      }
      .text{
          width: 60%;
          .name{
            text-transform: uppercase;
            margin-top: 1em;
            span{
              color: $gray-chateau-color;
              text-transform: lowercase;
            }
          }
      }
    }
    .logo{
        justify-content: space-between;
        align-items: center;
        img{
            height: 10%;
        }
    }
  }
}
</style>
