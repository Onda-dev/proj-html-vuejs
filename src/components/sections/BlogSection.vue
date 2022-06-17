<template>
    <section class="blog">
        <div class="container text-center">
            <h2 class="text-center">Latest News & Our <span class="green-text">Blog</span></h2>
            <div class="divisor mx-auto my-4"></div>
            <div class="row">
                <div class="col-4">
                    <div class="img-box first-img-box"></div>
                    <div class="info-box">
                        <div class="date">May 24, 2018 - by Alex</div>
                        <div class="title"><i class="fa-solid fa-circle mr-2"></i>Marketing Ideas</div>
                    </div>
                </div>
                <div class="col-4">
                    <div class="img-box second-img-box"></div>
                    <div class="info-box">
                        <div class="date">May 24, 2018 - by Alex</div>
                        <div class="title"><i class="fa-solid fa-circle mr-2"></i>Marketing Ideas</div>
                    </div>               
                </div>
                <div class="col-4">
                    <div class="img-box third-img-box"></div>
                    <div class="info-box">
                        <div class="date">May 24, 2018 - by Alex</div>
                        <div class="title"><i class="fa-solid fa-circle mr-2"></i>Marketing Ideas</div>
                    </div>                    
                </div>
            </div>
            <button type="button" class="grey-button grey-button-shadow mt-5">
                view all post
            </button>
        </div>
    </section>
</template>

<script>
export default {
    name: 'BlogSection'
}
</script>

<style lang="scss" scoped>
section {
    padding: 10rem 0;
    background-color: rgb(248, 248, 248);
}
.first-img-box {
    background-image: url(/src/assets/img/serious-businesswoman-with-documents-talking-on-P9Q6LX6-1024.jpg);
}
.second-img-box {
    background-image: url(/src/assets/img/Businessman-at-the-desk-in-his-office-resting--1024x768.jpg);
}
.third-img-box {
    background-image: url(/src/assets/img/simple-home-office-with-tree-PBXRXYB-large-1024x768.jpg);
}
.img-box {
    height: 16rem;
    background-size: cover;
    border-radius: .625rem;
    box-shadow: 0 0 10px 0 rgba(0, 0, 0, 0.05), 0 0 30px 0 rgba(0, 0, 0, 0.15);
}
.info-box {
    transform: translate(0, -50%);
    margin: auto;
    padding: 1.875rem;
    border-radius: .625rem;
    text-align: left;
    width: 85%;
    background-color: rgb(255, 255, 255);
    box-shadow: 0 0 10px 0 rgba(0, 0, 0, 0.05), 0 0 30px 0 rgba(0, 0, 0, 0.15);
    i {
        font-size: .4rem;
        color: lime;
        display: inline-block;
        transform: translate(0, -50%);
    }
}
</style>