<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="La mia prima app con Vue CLI!"/>
    <MyNewComponent/>
  </div>
</template>


<script>
import HelloWorld from './components/HelloWorld.vue'
import MyNewComponent from './components/MyNewComponent.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    MyNewComponent
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
