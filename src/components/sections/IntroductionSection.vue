<template>
    <section class="my-5">
        <div class="container">
            <div class="row justify-content-between">
                <div class="col-4 d-flex flex-column justify-content-center">
                    <h2>We Are Here To Make Your Website Look More Elegant And Stylish</h2>
                    <div class="my-4">
                        <button type="button" class="green-button">
                            view all
                        </button>
                    </div>
                </div>
                <div class="col-7">
                    <div class="row justify-content-end">
                        <div class="col-5">
                            <i class="fa-solid fa-gauge-simple-high"></i>
                            <h4>Speed Optimization</h4>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos quidem consectetur maiores eius.</p>
                        </div>
                        <div class="col-5">
                            <i class="fa-solid fa-cloud"></i>
                            <h4>Speed Optimization</h4>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos quidem consectetur maiores eius.</p>
                        </div>
                        <div class="col-5">
                            <i class="fa-solid fa-tablet-screen-button"></i>
                            <h4>Speed Optimization</h4>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos quidem consectetur maiores eius.</p>
                        </div>
                        <div class="col-5">
                            <i class="fa-solid fa-bullhorn"></i>
                            <h4>Speed Optimization</h4>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos quidem consectetur maiores eius.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'IntroductionSection'
}
</script>

<style lang="scss" scoped>
.col-7 .row {
    gap: 1.25rem;
    .col-5 {
        background-color: rgb(230, 230, 230);
        border-radius: 1.2rem;
        h4 {
            margin: 1.25rem 0;
        }
        i {
            font-size: 1.875rem;
        }
        padding: 1.875rem;
    }
}
</style>