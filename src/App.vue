<script>
    import AppHeader from './components/AppHeader.vue';
    import ComicsList from './components/ComicsList.vue';
    import AppMain from './components/AppMain.vue';
    import AppFooter from './components/AppFooter.vue';

    export default {
        components: {
            AppHeader,
            AppMain,
            AppFooter
        }
    }
</script>

<template>
    <AppHeader></AppHeader>

    <main>
        <AppMain>
            
        </AppMain>
        <!-- METTERE LA PARTE BLU DEL MAIN -->
    </main>
    <AppFooter></AppFooter>
</template>

<style lang="scss">
    @use './styles/generics';
</style>
