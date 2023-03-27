<template>
  <div id="app">
    <!-- <img alt="logo" src="./assets/logo.png" /> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    <nav-bar />
    <hello-world />
    <FooterComp />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import NavBar from "./components/NavBar.vue";
import FooterComp from "./components/FooterComp.vue";
//import Welcome from "./components/Welcome.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    NavBar,
    FooterComp,
    //   Welcome,
  },
};
</script>

<style>
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-image: linear-gradient(
    to bottom,
    rgba(0, 162, 255, 0.5),
    rgba(57, 57, 166, 0.5)
  );
}

/* body {
  height: 100vh;
  background-image: linear-gradient(#1ac3fc, #f8c869);
  color: #fff;
  font-family: "Open Sans", sans-serif;
  font-size: 18px;
} */
</style>
