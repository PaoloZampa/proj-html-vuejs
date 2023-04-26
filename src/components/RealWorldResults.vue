<script>
import DataList from './json/DataList.json'
export default {
    name: "RealWorldResults",
    data() {
        return {
            myJson: DataList
        }
    },
}
</script>

<template>
    <div class="container">
        <div class="row">
            <div class="col-6" v-for="customer in myJson.customers">
                <div class="my_card">
                    <div class="card_image">
                        <img :src="customer.image" alt="">
                        <h6>{{ customer.name }}</h6>
                        <span>{{ customer.phrase }}</span>
                    </div>
                    <div class="card_text"></div>
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped></style>