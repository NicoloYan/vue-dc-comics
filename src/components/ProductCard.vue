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
    width: calc((100% / 6 ) - 15px);
    margin: 30px 0;
}
img {
    width: 100%;
    margin-bottom: 10px;
}
h3 {
    color: #6f716a;
    text-transform: uppercase;
    font-size: 12px;
}
</style>