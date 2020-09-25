<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    EmployeeTable,
  }
}
</script>

<style>
button {
  background: #009435;
  border: 1px sold #009435;
}

.small container {
  max-width: 680px;
}
</style>
