<template>
  <div id="app">
    <Pro />
  </div>
</template>

<script>
import Pro from "./components/Pro/Pro.vue";

export default {
  name: "App",
  components: {
    Pro
  }
};
</script>

<style>
html,
body {
  padding: 0;
  margin: 0;
}
#app {
  width: 100vw;
  height: 100vh;
}
</style>
