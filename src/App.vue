<template>
  <div id="app">
    <MyHeader/>

    <main>

      <section>
        <MyJumbotron/>

      </section>

      <section id="products">
        <MyProducts/>

      </section>

      <section id="icon">
        <MyListIcon/>

      </section>
    </main>

    <MyFooter/>
    
  </div>
</template>

<script>
import MyHeader from './components/MyHeader.vue'
import MyFooter from './components/MyFooter.vue'
import MyProducts from './components/MyProducts.vue'
import MyListIcon from './components/MyListIcon.vue'
import MyJumbotron from './components/MyJumbotron.vue'

export default {
  name: 'App',
  components: {
    MyHeader,
    MyFooter,
    MyProducts,
    MyListIcon,
    MyJumbotron

  }
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;

}


#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  // text-align: center;
  color: #2c3e50;
  // margin-top: 60px;

  #icon{
    background-color: #0282f9;
  }
  
  #products{
    background-color: #1c1c1c;
  }

  
}
</style>
