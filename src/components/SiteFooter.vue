<template>
  <div id="site_footer">
    <div class="links">
      <div class="container">
        <div class="sub_cont">
          <div class="row">
            <div class="col-4">
              <div class="dc_comics_shop">
                <h3>DC COMICS</h3>
                <ul>
                  <li><a href="">Characters</a></li>
                  <li><a href="">Comics</a></li>
                  <li><a href="">Movies</a></li>
                  <li><a href="">TV</a></li>
                  <li><a href="">Games</a></li>
                  <li><a href="">Videos</a></li>
                  <li><a href="">News</a></li>
                </ul>

                <h3>SHOP</h3>
                <ul>
                  <li><a href="">Shop DC</a></li>
                  <li><a href="">Shop DC Collectibles</a></li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="site_end">
      <div class="container"></div>
    </div>
  </div>
  <!-- /#site_footer -->
</template>

<script>
export default {
  setup() {},
};
</script>

<style lang="scss">
#site_footer {
  .links {
    height: 375px;
    background-image: url("../assets/img/footer-bg.jpg");
    .sub_cont {
      padding: 35px 0;
      width: 375px;
      color: white;
      h3 {
        padding: 10px 5px 0 0;
      }
      ul {
        list-style: none;
        li {
          padding: 2px 0;
          a {
            text-decoration: none;
            color: white;
            font-size: 9px;
          }
        }
      }
    }
  }
}
</style>