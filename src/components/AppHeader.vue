<script>
    export default {
        name: "AppHeader"
    }
</script>

<template>
    <div class="logo">
        logo
    </div>
    <div>
        <ul>
            <li>CHARACTERS</li>
            <li>COMICS</li>
            <li>MOVIES</li>
            <li>TV</li>
            <li>GAMES</li>
            <li>COLLECTIBLES</li>
            <li>VIDEOS</li>
            <li>FANS</li>
            <li>NEWS</li>
            <li>SHOP</li>
        </ul>
    </div>
</template>

<style scoped lang="scss">
    @use '../styles/partials/variables' as *;

.logo{
    color: $brand-primary;
}
</style>
