<template>
  <div class="content">
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

<style scoped>
.content {
  width: calc(100% - 164px);
  max-width: 1100px;
  margin: 0 auto;
}

@media screen and (max-width: 640px){
  .content {
    width: 100%;
  }
}
</style>