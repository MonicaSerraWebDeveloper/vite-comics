<script>
  import AppHeader from './components/AppHeader.vue';
  import AppCard from './components/AppCard.vue';
  import AppBannerIcon from './components/AppBannerIcon.vue'

  export default {
    components: {
      AppHeader,
      AppCard,
      AppBannerIcon
    }
  }
</script>

<template>
    <AppHeader></AppHeader>
    <main>
      <AppCard></AppCard>
      <AppBannerIcon></AppBannerIcon>
    </main>
</template>

<style lang="scss">
  @use './style/generic';
</style>
