<template>
    <nav>
        <div class="container">
            <div class="content-nav row">
                <div class="logo-container">
                    <img src="../assets/dc-logo.png" alt="Logo DC">
                </div>

                <div>
                    <ul class="menu-info-nav">
                        <li>CHARACTERS</li>
                        <li>COMICS</li>
                        <li>MOVIES</li>
                        <li>TV</li>
                        <li>GAMES</li>
                        <li>VIDEOS</li>
                        <li>NEWS</li>
                        <li>SHOP</li>
                    </ul>
                </div>
            </div>
        </div>
    </nav>
    
</template>

<script>
export default {
    name: "Nav"
}
</script>

<style lang="scss" scoped>
.content-nav {
    justify-content: space-between;
    align-items: center;
    padding: 12px 0;
}

.logo-container {
    width: 80px;

    img {width: 100%;}
}

.menu-info-nav {
    display: flex;

    li {
        padding: 0 12px;
        font-weight: bold;
        font-size: 16px;
    }
}

</style>