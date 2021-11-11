<template>
  <div id="site_main">
    <div class="main_content">
      <section class="container">
        <div class="row">
          <h2>--> Content Goes Here</h2>
        </div>
      </section>
    </div>

    <div class="main_footer">
      <div class="container">
        <div class="row"></div>
      </div>
    </div>
  </div>
  <!-- /#site_main -->
</template>

<script>
</script>

<style lang="scss">
@import "../assets/scss/variables.scss";
#site_main {
  height: 130px;
  background-color: #1c1c1c;
  .container {
    .row {
      align-items: center;
      height: 130px;
      h2 {
        color: white;
      }
    }
  }
  .main_footer {
    height: 150px;
    background-color: $dc_lightblue_color;
  }
}
</style>