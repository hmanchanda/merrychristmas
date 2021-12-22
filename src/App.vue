<template>
  Hi there!! Looking for your present.. I see 
  <button @click="navigate(2)">Next</button>
  <!-- <img src="https://img.imageekhub.com/default/202012/20a06ff2-4.gif" title="1, 5-Christmas-gifts-for-girlfriend.gif" alt="1, 5-Christmas-gifts-for-girlfriend.gif"> -->
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  },
  methods:{
    navigate(page){
      this.$router.push(page)
    }
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
</style>
