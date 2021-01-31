<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Hello Vue 3 + Vite" />
  <Timer />
</template>

<script setup>
import HelloWorld from './components/HelloWorld.vue'
import Timer from './components/Timer.vue'
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
body {
	cursor: url("data:image/svg+xml;utf8, <svg xmlns='http://www.w3.org/2000/svg' width='64' height='64' style='font-size: 64px'><text y='50'>🚀</text></svg>"), auto;
	width: 100%;
	height: 100%;
}
</style>
