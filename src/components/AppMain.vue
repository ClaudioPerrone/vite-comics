<script>
    import ComicsList from './ComicsList.vue';

    export default {
        name: "AppMain",
        components: {
            ComicsList
        },
        props: {
            image: String,
            title: String
        }
    }
</script>

<template>
    <div class="hero"></div>
    <main>
        <ComicsList></ComicsList>
    </main>
</template>

<style scoped lang="scss">
    @use '../styles/partials/variables' as *;

    main {
        padding: 30px 0;
        background-color: $brand-secondary-darker;
    }

    .hero {
        background-image: url("../src/assets/img/jumbotron.jpg");
        background-size: 100%;
        height: 300px;
    }
</style>
