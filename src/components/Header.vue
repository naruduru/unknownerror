<template>
  <header>
    <div class="top-bar">
        <ul>
          <li style="height: 50px">Unknown Error</li>
          <li>About</li>
          <li>Products</li>
          <li>For Teams</li>
        </ul>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style lang="scss" scoped>
@import "../assets/scss/variables.scss";
.top-bar {
  position: fixed !important;
  left: 0 !important;
  top: 0 !important;
  min-width: auto;
  width: 100%;
  height: 50px;
  align-items: center;
  z-index: 5050;
}

ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: $black-025;
}

li {
  float: left;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

li a:hover {
  background-color: #111;
}
</style>