<template>

  <img alt="Vue logo" src="./assets/logo.png">
  <SecondMethod />
  <OmarOmar />
 

</template>


<script>
import SecondMethod from './components/SecondMethod.vue'
import OmarOmar from './components/OmarOmar.vue'


export default {
  name: 'App',
  components: {

    SecondMethod,
    OmarOmar,
  }
}
</script>

<style>
#app {
  font-family: Inter,Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: whitesmoke;
  margin:0;
  background-color: #2c3e50;
  padding:0;
  height:100vh;
}
</style>


