<template>
  <button @click="helloWorld2">Muestra Hello World</button>
	<p>The button above has been clicked {{ holaMundo2 }}.</p>
</template>

<script setup>

const holaMundo2  = 'aun nada'

const helloWorld2 = () => {
    console.log("Hola Mundo")
    // const holaMundo = document.querySelector('#holaMundo')
    // holaMundo.innerHTML = `<div>Hola Mundo!</div>`
    holaMundo2.value = 'Hola Mundo'
  }

</script>