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
            <div class="col-4">
              <div class="dc">
                <h3>DC</h3>
                <ul>
                  <li><a href="">Terms Of Use</a></li>
                  <li><a href="">Privacy policy (New)</a></li>
                  <li><a href="">Ad Choices</a></li>
                  <li><a href="">Advertising</a></li>
                  <li><a href="">Jobs</a></li>
                  <li><a href="">Subscriptions</a></li>
                  <li><a href="">Talent Workshops</a></li>
                  <li><a href="">CPSC Certificates</a></li>
                  <li><a href="">Ratings</a></li>
                  <li><a href="">Shop Help</a></li>
                  <li><a href="">Contact Us</a></li>
                </ul>
              </div>
            </div>
            <div class="col-4">
              <div class="sites">
                <h3>SITES</h3>
                <ul>
                  <li><a href="">DC</a></li>
                  <li><a href="">MAD Magazines</a></li>
                  <li><a href="">DC Kids</a></li>
                  <li><a href="">DC Universe</a></li>
                  <li><a href="">DC Power Visa</a></li>
                </ul>
              </div>
            </div>
          </div>
        </div>
        <div class="logo_bg">
          <img src="../assets/img/dc-logo-bg.png" alt="" />
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
      padding: 30px 0;
      width: 400px;
      color: white;
      h3 {
        padding: 15px 0 10px 0;
        font-size: 16px;
      }
      ul {
        list-style: none;
        li {
          a {
            text-decoration: none;
            color: white;
            font-size: 9px;
          }
        }
      }
    }
    .container {
      position: relative;
    }
    .logo_bg {
      position: absolute;
      right: 0;
      top: -100px;
    }
  }
}
</style>