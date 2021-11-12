<template>
  <div class="card">
    <img :src="thumb" alt="" />
    <h4>{{ comicSeries }}</h4>
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
</style>