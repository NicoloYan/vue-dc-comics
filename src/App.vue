<template>
  <div id="app">
    <PageHeader />
    <main>
      <PageJumbotron />
      <ContentSection />
      <CtaSection />
    </main>

    <footer>
      <FooterTop />
      <FooterBottom />
    </footer>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import PageHeader from './components/PageHeader.vue'
import PageJumbotron from './components/PageJumbotron.vue'
import ContentSection from './components/ContentSection.vue'
import CtaSection from './components/CtaSection.vue'
import FooterTop from './components/FooterTop.vue'
import FooterBottom from './components/FooterBottom.vue'

export default {
  name: 'App',
  components: {
    PageHeader,
    PageJumbotron,
    ContentSection,
    CtaSection,
    FooterTop,
    FooterBottom
  }
}
</script>

<style lang="scss">
@import './style/common';
@import './style/variables';
</style>
