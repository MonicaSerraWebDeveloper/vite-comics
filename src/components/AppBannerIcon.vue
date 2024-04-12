<script>

    export default {
        name: 'AppBannerIcon'
    }

</script>

<template>

    <div class="container-bg">
        <div class="container">
            <div class="row">
                <div class="container-logo">
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                    <h3>Digital Comics</h3>
                </div>
                <div class="container-logo">
                    <img src="../assets/img/buy-comics-merchandise.png" alt="">
                    <h3>DC merchandise</h3>
                </div>
                <div class="container-logo">
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                    <h3>Subscription</h3>
                </div>
                <div class="container-logo">
                    <img class="logo-locator" src="../assets/img/buy-comics-shop-locator.png" alt="">
                    <h3>Comic Shop Locator</h3>
                </div>
                <div class="container-logo">
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                    <h3>DC power visa</h3>
                </div>
            </div>
        </div>
    </div>
    
</template>

<style scoped lang="scss">

    @use '../style/partials/variables' as *;

    .container-bg {
        background-color: $primary-color;

        .container-logo {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            gap: 15px;
            padding: 50px 20px;
        }

        img {
            width: 50px;
        }

        h3 {
            text-transform: uppercase;
            font-weight: 300;
            color: $text-color-primary;
        }

        .logo-locator {
            width: 35px;
        }
    }

</style>