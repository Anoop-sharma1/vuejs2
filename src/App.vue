<template>
  <div id="app">
    <ActiveBoot/>
  </div>
</template>

<script>

import ActiveBoot from './components/ActiveBoot'

export default {
  name: 'App',
  components: {
    ActiveBoot
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
