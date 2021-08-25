<template>
  <div class="first">
  <img alt="Vue logo" src="./assets/logo.png">
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
   <Form class="second" /> 
  <Listen />
  </div>
  <!-- <MultiCheckBoxes /> -->
  <DymComponents />
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Form from './components/Form.vue'
import Listen from './components/Listen.vue'
// import MultiCheckBoxes from './components/MultiCheckBoxes.vue'
// import Listf from './components/Listf.vue'
import DymComponents from './components/DymComponents_temp.vue'


export default {
  name: 'App',
  components: {
    // HelloWorld,
    Form,
    Listen,
    // MultiCheckBoxes,
    // Listf,
    DymComponents
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
.first{
  /* align-self: left  0;; */
    text-align: left;
}
.second{
  text-align: left
}
</style>
