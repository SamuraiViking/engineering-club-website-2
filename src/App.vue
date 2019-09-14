<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>

export default {
  created() {
    document.title = "Engineering Club"  
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  height: 100%;
}
.center {
  margin: 0px auto;
}

html, body {
  padding: 0px;
  margin: 0px;
}

</style>
