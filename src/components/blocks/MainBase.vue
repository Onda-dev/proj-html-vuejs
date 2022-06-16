<template>
    <main>
        <HeroSection/>
        <IntroductionSection/>
    </main>
</template>

<script>
import HeroSection from '../sections/HeroSection.vue'
import IntroductionSection from '../sections/IntroductionSection.vue'

export default {
    components: {
      HeroSection,
      IntroductionSection,
    },
    name: 'MainBase'
}
</script>


<style lang="scss" scoped>

</style>