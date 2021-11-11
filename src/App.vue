<template>
  <div id="app">
    <Header/>
    <Search/>
    <TransportControls/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Search from './components/Search.vue'
import TransportControls from './components/TransportControls.vue'

export default {
  name: 'App',
  components: {
    Header,
    Search,
    TransportControls
  }
}
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
