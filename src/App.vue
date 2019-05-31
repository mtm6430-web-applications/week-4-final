<template>
  <div id="app">
    <div>
       <el-button @click="openDiag = true" type="primary">Welcome</el-button>
       <el-dialog :visible.sync="openDiag"><HelloWorld msg="Welcome to Your Vue.js App"/></el-dialog>
    </div>

  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  },
  data: function () {
    return {
      openDiag: false
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
