<template>

    <div class="col-2">
        <div class="card-container">
            <img :src="img" alt="Card Image">
        </div>
        <h3>{{ title }}</h3>
        <!-- FIX IT -->
        <p>{{ price }}</p>
    </div>

</template>

<script>
export default {
    // questo dovrà essere eportato nel main
    name: "Card", 

    // cosa gli viene passato per tipologia ed elemento dal data 
    props: {
        img: String,
        title: String,
        prirce: String,
    }
}
</script>

<style lang="sass" scoped>

</style>