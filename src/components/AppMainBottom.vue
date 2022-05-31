<template>
  <div class="bottom">
      <div class="title">
          <p>wanna transform your life?</p>
          <h2>Glad to <span>Help You</span> Learn</h2>
      </div>
      <div class="content">
          <div class="service">
              <i class="fab fa-font-awesome-flag"></i>
              <h3>Idea Discussion</h3>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Consectetur, hic repellendus! </p>
          </div>
          <div class="service">
              <i class="fas fa-cog"></i>
              <h3>Web Development</h3>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Consectetur, hic repellendus! </p>
          </div>
          <div class="service">
              <i class="fas fa-life-ring"></i>
              <h3>System Administration</h3>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Consectetur, hic repellendus! </p>
          </div>
          <div class="service">
              <i class="fas fa-desktop"></i>
              <h3>Graphic Design</h3>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Consectetur, hic repellendus! </p>
          </div>
      </div>
      <div class="image">
          <img src="../assets/img/home-6-services-image-768x308.png" alt="people work">
      </div>
      <div class="text">
          <p>Start today for getting <span>Online Certification</span></p>
          <h3>You can be your own guiding star with our help</h3>
          <button>Get started now</button>
      </div>
  </div>
</template>

<script>
export default {
    name: 'AppMainBottom'
}
</script>

<style lang="scss" scoped>
@import '../style/variable';

.bottom{
    padding-top: 4em;
    .title{
        text-align: center;
        padding: 2em;
        p{
            margin: .5em 0;
            color: $gray-chateau-color;
        }
        span{
            color: $mountain-meadow-color;
        }
    }
    .content{
        width: $project-width;
        margin: $project-margin;
        display: flex;
        .service{
            width: calc(100% / 4);
            & i{
                font-size: 2em;
            }
            & h3{
                margin: .3em 0;
            }
            p{
                color: $gray-chateau-color;
            }
        }
    }
    .image{
        text-align: center;
        width: $project-width;
        margin: $project-margin;
        padding-top: 4em;
        img{
            width: 100%;
        }
    }
    .text{
        text-align: center;
        padding: 5em;
        button{
            margin-top: 1.5em;
        }
        span{
            color: $mountain-meadow-color;
        }
    }
}
</style>