<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
  html{
    font-size: 16px;
    color: #666666;
  }
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

  /*text-align: center;*/
  /*color: #2c3e50;*/
  }
  .mu-primary-text-color{
    font-size: 16px;
  }
</style>
