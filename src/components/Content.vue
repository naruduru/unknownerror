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

<style scoped>
#content {
  max-width: 1100px;
  width: calc(100% - 164px);
  background-color: hsl(0,0%,100%);
  border-radius: 0;
  border: 1px solid hsl(210,8%,85%);
  border-top-width: 0;
  border-bottom-width: 0;
  border-left-width: 1px;
  border-right-width: 0;
  padding: 24px;
  box-sizing: border-box;
}

@media screen and (max-width: 640px){
  .content {
    width: 100%;
  }
}
</style>