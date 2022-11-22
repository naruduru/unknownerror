<template>
  <div id="content">
    <Middle/>
    <Right/>
  </div>
</template>

<script>
import Right from "@/components/Right";
import Middle from "@/components/Middle";
export default {
  name: "Content",
  components: {Middle, Right}
}
</script>

<style lang="scss" scoped>
@import "~@/assets/scss/variables.scss";
@import "~@/assets/scss/layouts/content.scss";

@media screen and (max-width: 640px){
  #content {
    width: 100%;
  }
}
</style>