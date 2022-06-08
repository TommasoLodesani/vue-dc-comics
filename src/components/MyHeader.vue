<template>
    <header>

      <h1>Questo è l HEADER</h1>

    </header>
  
</template>

<script>
export default {
  name: 'MyHeader'
 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

header{
  text-align: center;
  width: 100%;
  // debug
  height: 115px;
  background-color: green;


  h1{
    color: red;
  }
}
    

</style>
