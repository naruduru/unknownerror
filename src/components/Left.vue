<template>
  <div class="column left-side">
    <p>1 Left</p>
    <p>2 Left</p>
    <p>Left</p>
    <p>Left</p>
    <p>Left</p>
    <p>Left</p>
    <p>Left</p>
    <p>Left</p>
    <p>Left</p>
    <p>Left</p>
  </div>
</template>

<script>
export default {
  name: "Left"
}
</script>

<style scoped>
.column {
}

.column.left-side {
  width: 164px;
  flex-shrink: 0;
  background-color: red;
}
</style>