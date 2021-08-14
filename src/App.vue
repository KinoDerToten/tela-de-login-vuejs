<template>
  <div id="app">
    <Login/>
  </div>
</template>

<script>
import Login from './components/Login.vue'

export default {
  name: 'App',
  components: {
    Login
  }
}
</script>

<style>
  body{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
    font-size: 16px;
    height: 100vh;
    display: flex;
    flex-direction: column;
  }
</style>
