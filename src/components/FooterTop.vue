<template>
    <div class="footer_top">
        <div class="container">

            <!-- LEFT COL -->
            <div class="footer_col">

                <h3>DC COMICS</h3>
                <ul>
                    <li>
                        <a href="#">Characters</a>
                    </li>
                    
                    <li>
                        <a href="#">Comics</a>
                    </li>
                    <li>
                        <a href="#">Movies</a>
                    </li>
                    <li>
                        <a href="#">TV</a>
                    </li>
                    <li>
                        <a href="#">Games</a>
                    </li>
                    <li>
                        <a href="#">Videos</a>
                    </li>
                    <li>
                        <a href="#">News</a>
                    </li>
                </ul>

                <h3>SHOP</h3>

                <ul>
                    <li>
                        <a href="#">Shop DC</a>
                    </li>
                    <li>
                        <a href="#">Shop DC Collectibles</a>
                    </li>
                </ul>
            </div>

            <!-- MIDDLE COL -->
            <div class="footer_col">
                
                <h3>DC</h3>
                <ul>
                    <li>
                        <a href="#">Terms Of Use</a>
                    </li>
                    
                    <li>
                        <a href="#">Privacy policy (New)</a>
                    </li>
                    <li>
                        <a href="#">Ad Choices</a>
                    </li>
                    <li>
                        <a href="#">Advertising</a>
                    </li>
                    <li>
                        <a href="#">Jobs</a>
                    </li>
                    <li>
                        <a href="#">Subscriptions</a>
                    </li>
                    <li>
                        <a href="#">Talent Workshops</a>
                    </li>
                    <li>
                        <a href="#">CPSC Certificates</a>
                    </li>
                    <li>
                        <a href="#">Ratings</a>
                    </li>
                    <li>
                        <a href="#">Shop Help</a>
                    </li>
                    <li>
                        <a href="#">Contact Us</a>
                    </li>
                </ul>

            </div>

            <!-- RIGHT COL -->
            <div class="footer_col">
                
                <h3>SITES</h3>
                <ul>
                    <li>
                        <a href="#">DC</a>
                    </li>
                    
                    <li>
                        <a href="#">MAD Magazine</a>
                    </li>
                    <li>
                        <a href="#">DC Kids</a>
                    </li>
                    <li>
                        <a href="#">DC Universe</a>
                    </li>
                    <li>
                        <a href="#">DC Power Visa</a>
                    </li>
                    
                </ul>

            </div>

            <div class="footer-logo">
                <img src="../assets/img/dc-logo-bg.png" alt="">
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'FooterTop'
}
</script>

<style lang="scss" scoped>
.footer_top {
    background-image: url(../assets/img/footer-bg.jpg);
}
.container {
    display: flex;
    padding: 30px 0;
}
.footer_col {
    display: flex;
    flex-direction: column;
    margin-right: 40px;
}
h3 {
    color: white;
    margin: 20px 0;
}
a {
    color: #6f716a;
}
img {
    width: 400px;
}
</style>