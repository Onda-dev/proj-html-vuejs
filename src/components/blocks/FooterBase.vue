<template>
    <footer>
        <div class="footer-top">
            <div class="container">
                <div class="row">
                    <div class="col-3 logo-box">
                        <img src="@/assets/img/logo.png" alt="">
                        <p class="mt-4">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Iusto mollitia tenetur nihil, beatae veritatis sapiente optio cum culpa provident ullam quod ea ex consectetur quasi aliquam eaque accusantium incidunt commodi.</p>
                    </div>
                    <div class="col-3">
                        <a href="#">
                            <h4>quick links</h4>
                        </a>
                        <nav>
                            <ul class="text-center">
                                <li v-for="(link, index) in quickLinks" :key="index">
                                    <a :href="link.link">{{link.text}}</a>
                                </li>
                            </ul>
                        </nav>
                    </div>
                    <div class="col-3">
                        <a href="#">
                            <h4>contact</h4>
                        </a>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                        <p>info@yourdomain.com</p>
                        <p>+99 (0) 101 0000 888</p>
                    </div>
                    <div class="col-3 map-box">
                        <a href="#">
                            <h4>locations on map</h4>
                        </a>
                        <img src="@/assets/img/map.png" alt="">
                    </div>
                </div>
            </div>
        </div>
        <div class="footer-bottom py-4">
            <div class="container">
                <div class="row justify-content-between">
                    <div class="col-3">
                        © 2020 manuel business theme
                    </div>
                    <div class="col-3 icons-box d-flex justify-content-end">
                        <i class="fa-brands fa-facebook-f"></i>
                        <i class="fa-brands fa-twitter"></i>
                        <i class="fa-brands fa-pinterest-p"></i>
                    </div>
                </div>
            </div>
        </div>
        <div class="customer-service">
            <a href="#"><i class="fa-solid fa-message"></i></a>
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
.footer-top {
    padding: 5rem 0;
}
.logo-box {
    img {
        width: 70%;
    }
}
.map-box {
    img {
        width: 100%;
    }
}
.footer-bottom {
    background: rgb(54,54,54);
    background: linear-gradient(90deg, rgba(54,54,54,1) 20%, rgba(0,0,0,1) 100%);
    .icons-box {
        gap: 1.25rem;
    }
}
.customer-service {
    position: fixed;
    bottom: 1.25rem;
    right: 2rem;
    width: 4rem;
    height: 4rem;
    text-align: center;
    font-size: 1.5rem;
    color: white;
    i {
        border-radius: 50%;
        vertical-align: middle;
        background-color: rgb(122, 162, 255);
        padding: 1rem;
    }

}
</style>