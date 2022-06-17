<template>
    <section>
        <div class="hero d-flex justify-content-between align-items-center">
            <div class="text-box">
                <h3 class="green-text">17 years of experience</h3>
                <h1>Focus on your <br><span class="green-text">Business</span></h1>
                <div class="divisor my-4"></div>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Non quas atque possimus, libero eum laborum velit illo provident quisquam vitae eligendi officiis.</p>
                <button type="button" class="grey-button mt-5">
                    read more
                </button>
                <div class="social-row">
                    <ul class="d-flex">
                        <li v-for="(social, index) in socialLinks" :key="index">
                            <a :href="social.link">{{social.socialName}}</a>
                        </li>
                    </ul>
                </div>
            </div>
            <img src="@/assets/img/hero.png" alt="">
        </div>
    </section>
</template>

<script>
export default {
    name: 'HeroSection',
    data(){
        return {
            socialLinks: [
                {
                    "socialName": "Facebook",
                    "link": "#"
                },
                {
                    "socialName": "Instagram",
                    "link": "#"
                },
                {
                    "socialName": "Youtube",
                    "link": "#"
                },
                {
                    "socialName": "Twitter",
                    "link": "#"
                },
            ] 
        }
    }
}
</script>

<style lang="scss" scoped>
.hero {
    height: 60vh;
    background-color: rgb(248, 248, 248);
    overflow: hidden;
    padding-left: 7.25rem;
    img {
        height: 130%;
        margin-right: -6.25rem;
    }
    ul {
        padding-inline-start: 0px;
        gap: 1.875rem;
    }
    .social-row {
        padding-top: 6rem;
    }
}
</style>