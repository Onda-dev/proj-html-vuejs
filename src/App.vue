<template>
  <div id="app">
    <HeaderBase/>
    <MainBase/>
    <MissionSection/>
    <ProjectSection/>
  </div>
</template>

<script>
import HeaderBase from './components/blocks/HeaderBase.vue'
import MainBase from './components/blocks/MainBase.vue'
import MissionSection from './components/sections/MissionSection.vue'
import ProjectSection from './components/sections/ProjectsSection.vue'

export default {
  name: 'App',
  components: {
    HeaderBase,
    MainBase,
    MissionSection,
    ProjectSection,
  }
}
</script>

<style lang="scss">
@import 'assets/style/global.scss';

</style>
