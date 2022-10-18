<template>
  <div class="left-side">
    <div class="left-side--sticky-container">
      <nav class="left-side-nav">
        <p>1 Left</p>
        <p>2 Left</p>
        <p>3 Left</p>
        <p>4 Left</p>
        <p>5 Left</p>
        <p>6 Left</p>
        <p>7 Left</p>
        <p>8 Left</p>
        <p>9 Left</p>
        <p>10 Left</p>
        <p>11 Left</p>
        <p>12 Left</p>
      </nav>
    </div>
  </div>
</template>

<script>
export default {
  name: "Left"
}
</script>

<style scoped>
.left-side {
  width: 164px;
  flex-shrink: 0;
  background-color: red;
  z-index: 1000;
  position: relative !important;
}

@media screen and (max-width: 640px) {
  .left-side {
    display: none;
  }
}

.left-side--sticky-container {
  position: sticky;
  width: auto;
  overflow-y: auto;
  background-color: coral;
  max-height: calc(100vh - 50px);
  top: 50px;
}


.left-side-nav {
  display: block;
}
</style>