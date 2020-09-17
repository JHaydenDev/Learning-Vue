<template>
  <div class="wrapper">
    <div class="background">
      <img alt="Vue logo" src="./assets/logo.png" />
      <HelloAppDash msg="Hello App Dash." />
    </div>
  </div>
</template>

<script>
import HelloAppDash from "./components/HelloAppDash.vue";
import "reset-css";

export default {
  name: "App",
  components: {
    HelloAppDash,
  },
};
</script>

<style>
body {
  margin: 0 auto;
  background: black;
}

.wrapper {
  width: 800px;
  margin: 0 auto;
  background-image: url("~@/assets/BeachBackground.jpg");
  background-size: cover;
}
.background {
  background: rgba(0, 0, 0, 0.5);
  width: 800px;
  margin: 0 auto;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;
}
</style>
