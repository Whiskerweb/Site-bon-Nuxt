<template>
  <div class="designsanstitre121-container" v-bind:class="rootClassName">
    <img
      :alt="designsanstitre121Alt"
      :src="designsanstitre121Src"
      class="designsanstitre121-designsanstitre121"
    />
  </div>
</template>

<script>
export default {
  name: 'Designsanstitre121',
  props: {
    designsanstitre121Src: {
      type: String,
      default: '/designsanstitre1211331-83hq-2000w.png',
    },
    rootClassName: String,
    designsanstitre121Alt: {
      type: String,
      default: 'Designsanstitre1211331',
    },
  },
}
</script>

<style scoped>
.designsanstitre121-container {
  display: flex;
  position: relative;
  align-items: center;
  justify-content: center;
}
.designsanstitre121-designsanstitre121 {
  width: 1920px;
  height: 1175px;
}
@media(max-width: 1600px) {
  .designsanstitre121-designsanstitre121 {
    top: -499px;
    left: -698px;
    width: 1384px;
    height: 846px;
    position: absolute;
    align-self: flex-start;
    padding-bottom: 0px;
  }
}
@media(max-width: 1200px) {
  .designsanstitre121-designsanstitre121 {
    top: -502px;
    left: -612px;
    width: 1200px;
    height: 813px;
    margin: auto;
  }
}
</style>
