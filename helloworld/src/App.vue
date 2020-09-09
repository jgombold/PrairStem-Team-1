<template>
<!--The template is simple html that is inserted into the html-->
  <div id="app">
    <img alt="Vue logo" src="./assets/PStem.png">
    <HelloWorld msg="This is our Capstone"/><!--You can also insert data into a template, like here w/ HellowWorld-->
    <!--Located in the components folder-->
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
//since we used HelloWorld in the template, we have to import it in the script

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
//we also need to export this part (App.vue) so it can be used in the html
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
/*this is just style stuff for the template, this also applies to the components attached to it*/
</style>
