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
  margin: 0;
}

div {
  display: block;
  padding: 0;
  border: 0;
}

h1, h2, h3 {
  line-height: 1.3;
  margin: 0 0 1em;
  padding: 0;
  border: 0;
  font: inherit;
  font-size: 100%;
  vertical-align: baseline;
}

#middle h2, .middle h2, #middle h3, .middle h3, #middle h4, .middle h4 {
  font-weight: 400;
}
</style>
