<template>
    <footer>

      <div class="container_footer">
        
        <div class="list">
          <div class="col_sx">

            <H3>DC COMICS</H3>
            <ul>
              <li>
                <a href="#">Home</a>
              </li>
              <li>
                <a href="#">Home</a>
              </li>
              <li>
                <a href="#">Home</a>
              </li>
              <li>
                <a href="#">Home</a>
              </li>
              
            </ul>

            <H3>SHOP</H3>
            <ul>
                 <li>
                <a href="#">Home</a>
              </li>
              <li>
                <a href="#">Home</a>
              </li>
              <li>
                <a href="#">Home</a>
              </li>
              <li>
                <a href="#">Home</a>
              </li>
            </ul>

          </div>
          <div class="col_cen">
            <H3>DC</H3>
            <ul>
               <li>
                <a href="#">Home</a>
              </li>
              <li>
                <a href="#">Home</a>
              </li>
              <li>
                <a href="#">Home</a>
              </li>
              <li>
                <a href="#">Home</a>
              </li>   <li>
                <a href="#">Home</a>
              </li>
              <li>
                <a href="#">Home</a>
              </li>
              <li>
                <a href="#">Home</a>
              </li>
              <li>
                <a href="#">Home</a>
              </li>
            </ul>
          </div>
          <div class="col_dx">
               <H3>SITE</H3>
            <ul>
              <li>
                <a href="#">Home</a>
              </li>
              <li>
                <a href="#">Home</a>
              </li>
              <li>
                <a href="#">Home</a>
              </li>
              <li>
                <a href="#">Home</a>
              </li>
            </ul>
          </div>
        
        </div>
        <div class="container_img">
          <img src="../assets/img/dc-logo-bg.png" alt="">
        </div>
          
      </div>



    </footer>
  
</template>

<script>
export default {
  name: 'MyFooter'
 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
footer{
    width: 100%;
    height: 367px;
    background-image: url("../assets/img/footer-bg.jpg");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    overflow: hidden;
    .container_footer{
    width: 70%;
    margin: auto;
    display: flex;
    justify-content: space-between;

     ul{
        list-style-type: none;
      }
      a{
        color:#959595;
        text-decoration: none;
        font-size: 12px;
      }
   
    }

    .list{
      display: flex;
      justify-content: space-between;
      padding: 40px 0;

      h3{
        color: white;
        padding: 10px 0;
      }

      .col_cen{
        padding: 0 40px;
      }
     
    }



    .container_img{
      img{ 
        position: relative;
        bottom: 110px;
      }
    }

    
}

</style>