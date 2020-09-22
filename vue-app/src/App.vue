<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
  <HelloWorld msg="This is an experiment to test and understand VueJS" />

  <!-- <div id="table">
  <table>
    <thead>
      <tr>
        <th>Name</th>
        <th>Email</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Joe Bloggs</td>
        <td>joebloggs@vueexperiment.com</td>
      </tr>
      <tr>
        <td>Jane Doe</td>
        <td>janedoe@vueexperiment.com</td>
      </tr>
    </tbody>
  </table>
</div> -->

</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld, 
  },
};
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
