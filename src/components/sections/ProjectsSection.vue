<template>
    <section>
        <div class="container">
            <div class="row">
                <div class="col-6">
                    <h2>Our recent web design and some examples of past projects</h2>
                </div>
                <div class="col-6 my-5">
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Blanditiis repudiandae, quisquam rem rerum ratione nesciunt animi, ea iste accusamus dolorem aliquam, consequuntur consectetur perspiciatis eaque vitae magnam dicta facilis dolor.</p>
                </div>
            </div>
            <div class="row gallery">
                <img src="@/assets/img/ina-soulis-227104-unsplash-1024x1024.jpg" alt="">
                <img src="@/assets/img/sunisa-misa-531163-unsplash-1024x1024.jpg" alt="">
                <img src="@/assets/img/355H-1024x1024.jpg" alt="">
                <img src="@/assets/img/photo-1448932252197-d19750584e56-1024x1024.jpg" alt="">
                <img src="@/assets/img/business-competition-PB366D8-1024x1024.jpg" alt="">
                <img src="@/assets/img/cozy-sofa-in-living-room-PQR5AB9-1024x1024.jpg" alt="">
                <img src="@/assets/img/aa9a4539-PQGJ7HU-1024x1024.jpg" alt="">
                <img src="@/assets/img/cody-davis-253928-unsplash-1024x1024.jpg" alt="">                                              
            </div>
        </div>

    </section>
</template>

<script>
export default {
    name: 'ProjectSection'
}
</script>

<style lang="scss" scoped>
section {
    margin: 8rem 0;
}
.gallery{
    gap: .3rem;
}
img {
    width: 24%;
}
</style>