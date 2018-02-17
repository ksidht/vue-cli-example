<template>
  <div id="app">
    <img src="./assets/logo.png">
    <HelloWorld msg="welcome to the blockchain world" />
    <Ether msg="Ethereum" />
    <Form/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import Ether from './components/Ether'
import Form from './components/Form'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Ether,
    Form
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
  margin-top: 60px;
}
</style>
