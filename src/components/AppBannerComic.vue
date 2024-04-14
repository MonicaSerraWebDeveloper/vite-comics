<script>

    export default {
        name: 'AppBannerComic'
    }

</script>

<template>
    <div class="bg-container">
        <div class="container">
            <div class="row">
                <button class="primary-button">Current Series</button>
            </div>
        </div>
    </div>

</template>

<style scoped lang="scss">
    @use '../style/generic';
    @use '../style/partials/variables' as *;

    .bg-container {
        height: 300px;
        background-size: cover;
        background-image: url('../assets/img/jumbotron.jpg');
        position: relative;

        .primary-button {
            position: absolute;
            bottom: -6%;
        }
        
    }
</style>