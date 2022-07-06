<template>
  <div id="app">
    <PageHeader />
    <main>
      <ContentSection />
      <CtaSection />
    </main>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import PageHeader from './components/PageHeader.vue'
import ContentSection from './components/ContentSection.vue'
import CtaSection from './components/CtaSection.vue'

export default {
  name: 'App',
  components: {
    PageHeader,
    ContentSection,
    CtaSection
  }
}
</script>

<style lang="scss">
@import './style/common';
@import './style/variables';
</style>
