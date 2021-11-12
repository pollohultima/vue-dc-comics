<template>
  <div class="main_footer">
    <div class="container">
      <div class="row">
        <div class="col5">
          <div class="icon">
            <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
            <p>DIGITAL COMICS</p>
          </div>
        </div>
        <div class="col5">
          <div class="icon">
            <img src="../assets/img/buy-comics-merchandise.png" alt="" />
            <p>DC MERCHANDISE</p>
          </div>
        </div>
        <div class="col5">
          <div class="icon">
            <img src="../assets/img/buy-comics-subscriptions.png" alt="" />
            <p>SUBSCRIPTION</p>
          </div>
        </div>
        <div class="col5">
          <div class="icon">
            <img src="../assets/img/buy-comics-shop-locator.png" alt="" />
            <p>COMIC SHOP LOCATOR</p>
          </div>
        </div>
        <div class="col5">
          <div class="icon">
            <img
              class="visa"
              src="../assets/img/buy-dc-power-visa.svg"
              alt=""
            />
            <p>DC POWER VISA</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
</script>

<style lang="scss">
@import "../assets/scss/variables.scss";
.main_footer {
  height: 150px;
  background-color: $dc_lightblue_color;
  z-index: 1;
  position: relative;
  .container {
    height: 150px;
    .icon {
      display: flex;
      align-items: center;

      p {
        padding-left: 1rem;
        color: white;
        font-size: 10px;
      }
      img {
        height: 55px;
      }
    }
    .row {
      height: 150px;
    }
  }
  .visa {
    width: 55px;
  }
}
</style>