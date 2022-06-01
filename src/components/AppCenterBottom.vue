<template>
  <div class="center-bottom">
    <div class="title">
      <p>enjoy reading on maxcoach</p>
      <h2>Latest on <span>Our Blogs</span></h2>
    </div>
    <div class="blogs dimension d-flex">
      <div class="card">
        <img src="../assets/img/artist-blog-03-480x325.jpeg" alt="artist" />
        <p>artist</p>
        <h3>Brush Strokes Energize Trees in Paintings</h3>
        <span><i class="fas fa-calendar"></i> May, 15, 2020 </span>
        <span><i class="far fa-eye"></i> 200 views</span>
      </div>
      <div class="card">
        <img src="../assets/img/artist-blog-01-480x325.jpg" alt="artist" />
        <p>artist</p>
        <h3>Pocket-Sized Notebooks Hold Miniature Paintings</h3>
        <span><i class="fas fa-calendar"></i> May, 15, 2020 </span>
        <span><i class="far fa-eye"></i> 300 views</span>
      </div>
      <div class="card">
        <img src="../assets/img/artist-blog-02-480x325.jpg" alt="artist" />
        <p>artist</p>
        <h3>Connection Between Self-Portraits and Identity</h3>
        <span><i class="fas fa-calendar"></i> May, 15, 2020 </span>
        <span><i class="far fa-eye"></i> 400 views</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AppCenterBottom",
};
</script>

<style lang="scss" scoped>
@import "../style/variable";

.center-bottom {
  padding: 4em;
  .title {
    text-align: center;
    p{
      color: $gray-chateau-color;
    }
    span{
      color: $mountain-meadow-color;
    }
  }
  .blogs {
    margin-top: 2em;
    .card {
      width: calc(100% / 3);
      margin-right: 1em;
      img {
        width: 100%;
        margin-bottom: 0.5em;
      }
      p{
        color: $gray-chateau-color;
      }
      span {
        color: $gray-chateau-color;
        margin-right: 1em;
      }
      h3 {
        margin: 0.5em 0;
      }
    }
  }
}
</style>
