<template>
  <div class="main-top">
    <div class="top">
      <div class="text">
        <h2>ciao sono un h2</h2>
        <p>ciao coa cao</p>
        <p>ciao</p>
      </div>
      <div class="flex">
        <div class="info">
          <div>1926</div>
          <p>finished sessions</p>
        </div>
        <div class="info">
          <div>1926</div>
          <p>finished sessions</p>
        </div>
        <div class="info">
          <div>1926</div>
          <p>finished sessions</p>
        </div>
        <div class="info">
          <div>1926</div>
          <p>finished sessions</p>
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
              <h3>Graphic Design</h3>
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
              <h3>Graphic Design</h3>
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
              <h3>Graphic Design</h3>
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
          <h2>services we can provide for my clients</h2>
          <ul>
              <li><i class="fa-solid fa-check"></i> ahahhhhashururuih</li>
              <li><i class="fa-solid fa-check"></i> ewuecuuuncj</li>
              <li><i class="fa-solid fa-check"></i> cjbkwejjkw</li>
              <li><i class="fa-solid fa-check"></i> crjkjrccejn</li>
          </ul>
          <button>click</button>
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
        width: calc(100% / 3);
        margin-right: 1em;
        .services-top,
        .services-bottom {
          box-shadow: 5px 5px 25px gray;
          margin-bottom: 1em;
          img {
            width: 100%;
            padding-right: 2em;
          }
          .services-text {
            padding: 0.5em;
          }
        }
      }

      .services-right{
          margin-top: 4em;
      }
    }

    .start{
        width: calc(100% / 2);
        display: flex;
        flex-direction: column;
        justify-content: center;
    }
  }
}
</style>
