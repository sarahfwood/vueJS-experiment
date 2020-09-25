<template>
  <div id="app" class="small-container">
    <h1>Employees</h1>
  
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
