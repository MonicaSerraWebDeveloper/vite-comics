<script>

export default {
    name: 'AppCardListing',

    data() {
        return {
            comics: [
                {
                    "thumb": "https://www.coverbrowser.com/image/action-comics/1-1.jpg",
                    "price": "$19.99",
                    "series": "Action Comics",
                    "type": "comic book"
                },
                {
                    "thumb": "https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/M/1/M1BLLA015ISBN_0.jpg",
                    "price": "$3.99",
                    "series": "American Vampire 1976",
                    "type": "comic book"
                },
                ]
            }         
        }
}

</script>

<template>

    <div class="comic-card">
        <img src="https://www.coverbrowser.com/image/action-comics/1-1.jpg" alt="">
        <h4>Action Comics</h4>
    </div>
    <div class="comic-card">
        <img src="https://www.coverbrowser.com/image/action-comics/1-1.jpg" alt="">
        <h4>Action Comics</h4>
    </div>
    <div class="comic-card">
        <img src="https://www.coverbrowser.com/image/action-comics/1-1.jpg" alt="">
        <h4>Action Comics</h4>
    </div>
    <div class="comic-card">
        <img src="https://www.coverbrowser.com/image/action-comics/1-1.jpg" alt="">
        <h4>Action Comics</h4>
    </div>
    <div class="comic-card">
        <img src="https://www.coverbrowser.com/image/action-comics/1-1.jpg" alt="">
        <h4>Action Comics</h4>
    </div>
    <div class="comic-card">
        <img src="https://www.coverbrowser.com/image/action-comics/1-1.jpg" alt="">
        <h4>Action Comics</h4>
    </div>
    <div class="comic-card">
        <img src="https://www.coverbrowser.com/image/action-comics/1-1.jpg" alt="">
        <h4>Action Comics</h4>
    </div>

</template>

<style scoped lang="scss">

    .comic-card {

        width: calc(100% / 6);
        padding: 20px;
        display: flex;
        flex-direction: column;
        gap: 10px;
        cursor: pointer;

        img {
            max-width: 100%;
            object-fit: cover;
        }

        h4 {
            text-transform: uppercase;
        }
    }

</style>