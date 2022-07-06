<template>
    <header class="container">
        <!-- LOGO -->
        <div class="logo">
            <img src="../assets/img/dc-logo.png" alt="dc logo">
        </div>

        <!-- NAVBAR -->
        <nav>
            <ul>
                <li v-for="link, index in navLinks" :key="index" :class="{ 'active': link.active }">
                    <a :href="link.url">{{ link.text }}</a>
                </li>
            </ul>
        </nav>
    </header>
</template>

<script>
export default {
    name: "PageHeader",
    data() {
        return {
            navLinks: [
                {
                    text: 'CHARACTERS',
                    url: '#',
                    active: false
                },
                {
                    text: 'COMICS',
                    url: '#',
                    active: true
                },
                {
                    text: 'MOVIES',
                    url: '#',
                    active: false
                },
                {
                    text: 'TV',
                    url: '#',
                    active: false
                },
                {
                    text: 'GAMES',
                    url: '#',
                    active: false
                },
                {
                    text: 'COLLECTIBLES',
                    url: '#',
                    active: false
                },
                {
                    text: 'VIDEOS',
                    url: '#',
                    active: false
                },
                {
                    text: 'FANS',
                    url: '#',
                    active: false
                },
                {
                    text: 'NEWS',
                    url: '#',
                    active: false
                },
                {
                    text: 'SHOP',
                    url: '#',
                    active: false
                }
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
@import '../style/variables';

header {
    height: 85px;
    display: flex;
    justify-content: space-between;
}
img {
    width: 60px;
}
.logo {
    display: flex;
    align-items: center;
}
.active {
    border-bottom: 5px solid $brand_primary_color;
}
ul {
    display: flex;
}
a {
    color: #303030;
    font-size: 12px;
    line-height: 80px;
}
li {
    margin: 0 8px;
}
</style>