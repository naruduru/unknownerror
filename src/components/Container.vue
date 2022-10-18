<template>
  <div class="container">
    <Left/>
    <Content/>
  </div>
</template>

<script>
import Left from "@/components/Left";
import Content from "@/components/Content";
export default {
  name: "Container",
  components: {Content, Left}
}
</script>

<style lang="scss" scoped>
@import "../assets/scss/variables.scss";
.container {
  display: flex;
  position: relative;
  flex: 1 0 auto;
  width: 100%;
  max-width: $global_width;
  margin: 0 auto;
}
</style>