<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: "App",
  methods: {}
};
</script>

<style scoped></style>

<style>
html {
  margin: 0;
  padding: 0;
}
body {
  margin: 0;
  padding: 0;
  font-size: 16px;
  font-family: Arial, sans-serif;
  color: #232321;
  background: #fff !important;
}
html,
body,
#app {
  height: 100%;
  width: 100%;
  box-sizing: border-box;
}
#app {
  overflow: auto;
}
* {
  margin: 0;
  padding: 0;
}
</style>
