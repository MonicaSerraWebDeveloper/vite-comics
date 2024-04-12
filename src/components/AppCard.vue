<script>

    export default {
        name: 'AppCard'
    }

</script>

<template>
    <div class="container-bg">
        <div class="container">
            <div class="row">
                <h2>Content Goes Here</h2>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">

    @use '../style/partials/variables' as *;

    .container-bg {
        height: 200px;
        display: flex;
        align-items: center;
        color: $text-color-primary;
        background-color: $secondary-color;


    }
</style>