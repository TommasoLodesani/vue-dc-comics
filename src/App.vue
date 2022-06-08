<template>
  <div id="app">
    <MyHeader/>

    <main>
      <MyProducts/>
    </main>


    <MyFooter/>
  </div>
</template>

<script>
import MyHeader from './components/MyHeader.vue'
import MyFooter from './components/MyFooter.vue'
import MyProducts from './components/MyProducts.vue'

export default {
  name: 'App',
  components: {
    MyHeader,
    MyFooter,
    MyProducts

  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  // text-align: center;
  color: #2c3e50;
  // margin-top: 60px;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
