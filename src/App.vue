<template>
  <div id="app">
    <HeaderBase/>
    <MainBase/>
    <FooterBase/>
  </div>
</template>

<script>
import HeaderBase from './components/blocks/HeaderBase.vue'
import MainBase from './components/blocks/MainBase.vue'
import FooterBase from './components/blocks/FooterBase.vue'

export default {
  name: 'App',
  components: {
    HeaderBase,
    MainBase,
    FooterBase
  }
}
</script>

<style lang="scss">
@import 'assets/style/global.scss';

</style>
