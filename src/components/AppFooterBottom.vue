<script>
export default {
    name: 'AppFooterBottom'
}
</script>

<template>
    <div class="container-bg">
        <div class="container">
            <div class="row-space-between align-items-center padding-top-bottom">
                <button>
                    Sign-up Now!
                </button>
                <div class="container-social">
                    <span>Follow Us</span>
                    <img src="../assets/img/footer-facebook.png" alt="">
                    <img src="../assets/img/footer-twitter.png" alt="">
                    <img src="../assets/img/footer-youtube.png" alt="">
                    <img src="../assets/img/footer-pinterest.png" alt="">
                    <img src="../assets/img/footer-periscope.png" alt="">
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
    @use '../style/partials/variables' as *;

    .container-bg {
        background-color: $tertiary-color;
        position: relative;

        .align-items-center {
            align-items: center;
        }

        .padding-top-bottom {
            padding: 30px 0;
        }

        button {
            text-transform: uppercase;
            color: $text-color-primary;
            padding: 10px;
            background-color: transparent;
            border: 2px solid $primary-color;
        }

        .container-social {
            display: flex;
            align-items: center;
            gap: 15px;

            span {
                color: $primary-color;
                text-transform: uppercase;
                font-weight: 700;
            }
        }
    }
</style>