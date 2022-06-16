<template>
  <div id="app">
    <HeaderBase/>
    <MainBase/>
    <MissionSection/>
    <ProjectSection/>
    <FeedbacksSection/>
  </div>
</template>

<script>
import HeaderBase from './components/blocks/HeaderBase.vue'
import MainBase from './components/blocks/MainBase.vue'
import MissionSection from './components/sections/MissionSection.vue'
import ProjectSection from './components/sections/ProjectsSection.vue'
import FeedbacksSection from './components/sections/FeedbacksSection.vue'

export default {
  name: 'App',
  components: {
    HeaderBase,
    MainBase,
    MissionSection,
    ProjectSection,
    FeedbacksSection,
  }
}
</script>

<style lang="scss">
@import 'assets/style/global.scss';

</style>
