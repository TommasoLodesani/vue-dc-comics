<template>
    <header>
      <img src="../assets/img/dc-logo.png" alt="logo DC">

      <nav>
        <ul>
          <li v-for="(link, inedx) in links" :key="inedx">
            <a href="link.url" :class="link.current ? 'here' : '' "> {{link.text}}</a>
          </li>          
        </ul>
      </nav>

      

    </header>
  
</template>

<script>
export default {
  name: 'MyHeader',
  data(){
    return {
      links :[
        {
          text : "CHARACTERS",
          url : "#",
          current : false
        },
        {
          text : "COMICS",
          url : "#",
          current : true
        },
        {
          text : "MOVIE",
          url : "#",
          current : false
        },
        {
          text : "TV",
          url : "#",
          current : false
        },
        {
          text : "GAMES",
          url : "#",
          current : false
        },
        {
          text : "COLLECTIBLES",
          url : "#",
          current : false
        },
        {
          text : "VIDEOS",
          url : "#",
          current : false
        },
        {
          text : "FANS",
          url : "#",
          current : false
        },
        {
          text : "NEWS",
          url : "#",
          current : false
        },
        {
          text : "SHOP",
          url : "#",
          current : false
        }
       
      ]
    }
  }
 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

header{
  width: 70%;
  margin: auto;
  padding: 20px 20px;
  display: flex;
  align-items: center;
  justify-content: space-between;

  img{
    height: 80px;
  }

  ul{
    list-style-type: none;

    li{
      display: inline-block;
      padding: 0 15px;

      a{
        text-decoration: none;
        color: black;
        font-size: 12px;
        font-weight: bold;

        &:hover{
          color: #0c7cec;
        }
        &.here{
          border-bottom: solid 4px #0c7cec;
          padding-bottom: 42px;
          color: #0c7cec;
        }
      }

    }
    
  }

}
    

</style>
