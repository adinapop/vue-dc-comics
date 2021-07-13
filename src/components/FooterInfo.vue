<template>
    <div class="footer-info">

        <div class="container">

            <div class="content-footer-info row">

                <div class="info-lists">

                    <ul class="info-box">
                        <li class="title">DC COMICS</li>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Comics</a></li>
                        <li><a href="#">Movies</a></li>
                        <li><a href="#">TV</a></li>
                        <li><a href="#">Games</a></li>
                        <li><a href="#">Videos</a></li>
                        <li><a href="#">News</a></li>
                        <li class="title">SHOP</li>
                        <li><a href="#">Shop DC</a></li>
                        <li><a href="#">Shop DC Collectibles</a></li>
                    </ul>

                    <ul class="info-box">
                        <li class="title">DC</li>
                        <li><a href="#">Terms Of Use</a></li>
                        <li><a href="#">Privacy Policy (New)</a></li>
                        <li><a href="#">Ad Choice</a></li>
                        <li><a href="#">Advertising</a></li>
                        <li><a href="#">Jobs</a></li>
                        <li><a href="#">Subscriptions</a></li>
                        <li><a href="#">Talent Workshops</a></li>
                        <li><a href="#">CPSC Certificates</a></li>
                        <li><a href="#">Ratings</a></li>
                        <li><a href="#">Shop Help</a></li>
                        <li><a href="#">Contact Us</a></li>
                    </ul>

                    <ul class="info-box">
                        <li class="title">SITES</li>
                        <li><a href="#">DC</a></li>
                        <li><a href="#">MAD Magazine</a></li>
                        <li><a href="#">DC Kids</a></li>
                        <li><a href="#">DC Universe</a></li>
                        <li><a href="#">DC Power Visa</a></li>
                    </ul>

                </div>

                <!-- FIX THE BIG LOGO -->
                <div class="container-big-logo">
                    <img src="../assets/dc-logo-bg.png" alt="Big Logo DC Comics">
                </div>

            </div>

        </div>

    </div>
    
</template>

<script>
export default {
    name: "FooterInfo"
}
</script>

<style lang="scss" scoped>
.footer-info {
    background-image: url("../assets/footer-bg.jpg");
    height: 350px;
}

.content-footer-info {justify-content: space-between;}

.info-lists {
    display: flex;
    padding-top: 24px;
}

.title {
    color: white;
    padding: 12px 0;
    font-size: 18px;
}

.info-box {
    padding-right: 24px;

    li {
        padding: 2px 0;
        a {
            color: gray;
            font-size: 14px;

            &:hover {text-decoration: underline;}
        }
    }
}

.container-big-logo {
    width: 300px;

    img {width: 100%;}
}


</style>