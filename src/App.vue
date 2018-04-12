<template>
  <div id="app">
    <Mheader></Mheader>
    <Tab></Tab>
    <router-view style="color:white"></router-view>
  </div>
</template>

<script>
import Mheader from "./components/m-header/m-header"
import Tab from "./components/tab/tab"
export default {
  name: 'App',
  components:{
    Mheader,Tab
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* background-color: white; */
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
