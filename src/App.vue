<template>
  <div id="app">
    <HeaderBase/>
    <MainBase/>

  </div>
</template>

<script>
import HeaderBase from './components/blocks/HeaderBase.vue'
import MainBase from './components/blocks/MainBase.vue'

export default {
  name: 'App',
  components: {
    HeaderBase,
    MainBase,
  }
}
</script>

<style lang="scss">
@import 'assets/style/global.scss';

</style>
