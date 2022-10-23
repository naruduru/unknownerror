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

<style>
body * {
  box-sizing: inherit;
}
body {
  padding-top: 50px;
  display: flex;
  min-height: 100%;
  flex-direction: column;
}

div {
  display: block;
}
</style>
