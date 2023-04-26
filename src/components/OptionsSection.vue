<script>
import OptionList from './json/OptionList.json';
export default {
    name: "OptionsSection",
    data() {
        return {
            myJson: OptionList
        }
    },
}
</script>

<template>
    <div class="options_section">
        <div class="container">
            <div class="row">
                <div class="col-3 px-5" v-for="option in myJson.options">
                    <div class="my_card text-center">

                        <h5>{{ option.name }}</h5>

                        <img class="img-fluid" src="../assets/img/divider-x-red.png" alt="">
                        <p>{{ option.phrase }}</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

.options_section {
    background-image: url(../assets/img/gym_bkgd_bw-compressor.jpg);
    padding: 7rem 0;
    background-position: 5rem;

    h5 {
        color: $Light;
    }

    p {
        color: $OsloGrey;
    }
}
</style>