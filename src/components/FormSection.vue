<script>
export default {
    name: "FormSection",
}
</script>

<template>
    <div class="form_section">
        <div class="container">
            <div class="row">
                <div class="col-6">
                    <div class="form_image">
                        <img class="img-fluid" src="../assets/img/home_img-compressor.jpg" alt="">
                    </div>
                </div>
                <div class="col-6">
                    <h3 class="text-center mx-3">Sign up for a free training session!</h3>
                    <div class=" mx-3 my_form p-4 d-flex flex-column">
                        <span>Name...</span>
                        <input class="mb-4" type="text" placeholder="Jhon Doe"/>
                        <span>Email...</span>
                        <input class="mb-4" type="email" placeholder="JhonDoe@example.com"/>
                        <button type="submit">START NOW!</button>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

.form_section {
    padding: 8rem 0;
    background-color: $SharkLight;
    color: $Light;
    h3 {
        font-weight: 900;
    }

    input{
        padding: 0.4rem;
    }

    button{
        padding: 0.8rem 1rem;
        background-color: $ChestnutRose;
        border: none;
        color: $Light;
    }
}
</style>