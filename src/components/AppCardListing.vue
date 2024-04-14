<script>

export default {
    name: 'AppCardListing',
    props: {
        image: String,
        title: String
    }
        
    
}

</script>

<template>

    <div class="comic-card">
        <img :src="image" alt="">
        <h4>{{ title }}</h4>
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
            width: 180px;
            height: 180px;
            object-fit: cover;
            object-position:top
        }

        h4 {
            text-transform: uppercase;
        }
    }

</style>