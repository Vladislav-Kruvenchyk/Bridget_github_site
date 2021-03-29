<template>
    <div class="img">
        <div class="container">
            <div class="block_img"></div>
            <div class="block_img"></div>
            <div class="block_img"></div>
            <div class="block_img"></div>
            <div class="block_img"></div>
            <div class="block_img"></div>
            <div class="block_img"></div>
            <div class="block_img"></div>
        </div>
    </div>
</template>

<script>
export default {
    nama: 'Img'
}
</script>


<style lang="scss" scoped>
.img {
    display: flex;
    width: 100%;

}

.container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    overflow: hidden;
    margin-top: 5rem;
}

.block_img {
    display: flex;
    width: 475px;
    height: 407px;
    background: url('../assets/block_foure_img/Rectangle 3.png');
    background-size: cover;
}
</style>