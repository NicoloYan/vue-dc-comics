<template>
    <div class="content_section">
        <div class="container">
            <span>--- Content goes here ---</span>
        </div>
    </div>
</template>

<script>
export default {
    name: 'ContentSection'
}
</script>

<style lang="scss" scoped>
.content_section {
    background-color: black;
    height: 80px;
    display: flex;
    align-items: center;
}
span {
    color: white;
    padding: 40px 0;
}
</style>