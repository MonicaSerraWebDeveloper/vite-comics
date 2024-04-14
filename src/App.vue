<script>
  import AppHeader from './components/AppHeader.vue';
  import AppCard from './components/AppCard.vue';
  import AppBannerIcon from './components/AppBannerIcon.vue'
  import AppFooterTop from './components/AppFooterTop.vue'
  import AppFooterBottom from './components/AppFooterBottom.vue'
  import AppBannerComic from './components/AppBannerComic.vue'

  export default {
    components: {
      AppHeader,
      AppCard,
      AppBannerIcon,
      AppFooterTop,
      AppFooterBottom,
      AppBannerComic
    }
  }
</script>

<template>
    <AppHeader></AppHeader>
    <main>
      <AppBannerComic></AppBannerComic>
      <AppCard></AppCard>
      <AppBannerIcon></AppBannerIcon>
    </main>
    <footer>
      <AppFooterTop></AppFooterTop>
      <AppFooterBottom></AppFooterBottom>
    </footer>
</template>

<style lang="scss">
  @use './style/generic';
</style>
