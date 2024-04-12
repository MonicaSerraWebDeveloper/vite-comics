<script>
    export default {
        name: 'AppFooterTop'
    }
</script>

<template>

    <div class="container-bg">
        <div class="container">
            <div class="row">
                <div class="container-menu-footer">
                    <div class="col-25">
                        <h4>DC Comics</h4>
                            <nav>
                                <ul>
                                    <li>Characters</li>
                                    <li>Comics</li>
                                    <li>Movies</li>
                                    <li>TV</li>
                                    <li>Games</li>
                                    <li>Videos</li>
                                    <li>News</li>
                                </ul>
                            </nav>
                            <h4>Shop</h4>
                            <nav>
                                <ul>
                                    <li>Shop DC</li>
                                    <li>Shop DC Collectibles</li>
                                </ul>
                            </nav>
                    </div>
                    <div class="col-25">
                        <h4>DC</h4>
                        <nav>
                            <ul>
                                <li>Term Of Use</li>
                                <li>Privacy policy (New)</li>
                                <li>Ad Choices</li>
                                <li>Advertising</li>
                                <li>Jobs</li>
                                <li>Subscriptions</li>
                                <li>Talent Workshops</li>
                                <li>CPSC Certificates</li>
                                <li>Ratings</li>
                                <li>Shop Help</li>
                                <li>Contact Us</li>
                            </ul>
                        </nav>
                    </div>
                    <div class="col-25">
                        <h4>Sites</h4>
                        <nav>
                            <ul>
                                <li>DC</li>
                                <li>MAD Magazine</li>
                                <li>DC Kids</li>
                                <li>DC Universe</li>
                                <li>DC Power Visa</li>
                            </ul>
                        </nav>
                    </div>
                </div>
                <div class="container-logo-footer">
                    <img src="../assets/img/dc-logo-bg.png" alt="">
                </div>
            </div>
        </div>
    </div>

</template>

<style scoped lang="scss">
    @use '../style/partials/variables' as *;

    .container-bg {
        background-image: url('../assets/img/footer-bg.jpg');
        background-repeat: no-repeat;
        background-size: cover;
        padding: 40px 0;

        .container-menu-footer {
            width: 50%;
            display: flex;
        }

        .col-25 {
            width: calc(100% / 4);
        }

        nav {
            padding-bottom: 20px;
        }

        h4 {
            color: $text-color-primary;
            text-transform: uppercase;
            padding-bottom: 20px;
        }

        li {
            color: grey;
            cursor: pointer;

            &:hover {
                color: lightgray;
            }
        }

        .container-logo-footer {
            position: relative;
            width: 50%;

            img {
                width: 500px;
                position: absolute;
                top: -40%;
                right: 0;
            }
        }
    }

</style>