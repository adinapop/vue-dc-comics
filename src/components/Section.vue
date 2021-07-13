<template>
    <section>
        <div class="container">
            <div class="content-section row">
                <div class="buy-info-container">
                    <div class="icon-box">
                        <img src="../assets/buy-comics-digital-comics.png" alt="Digital Comics Icon">
                    </div>
                    <span>DIGITAL COMICS</span>
                </div>
                
                
                <div class="buy-info-container">
                    <div class="icon-box">
                        <img src="../assets/buy-comics-merchandise.png" alt="Digital Comics Icon">
                    </div>
                    <span>DC MERCHANDISE</span>
                </div>
                
                <div class="buy-info-container">
                    <div class="icon-box">
                        <img src="../assets/buy-comics-subscriptions.png" alt="Digital Comics Icon">
                    </div>
                    <span>SUBSCRIPTIONS</span>
                </div>
                

                <div class="buy-info-container">
                    <div class="icon-box">
                        <img src="../assets/buy-comics-shop-locator.png" alt="Digital Comics Icon">
                    </div>
                    <span>COMIC SHOP LOCATOR</span>
                </div>
                
                <!-- TO FIX: ADD THE RIGHT IMG -->
                <div class="buy-info-container">
                    <div class="icon-box smaller">
                        <img src="../assets/buy-comics-shop-locator.png" alt="Digital Comics Icon">
                    </div>
                    <span>DC POWER VISA</span>
                </div>
            </div>
        </div>
    </section>
    
</template>

<script>
export default {
    name: "Section"
}
</script>

<style lang="scss" scoped>

.buy-info-container {
    display: flex;
    align-items: center;
    margin: 0 24px;

    .icon-box {
        width: 50px;
        padding-right: 12px;

        img {width: 100%;}
    }
}

</style>