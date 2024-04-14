<script>
    export default {
        name: "AppMain"
    }
</script>

<template>
    <main>

        <div class="container">
            <div class="content">
                <------ CONTENT HERE

            </div>
        </div>
    </main>
</template>

<style scoped lang="scss">
    @use '../styles/partials/variables' as *;

    main {
        padding: 30px 0;
        background-color: $brand-secondary-darker
    }

    .content {
        color: white;
    }
</style>
