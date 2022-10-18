<template>
  <div class="footer">
    <div class="site-footer--container">
      <ul>
        <li>Footer</li>
        <li>Footer</li>
        <li>Footer</li>
        <li>Footer</li>
        <li>Footer</li>
        <li>Footer</li>
        <li>Footer</li>
        <li>Footer</li>
        <li>Footer</li>
        <li>Footer</li>
        <li>Footer</li>
        <li>Footer</li>
        <li>Footer</li>
        <li>Footer</li>
        <li>Footer</li>
        <li>Footer</li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer"
}
</script>

<style lang="scss" scoped>
@import "../assets/scss/variables.scss";

.footer {
  display: block;
}

ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: $global_background_color;
  width: 100%;
}

.site-footer--container {
  max-width: $global_width;
  width: 100%;
  margin: 0 auto;
  display: flex;
  flex-flow: row wrap;
}

</style>