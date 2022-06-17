<template>
    <section class="introduction">
        <div class="container">
            <div class="row justify-content-between">
                <div class="col-4 d-flex flex-column justify-content-center">
                    <h2>We Are Here To Make Your <span class="green-text">Website</span> Look More <span class="green-text">Elegant</span> And Stylish!</h2>
                    <div class="divisor my-3"></div>
                    <div class="my-4">
                        <button type="button" class="green-button green-button-shadown">
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
        background-color: white;
        border-radius: 1.2rem;
        box-shadow: 0 0 10px 0 rgba(0, 0, 0, 0.05), 0 0 30px 0 rgba(0, 0, 0, 0.15);
        h4 {
            margin: 1.25rem 0;
        }
        i {
            font-size: 1.875rem;
        }
        padding: 1.875rem;
    }
    // .col-5::before {
    //     content: "";
    //     position: absolute;
    //     left: 0;
    //     top: 0;
    //     width: 100%;
    //     height: 100%;
    //     background: rgb(0,214,185);
    //     background: linear-gradient(45deg, rgba(0,214,185,0.9) 10%, rgba(154,226,0,0.9) 100%);
    // }
}
</style>