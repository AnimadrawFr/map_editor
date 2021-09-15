<template>
  <div class="panel sidebar" :class="close == true ? 'close' : ''">
    <div class="toggle_button" @click="close = !close"></div>
    <p>AAAAAaaaaaaaA</p>
  </div>
</template>

<script>
export default {
  data: function() {
    return {
      close: false,
    };
  },
  methods: {},
};
</script>

<style lang="scss" scoped>
@import "../style.scss";
.sidebar {
  background-color: $black;
  position: sticky;
  top: 0;
  right: 0;
  width: 15%;
  transition: 0.5s;
  &.close {
    width: 0;
    transition: 0.5s;
  }
  .toggle_button {
    position: absolute;
    top: 80px;
    left: -25px;
    height: 50px;
    width: 25px;
    background-color: $black;
    border-top-left-radius: 5px;
    border-bottom-left-radius: 5px;
    cursor: pointer;
  }
}
</style>
