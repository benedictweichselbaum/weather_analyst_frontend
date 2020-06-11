<template>
  <div id="app">
    <WeatherHeader/>
  </div>
</template>

<script>
import WeatherHeader from './components/WeatherHeader.vue'

export default {
  name: 'App',
  components: {
    WeatherHeader
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
