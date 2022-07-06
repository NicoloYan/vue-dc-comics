<template>
    <div class="cta_section">
        <div class="container">

            <div class="cta_card">
                <div class="card_img">
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="digital comics">
                </div>
                <div class="cta_text">
                    DIGITAL COMICS
                </div>
            </div>

            <div class="cta_card">
                <div class="card_img">
                    <img src="../assets/img/buy-comics-merchandise.png" alt="digital comics">
                </div>
                <div class="cta_text">
                    DC MERCHANDISE
                </div>
            </div>

            <div class="cta_card">
                <div class="card_img">
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="digital comics">
                </div>
                <div class="cta_text">
                    SUBSCRIPTION
                </div>
            </div>

            <div class="cta_card">
                <div class="card_img">
                    <img src="../assets/img/buy-comics-shop-locator.png" alt="digital comics">
                </div>
                <div class="cta_text">
                    COMIC SHOP LOCATOR
                </div>
            </div>

            <div class="cta_card">
                <div class="card_img">
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="digital comics">
                </div>
                <div class="cta_text">
                    DC POWER VISA
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'CtaSection'
}
</script>

<style lang="scss" scoped>
@import '../style/variables';
.cta_section {
    background-color: $brand_primary_color;
}
.container {
    display: flex;
    padding: 30px;
    justify-content: space-between;
}
.cta_card {
    display: flex;
    align-items: center;
}
.cta_text {
    font-size: 12px;
    color: white;
}
img {
    width: 35px;
    margin-right: 10px;
}
</style>