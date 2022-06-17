<template>
    <section class="introduction">
        <div class="container">
            <div class="row justify-content-between">
                <div class="col-4 d-flex flex-column justify-content-center">
                    <h2>We Are Here To Make Your <span class="green-text">Website</span> Look More <span class="green-text">Elegant</span> And Stylish!</h2>
                    <div class="divisor my-3"></div>
                    <div class="my-4">
                        <button type="button" class="green-button">
                            view all
                        </button>
                    </div>
                </div>
                <div class="col-7">
                    <div class="row justify-content-end">
                        <div class="col-5">
                            <i class="fa-solid fa-gauge-simple-high green-text"></i>
                            <h4>Speed Optimization</h4>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                        </div>
                        <div class="col-5">
                            <i class="fa-solid fa-cloud green-text"></i>
                            <h4>Speed Optimization</h4>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                        </div>
                        <div class="col-5">
                            <i class="fa-solid fa-tablet-screen-button green-text"></i>
                            <h4>Speed Optimization</h4>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                        </div>
                        <div class="col-5">
                            <i class="fa-solid fa-bullhorn green-text"></i>
                            <h4>Speed Optimization</h4>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
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
section {
    margin-top: 10rem;
}
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