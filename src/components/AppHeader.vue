<script>
    export default {
        name: "AppHeader"
    }
</script>

<template>
    <header class="container d-flex justify-content-between">
        <div class="logo">
            logo
        </div>
        <div class="list">
            <ul class="d-flex px-2">
                <li><a href="#">CHARACTERS</a></li>
                <li><a href="#">COMICS</a></li>
                <li><a href="#">MOVIES</a></li>
                <li><a href="#">TV</a></li>
                <li><a href="#">GAMES</a></li>
                <li><a href="#">COLLECTIBLES</a></li>
                <li><a href="#">VIDEOS</a></li>
                <li><a href="#">FANS</a></li>
                <li><a href="#">NEWS</a></li>
                <li><a href="#">SHOP</a></li>
            </ul>
        </div>
    </header>
</template>

<style scoped lang="scss">
    @use '../styles/partials/variables' as *;

header {
    padding: 30px 0;
}
/* ----------------------

        LOGO

----------------------- */
.logo{
    color: $brand-primary;
}
/* ----------------------

        LIST

----------------------- */

li {
    list-style-type: none;
    padding: 0 10px; 

    a {
        text-decoration: none;
        color: $brand-secondary;
    }
}
</style>
