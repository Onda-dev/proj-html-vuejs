<template>
    <footer>
        <div class="footer-top">
            <div class="container">
                <div class="row">
                    <div class="col-3">
                        <img src="@/assets/img/logo.png" alt="">
                        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Iusto mollitia tenetur nihil, beatae veritatis sapiente optio cum culpa provident ullam quod ea ex consectetur quasi aliquam eaque accusantium incidunt commodi.</p>
                    </div>
                    <div class="col-3">
                        <a href="#">
                            <h4>quick links</h4>
                            <nav>
                                <ul class="text-center">
                                    <li v-for="(link, index) in quickLinks" :key="index">
                                        <a :href="link.link">{{link.text}}</a>
                                    </li>
                                </ul>
                            </nav>
                        </a>
                    </div>
                    <div class="col-3">
                        <a href="#">
                            <h4>contact</h4>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                            <p>info@yourdomain.com</p>
                            <p>+99 (0) 101 0000 888</p>
                        </a>
                    </div>
                    <div class="col-3">
                        <a href="#">
                            <h4>locations on map</h4>
                            <img src="@/assets/img/map.png" alt="">
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'FooterBase',
    data() {
        return {
            quickLinks: [
                {
                    "text": "Careers",
                    "link": "#",
                },
                {
                    "text": "News",
                    "link": "#",
                },
                {
                    "text": "Terms of Use",
                    "link": "#",
                },
                {
                    "text": "Privacy Projects",
                    "link": "#",
                },
                {
                    "text": "About",
                    "link": "#",
                },
                {
                    "text": "Contact",
                    "link": "#",
                },
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
img {
    width: 100%;
}
</style>