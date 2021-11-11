<template>
  <div id="site_main">
    <div class="main_content">
      <section class="container">
        <div class="row_top">
          <h2>--> Content Goes Here</h2>
        </div>
      </section>
    </div>
    <Banner />
  </div>
  <!-- /#site_main -->
</template>

<script>
import Banner from "./Banner.vue";
export default {
  components: { Banner },
};
</script>

<style lang="scss">
@import "../assets/scss/variables.scss";
#site_main {
  background-color: #1c1c1c;
  .container {
    .row_top {
      display: flex;
      align-items: center;
      height: 130px;
      h2 {
        color: white;
      }
    }
  }
}
</style>