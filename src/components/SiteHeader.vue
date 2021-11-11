<template>
  <header id="site_header">
    <div class="container">
      <div class="row head_cont">
        <div class="logo">
          <img src="../assets/img/dc-logo.png" alt="" />
        </div>
        <!-- /.logo -->

        <nav class="menu">
          <a href="">CHARACTERS</a>
          <a href="">COMICS<span class="active"></span></a>
          <a href="">MOVIES</a>
          <a href="">TV</a>
          <a href="">GAMES</a>
          <a href="">COLLECTIBLES</a>
          <a href="">VIDEOS</a>
          <a href="">FANS</a>
          <a href="">NEWS</a>
          <a href="">SHOP</a>
        </nav>
        <!-- ./menu -->
      </div>
    </div>
  </header>
</template>

<script>
</script>

<style lang="scss">
@import "../assets/scss/variables.scss";
#site_header {
  .head_cont {
    align-items: center;
    justify-content: space-between;
    height: 120px;

    img {
      width: 80px;
    }

    .menu {
      a {
        margin: 1rem;
        text-decoration: none;
        font-weight: bold;
        font-size: 10px;
        color: black;
        position: relative;
      }
      .active {
        width: 100%;
        height: 5px;
        background-color: $dc_lightblue_color;
        position: absolute;
        bottom: -51px;
        left: 0;
      }
    }
  }
}
</style>