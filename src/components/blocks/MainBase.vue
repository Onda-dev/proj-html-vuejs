<template>
    <main>
        <HeroSection/>
        <IntroductionSection/>
        <MissionSection/>
        <ProjectSection/>
        <FeedbacksSection/>
        <ServicesSection/>
        <ReviewSection/>
        <BlogSection/>
    </main>
</template>

<script>
import HeroSection from '../sections/HeroSection.vue'
import IntroductionSection from '../sections/IntroductionSection.vue'
import MissionSection from '../sections/MissionSection.vue'
import ProjectSection from '../sections/ProjectsSection.vue'
import FeedbacksSection from '../sections/FeedbacksSection.vue'
import ServicesSection from '../sections/ServicesSection.vue'
import ReviewSection from '../sections/ReviewSection.vue'
import BlogSection from '../sections/BlogSection.vue'

export default {
    components: {
        HeroSection,
        IntroductionSection,
        MissionSection,
        ProjectSection,
        FeedbacksSection,
        ServicesSection,
        ReviewSection,
        BlogSection,
    },
    name: 'MainBase'
}
</script>


<style lang="scss" scoped>

</style>