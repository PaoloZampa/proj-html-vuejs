<script>
export default {
    name: "Jumbotron",
}
</script>

<template>
    <div class="jumbotron w-100">
        <div class="container text-center">
            <div class="title">
                <h1 class="">
                    NO PAIN NO GAIN
                </h1>
            </div>
            <div class="jumbo_span my-3">
                <span>
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Doloremque ea eum alias perspiciatis voluptate
                </span>
            </div>
            <div class="jumbo_button my-3">
                <a href="#">Join us today</a>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

.jumbotron {
    background-image: url(../assets/img/home-banner.jpg);
    color: $Light;
    padding: 20rem 0;
    background-position: center;

    a {
        text-decoration: none;
        padding: 0.5rem 2rem;
        border: 1px solid $Light;
        color: $Light;
    }

    h1 {
        font-size: 7rem;
    }
}
</style>