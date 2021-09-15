<template>
  <div id="app">
    <TopToolBar />
    <Home />
  </div>
</template>

<script>
import TopToolBar from "@/components/TopToolBar.vue";
import Home from "@/views/Home.vue";

export default {
  components: {
    TopToolBar,
    Home
  }
}
</script>

<style lang="scss">
@import 'style.scss';

</style>
