<template>
    <div class="footer-media">
        <div class="container">
            <div class="content-social-media-footer row">
                
                <div class="sign-up-button-container">
                    <button>SIGN-UP NOW!</button>
                </div>

                <!-- FIX THE IMGS -->
                <div>
                    <div class="social-media-box">
                        <a href="#">FOLLOW US</a>
                        <div><img src="../assets/footer-facebook.png" alt="Facebook Logo"></div>
                        <div><img src="../assets/footer-twitter.png" alt="Twitter Logo"></div>
                        <div><img src="../assets/footer-youtube.png" alt="Youtube Logo"></div>
                        <div><img src="../assets/footer-pinterest.png" alt="Pinterest Logo"></div>
                        <div><img src="../assets/footer-periscope.png" alt="Periscope Logo"></div>
                    </div>
                </div>

            </div>
        </div>
    </div>
    
</template>

<script>
export default {
    name: "FooterMedia",
}
</script>

<style lang="scss" scoped>
.content-social-media-footer {
    align-items: center;
    justify-content: space-between;
}

.social-media-box {
    display: flex;
    list-style: none;

    a {
        color: #0282f9;
        padding-right: 12px;
    }
} 

.sign-up-button-container {
    button {
        background-color: #303030;
        border: 1px solid #0282f9;
        color: white;
        padding: 12px;
        font-size: 16px;
        cursor: pointer;
    }
}

</style>