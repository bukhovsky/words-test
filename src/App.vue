<template>
<div>
  <img alt="Vue logo" src="./assets/logo.png">

  <input type="text">

  <Button1 msg="Start"/>
</div>  
</template>

<script>
import Button1 from './components/Button1.vue'


export default {
  name: 'App',
  components: {
    Button1
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
