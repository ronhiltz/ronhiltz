<template>
  <div id="app">
    <img src="./assets/logo.png">
    <RonsPizzaShack/>
    <img src="./assets/ChickenTikka.png">
    <img src="./assets/DSCheese.png">
    <img src="./assets/DSBrisket.png">
    <img src="./assets/DSHamPineapple.png">
  </div>
</template>

<script>
import RonsPizzaShack from './components/RonsPizzaShack'

export default {
  name: 'App',
  components: {
    RonsPizzaShack
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