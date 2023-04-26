<script>
export default {
    name: "AppHeader",
}
</script>

<template>
    <nav class="d-flex justify-content-between">
        <div class="logo">
            <img src="../assets/img/gym_logo_1x.png" alt="">
        </div>
        <div class="menu align-self-center">
            <ul class="d-flex">
                <li><a href="#">Menu</a></li>
                <li><a href="#">Menu</a></li>
                <li><a href="#">Menu</a></li>
                <li><a href="#">Menu</a></li>
                <li><a href="#">Menu</a></li>
                <li><a href="#">Menu</a></li>
            </ul>
        </div>
    </nav>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

nav {
    background-color: black;

    li {
        list-style: none;
        padding: 0 1.5rem;
    } a {
        text-decoration: none;
        color: $Light;
    }
}
</style>