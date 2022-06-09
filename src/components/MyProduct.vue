<template>

    <div class="product">

        <img :src="details.thumb" :alt="details.type">

        <h5>{{ details.series }}</h5>

    </div>

</template>

<script>
export default {
    name: 'MyProduct',
    props: {
        details: Object
    }

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.product {
    flex-basis: calc(100% / 6);
    padding: 10px;

    img {
        max-width: 100%;

    }

    h5 {
        color: white;
    }

}
</style>
