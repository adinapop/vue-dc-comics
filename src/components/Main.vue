<template>
    <main>
       
       <div class="container">

           <div class="card-container row">    

            <Card 
                v-for = "(element, index) in comics"
                :key = "index"
                :img = "element.thumb"
                :title = "element.series"
                :price = "element.price"
            />

           </div>

       </div>
        
    </main>
</template>

<script>
// prima di utilizzare il componente Card, devo importarlo
import Card from "./Card.vue"

export default {
    name: "Main",
    components: {
        Card,
    },
    // cosa gli viene passato per tipologia dal data
    props: {
        comics: Array
    }
}
</script>

<style lang="scss" scoped>
.card-container {
    flex-wrap: wrap;
    }

</style>