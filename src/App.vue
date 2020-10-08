<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <img
      alt="Docker logo"
      src="https://www.docker.com/sites/default/files/social/docker_facebook_share.png"
    />
    <HelloWorld msg="Malcolm testing Vue on Docker" />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
