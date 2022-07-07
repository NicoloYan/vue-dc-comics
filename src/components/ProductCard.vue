<template>
    <div class="card"> 
        <img :src="productInfo.thumb" :alt="productInfo.series">
        <h3>{{ productInfo.series }}</h3>
    </div>
</template>

<script>
export default {
    name: 'ProductCard',
    props: {
        productInfo: Object
    }
}
</script>

<style lang="scss" scoped>
.card {
    background-color: white;
    width: calc((100% / 6 ) - 15px);
    margin: 30px 0;
}
img {
    width: 100%;
}
</style>