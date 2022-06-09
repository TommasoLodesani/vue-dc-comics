<template>
    <div class="container_footerBottom">
        <div class="left_section">
            <button>
                SIGN-UP NOW!
            </button>

        </div>

        <div class="right_section">
            <h3>FOLLOW US</h3>
            <a href="#">
                <img src="../assets/img/footer-facebook.png" alt="logo facebook">

            </a>
            <a href="#">
                <img src="../assets/img/footer-twitter.png" alt="logo twitter">

            </a>
            <a href="#">
                <img src="../assets/img/footer-youtube.png" alt="logo youtube">

            </a>
            <a href="#">
                <img src="../assets/img/footer-pinterest.png" alt="logo pinterest">

            </a>
            <a href="#">
                <img src="../assets/img/footer-periscope.png" alt="logo periscope">
                
            </a>
            
            
            
        </div>


    </div>


</template>

<script>
export default {
    name: 'MyBottomFooter'

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.container_footerBottom {
    width: 70%;
    margin: auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 30px 0;

    button {
        padding: 14px 12px;
        background-color: #303030;
        color: white;
        font-size: 15px;
        font-weight: bold;
        border: 2px solid #0282f9;
    }

    .right_section{
        display: flex;
        justify-content: space-between;
        align-items: center;
        
        h3{
            padding-right: 10px;
            color: #0282f9;
        }
        img{
            padding: 0 10px;
        }
        
    }
}


</style>