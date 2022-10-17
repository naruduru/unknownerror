<template>
  <Left/>
  <Content/>
</template>

<script>
import Left from "@/components/Left";
import Content from "@/components/Content";
export default {
  name: "Container",
  components: {Content, Left}
}
</script>

<style scoped>

</style>