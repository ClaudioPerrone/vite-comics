<script>
    export default {
        name: 'ComicCard',
        props: {
            comicInfo: Object
        }
    }
</script>

<template>
    <div class="card">
        <img :src=comicInfo.thumb alt="">
    </div>
    <h4 class="title">{{ comicInfo.series }}</h4>
</template>

<style scoped lang="scss">

.title {
    color: white;
}
img {
    object-fit: cover;
    object-position: top;
    width: 100%;
    height: 200px;
}
</style>