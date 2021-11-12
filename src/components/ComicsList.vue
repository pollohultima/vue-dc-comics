<template>
  <div class="card">
    <img :src="thumb" alt="" />
    <p>{{ comicSeries.toUpperCase() }}</p>
  </div>
</template>

<script>
export default {
  props: {
    thumb: String,
    comicSeries: String,
  },
};
</script>

<style lang="scss">
.card {
  margin-top: 40px;
  display: flex;
  flex-direction: column;
  justify-content: start;
  width: calc(100% / 6);
  padding: 14px;
  padding-bottom: 0;
  img {
    height: 185px;
    object-fit: cover;
    object-position: top;
  }
  p {
    padding-top: 23px;
    color: white;
    font-size: 12px;
  }
}
</style>