<template>
  <div id="app">
    <HelloWorld :total="total"/>
  </div>
</template>
<script>
import HelloWorld from './components/HelloWorld.vue'
export default {
  // eslint-disable-next-line
  data() {
    return {
      total: 80
    }
  },
  components: {
    HelloWorld
  }
}
</script>

<style lang="less">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
