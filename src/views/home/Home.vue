<template>
  <div class="home">
    <nav-bar  class="home-nav">
      <div slot="left">◀</div>
      <div slot="center">购物街</div>
      <div slot="right">·</div>
    </nav-bar>
  </div>
</template>

<script>
import NavBar from 'components/common/navbar/NavBar.vue'
export default {
  data () {
    return {

    }
  },
  components: {
    NavBar
  }
}
</script>

<style>
.home-nav {
  background-color: var(--color-tint);
  color: #fff;

  position: fixed;
  left: 0;
  right: 0;
  top: 0;
  z-index: 9;
}
</style>
