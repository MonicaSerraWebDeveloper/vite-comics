<script>
    export default {
        name: 'AppHeader',
    }
</script>

<template>
    <header>
        <div class="container">
            <div class="row-space-between height">
                <div class="logo-container">
                    <a href="#">
                        <img src="../assets/img/dc-logo.png" alt="logo-dc-comincs">
                    </a>     
                </div>
                <nav>
                    <ul>
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>Tv</li>
                        <li>Games</li>
                        <li>Collectibles</li>
                        <li>Videos</li>
                        <li>Fans</li>
                        <li>News</li>
                        <li>Shop</li>
                    </ul>
                </nav>
            </div>
        </div>
    </header>
</template>

<style scoped lang="scss">

    @use '../style/partials/variables' as *;

    .height {
       height: 120px;
    }

    .logo-container {
        display: flex;
        align-items: center;

        img {
        width: 80px;
    }
    }

    nav {
        display: flex;
        align-items: center;

        ul {
        display: flex;
        flex-direction: row;
        gap: 20px;
        height: 100%;
        
        li {
            text-transform: uppercase;
            cursor: pointer;
            border-bottom: 4px solid #fff;
            display: flex;
            height: 100%;
            align-items: center;
            

            &:hover {
                border-bottom: 4px solid $primary-color;
                color: $primary-color;
            }
        }
    }
    }
    
</style>