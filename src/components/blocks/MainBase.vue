<template>
    <main>
        <HeroSection/>
        <IntroductionSection/>
        <MissionSection/>
        <ProjectSection/>
        <FeedbacksSection/>
        <ServicesSection/>
    </main>
</template>

<script>
import HeroSection from '../sections/HeroSection.vue'
import IntroductionSection from '../sections/IntroductionSection.vue'
import MissionSection from '../sections/MissionSection.vue'
import ProjectSection from '../sections/ProjectsSection.vue'
import FeedbacksSection from '../sections/FeedbacksSection.vue'
import ServicesSection from '../sections/ServicesSection.vue'

export default {
    components: {
        HeroSection,
        IntroductionSection,
        MissionSection,
        ProjectSection,
        FeedbacksSection,
        ServicesSection,
    },
    name: 'MainBase'
}
</script>


<style lang="scss" scoped>

</style>