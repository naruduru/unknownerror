<template>
  <Header/>
  <Container/>
  <Footer/>
</template>

<script>
import Header from "@/components/Header";
import Footer from "@/components/Footer";
import Container from "@/components/Container";

export default {
  name: 'App',
  components: {
    Container,
    Header,
    Footer
  }
}
</script>

<style lang="scss">
@import "~@/assets/scss/layouts/app.scss";
@import "~@/assets/scss/layouts/common.scss";
</style>
