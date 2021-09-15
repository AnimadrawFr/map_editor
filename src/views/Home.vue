<template>
  <div class="home">
    <MainScreen />
    <Sidebar />
  </div>
</template>

<script>
// @ is an alias to /src7

import MainScreen from "@/components/MainScreen.vue";
import Sidebar from "@/components/Sidebar.vue";

export default {
  name: "Home",
  components: {
    MainScreen,
    Sidebar,
  },
};
</script>

<style lang="scss" scoped>
.home {
  display: flex;
  align-items: flex-start;
  height: 100vh;
}
</style>
