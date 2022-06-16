<template>
    <section>
        <div class="container text-center">
            <h2 class="text-center">Latest News and Our Blog</h2>
            <div class="row">
                <div class="col-4">
                    <div class="img-box first-img-box"></div>
                </div>
                <div class="col-4">
                    <div class="img-box second-img-box"></div>                    
                </div>
                <div class="col-4">
                    <div class="img-box third-img-box"></div>                    
                </div>
            </div>
            <button type="button" class="grey-button mt-5">
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
    margin: 6.25rem 0;
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
}
</style>