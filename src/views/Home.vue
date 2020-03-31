<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <Header></Header>
    <Body></Body>
    <Footer></Footer>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/global/Header";
import Body from "@/components/global/Body";
import Footer from "@/components/global/Footer";
export default {
  name: 'Home',
  components: {
    Header,
    Body,
    Footer,
  },
};
</script>
