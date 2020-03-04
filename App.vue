<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>

  export default {
    name: 'App',
    components: {}
  }
</script>

<style>
  * {
    box-sizing: border-box;
  }
  body {
    margin: 0;
  }
  a {
    outline: none;
    text-decoration: none;
  }
  #app {
    background-color: #eef0f3;
    height: 100vh;
  }
</style>
