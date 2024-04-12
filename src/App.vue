<script>
  import AppHeader from './components/AppHeader.vue';
  import AppCard from './components/AppCard.vue';
  import AppBannerIcon from './components/AppBannerIcon.vue'
  import AppFooterTop from './components/AppFooterTop.vue'

  export default {
    components: {
      AppHeader,
      AppCard,
      AppBannerIcon,
      AppFooterTop
    }
  }
</script>

<template>
    <AppHeader></AppHeader>
    <main>
      <AppCard></AppCard>
      <AppBannerIcon></AppBannerIcon>
    </main>
    <footer>
      <AppFooterTop></AppFooterTop>
    </footer>
</template>

<style lang="scss">
  @use './style/generic';
</style>
