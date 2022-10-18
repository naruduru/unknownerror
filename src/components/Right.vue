<template>
  <div class="right-side">
    <p>1 Right</p>
    <p>2 Right</p>
    <p>3 Right</p>
    <p>4 Right</p>
    <p>5 Right</p>
    <p>6 Right</p>
    <p>7 Right</p>
    <p>8 Right</p>
    <p>9 Right</p>
    <p>0 Right</p>
    <p>1 Right</p>
    <p>2 Right</p>
    <p>3 Right</p>
    <p>4 Right</p>
    <p>5 Right</p>
    <p>1 Right</p>
    <p>2 Right</p>
    <p>3 Right</p>
    <p>4 Right</p>
    <p>5 Right</p>
  </div>
</template>

<script>
export default {
  name: "Right"
}
</script>

<style scoped>
.right-side {
  float: right;
  width: 300px;
  background-color: yellow;
}

@media screen and (max-width: 980px) {
  .right-side {
    float: none;
    clear: both;
    width: 100%;
    margin: 0 auto;
    background-color: aqua;
  }
}
</style>