<template>
    <section>
        <div class="hero d-flex justify-content-between align-items-center">
            <div class="text-box">
            <p>17 years of experience</p>
            <h1>Focus on your experience</h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Non quas atque possimus, libero eum laborum velit illo provident quisquam vitae eligendi officiis enim hic excepturi doloribus consectetur voluptas dolore veritatis?</p>
            <button type="button" class="grey-button">
                read more
            </button>
        </div>
            <img src="@/assets/img/hero.png" alt="">
        </div>
    </section>
</template>

<script>
export default {
    name: 'HeroSection'
}
</script>

<style lang="scss" scoped>
.hero {
    height: 70vh;
    background-color: rgb(244, 244, 244);
    overflow: hidden;
    padding-left: 7.25rem;
    img {
        height: 120%;
        margin-right: -6.25rem;
    }
}
</style>