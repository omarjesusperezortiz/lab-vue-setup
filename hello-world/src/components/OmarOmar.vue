<template>
  <button @click="helloWorld">Muestra Hello World</button>
	<p>The button above has been clicked {{ holaMundo }}.</p>
  <p id="holaMundo"></p>
</template>

<script>


export default {
  data() {
    return {
      name: 'Vue.js',
      holaMundo: 'aun nada'
    }
  },
 

  methods: {
  
  helloWorld() {
    console.log("Hola Mundo")
    // const holaMundo = document.querySelector('#holaMundo')
    // holaMundo.innerHTML = `<div>Hola Mundo!</div>`
    this.holaMundo = 'Hola Mundo'
  }
}
  
}

    
</script>