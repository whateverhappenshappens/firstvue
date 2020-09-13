<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="utkarsh is nice boy" msg2="ankit is gandu"/>
  <hello/>
  <HelloWorld msg="utkarsh is nice boy" msg2="ankit is gandu"/>

</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import hello from './components/hello.vue'
export default {
  name: 'App',
  components: {
    HelloWorld,
    hello
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
