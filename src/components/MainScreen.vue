<template>
  <div class="panel mainScreen">
    <div class="editor"></div>
    <div class="inventory"></div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
@import "../style.scss";

.mainScreen {
    width: 100%;
  .editor {
    height: 75%;
  }
  .inventory {
    background-color: $smoothy_black;
    height: 25%;
  }
}
</style>
