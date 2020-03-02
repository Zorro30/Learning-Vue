<template>
  <div id="app">
      <Header />
    <router-view/>
  </div>
</template>
<script>
import Header from './components/Layout/Header';
export default {
  name: "app",
  components: {
    Header
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
}

#nav {
  padding: 30px;
}

</style>
