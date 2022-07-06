<template>
    <div class="footer_bottom">
        <div class="container">
            <div class="btn">
                <a href="#">SIGN-UP NOW!</a>
            </div>
            <div class="footer_links">
                <span>FOLLOW US</span>
                <div class="social_image">
                    <img src="../assets/img/footer-facebook.png" alt="">
                </div>
                <div class="social_image">
                    <img src="../assets/img/footer-twitter.png" alt="">
                </div>
                <div class="social_image">
                    <img src="../assets/img/footer-youtube.png" alt="">
                </div>
                <div class="social_image">
                    <img src="../assets/img/footer-pinterest.png" alt="">
                </div>
                <div class="social_image">
                    <img src="../assets/img/footer-periscope.png" alt="">
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'FooterBottom'
}
</script>

<style lang="scss" scoped>
@import '../style/variables';
.footer_bottom {
    background-color: #303030;
}
.container {
    display: flex;
    justify-content: space-between;
}
a {
    background-color: #303030;
    border: 3px solid $brand_primary_color;
    color: white;
    padding: 10px;
    line-height: 96px;
}
.footer_links {
    display: flex;
    align-items: center;
}
span {
    color: $brand_primary_color;
    margin-right: 20px;
}
img {
    margin-right: 20px;
}
</style>