<template>
  <div class="main-top">
    <div class="top">
      <div class="text">
        <h2>Let passion and determination be the guide along the way and develop at your own pace that's comfortable.</h2>
        <p>fannie moreno</p>
        <p>/Founder & CEO</p>
      </div>
      <div class="flex">
        <div class="info">
          <div>1926</div>
          <p>finished sessions</p>
        </div>
        <div class="info">
          <div>3.092+</div>
          <p>enrolled learners</p>
        </div>
        <div class="info">
          <div>200</div>
          <p>online instructors</p>
        </div>
        <div class="info">
          <div>100%</div>
          <p>satisfaction rate</p>
        </div>
      </div>
    </div>
    <div class="bottom">
      <div class="services">
        <div class="services-left">
          <div class="services-top">
            <div class="services-text">
              <h3>Graphic Design</h3>
              <p>
                Lorem, ipsum dolor que excepturi debitis, rem in dolores labore,
                earum quod!
              </p>
            </div>
            <img
              src="../assets/img/home-6-service-image-01.png"
              alt="graphic design"
            />
          </div>
          <div class="services-bottom">
            <img
              src="../assets/img/home-6-service-image-03.png"
              alt="graphic design"
            />
            <div class="services-text">
              <h3>Idea Discussion</h3>
              <p>
                Lorem, ipsum dolor que excepturi debitis, rem in dolores labore,
                earum quod!
              </p>
            </div>
          </div>
        </div>
        <div class="services-right">
          <div class="services-top">
            <div class="services-text">
              <h3>Business Administration</h3>
              <p>
                Lorem, ipsum dolor que excepturi debitis, rem in dolores labore,
                earum quod!
              </p>
            </div>
            <img
              src="../assets/img/home-6-service-image-02.png"
              alt="graphic design"
            />
          </div>
          <div class="services-bottom">
            <img
              src="../assets/img/home-6-service-image-04.png"
              alt="graphic design"
            />
            <div class="services-text">
              <h3>Web Development</h3>
              <p>
                Lorem, ipsum dolor que excepturi debitis, rem in dolores labore,
                earum quod!
              </p>
            </div>
          </div>
        </div>
      </div>
      <div class="start">
          <h4>together we can create</h4>
          <h2>Services We Can Provide For My Clients.</h2>
          <ul>
              <li><i class="fa-solid fa-check"></i> Select & customize courses to your preferences</li>
              <li><i class="fa-solid fa-check"></i> Change the tutor and make arrangements</li>
              <li><i class="fa-solid fa-check"></i> Participate in events to join others</li>
              <li><i class="fa-solid fa-check"></i> Get the desired certificate delivered at house</li>
          </ul>
          <button>Get started for free</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AppMainTop",
};
</script>

<style lang="scss" scoped>
@import "../style/variable";
.main-top {
  width: $project-width;
  margin: $project-margin;
  .text {
    padding: 3em;
    text-align: center;
    h2 {
      margin-bottom: 1em;
    }
  }

  .flex {
    display: flex;
    text-align: center;
    .info {
      width: calc(100% / 4);
    }
  }

  .bottom {
    padding: 6em 0;
    display: flex;
    .services {
      display: flex;
      .services-left,
      .services-right {
        width: 40%;
        margin-right: 1em;
        .services-top,
        .services-bottom {
          box-shadow: 5px 5px 20px rgb(208, 208, 208);
          margin-bottom: 1em;
          img {
            width: 100%;
            padding: .5em;
          }
          .services-text {
            padding: 0.5em;
          }
        }
      }

      .services-right{
          margin-top: 2em;
      }
    }

    .start{
        width: 60%;
        display: flex;
        flex-direction: column;
        justify-content: center;
    }
  }
}
</style>
