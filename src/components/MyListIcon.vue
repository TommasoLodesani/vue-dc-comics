<template>
    <section id="container_icon">

        <a href="link.url" v-for="(link,index) in links" :key="index">
            <div class="product">
                <img :src="link.immagine" alt="">
                <h5> {{link.text}}</h5>

            </div>

        </a>

    </section>

</template>

<script>
export default {
    name: 'MyListIcon',
    data() {
        return {
            links: [
                {
                    text : "digital comics",
                    url : "#",
                    immagine : require("../assets/img/buy-comics-digital-comics.png")

                },
                {
                    text : "dc merchandise",
                    url : "#",
                    immagine : require("../assets/img/buy-comics-merchandise.png")

                },
                {
                    text : "subscription",
                    url : "#",
                    immagine : require("../assets/img/buy-comics-subscriptions.png")

                },
                {
                    text : "comic shop locator",
                    url : "#",
                    immagine : require("../assets/img/buy-comics-shop-locator.png")

                },
                {
                    text : "dc power visa",
                    url : "#",
                    immagine : require("../assets/img/buy-dc-power-visa.svg")

                },
            ]
        }
    }

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
#container_icon {
    width: 70%;
    margin: auto;
    padding: 50px 20px;
    display: flex;
    justify-content: space-between;

    a{
        text-decoration: none;
    }

    .product {
        display: flex;
        align-items: center;

        img {
            height: 55px;
        }

        h5 {
            color: white;
            margin-left: 15px;
            text-transform: uppercase;
        }
    }


}
</style>
