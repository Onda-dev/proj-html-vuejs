<template>
    <header>
        <div class="info-bar">
            <div class="container">
                <div class="row justify-content-between">
                    <div class="col-2 d-flex p-2 align-items-center">
                        <i class="fa-solid fa-phone"></i>
                        <div class="contact-numbers d-flex">
                            <div>(001)88451234</div>
                            <div>88451238</div>
                        </div>
                    </div>
                    <div class="col-2 d-flex p-2 justify-content-end align-items-center">
                        <i class="fa-brands fa-facebook-f"></i>
                        <i class="fa-brands fa-twitter"></i>
                        <i class="fa-brands fa-pinterest-p"></i>
                    </div>
                </div>
            </div>
        </div>
        <div class="nav-bar">
            <div class="container">
                <div class="row py-4 align-items-center">
                    <div class="col-2">
                        <div class="logo">
                            <img src="@/assets/img/logo.png" alt="">
                        </div>
                    </div>
                    <div class="col-8 d-flex justify-content-center">
                        <nav class="d-flex align-items-center">
                            <ul class="d-flex">
                                <li v-for="(navLink, index) in navLinks" :key="index">
                                    <a :href="navLink.link">{{navLink.text}}</a>
                                </li>
                            </ul>
                        </nav>
                    </div>
                    <div class="col-2 d-flex justify-content-end">
                        <button type="button" class="green-button">
                            purchase
                        </button>
                    </div>
                </div>
            </div>
        </div>

    </header>
</template>

<script>
export default {
    name: 'HeaderBase',
    data(){
        return {
            navLinks: [
                {
                    "text": "home",
                    "link": "#"
                },
                {
                    "text": "about",
                    "link": "#"
                },
                {
                    "text": "services",
                    "link": "#"
                },
                {
                    "text": "showcase",
                    "link": "#"
                },
                {
                    "text": "blog",
                    "link": "#"
                },
                {
                    "text": "contact",
                    "link": "#"
                },
                
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
.col-2 {
    gap: .625rem;
}
img {
    width: 100%;
}
.info-bar {
    background-color: #232323;
}
.contact-numbers {
    gap: .625rem;
}
ul {
    gap: 1.875rem;
}
</style>