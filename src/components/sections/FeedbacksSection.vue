<template>
    <section class="feedbacks">
        <div class="container">
            <div class="row">
                <div class="col-6 col-under px-0 d-flex flex-column justify-content-center align-items-center">
                    <div class="text-box">
                        <div class="projects-number text-center mb-3">
                            280
                            <div class="subtitle">projects</div>
                        </div>
                        <div class="d-flex">
                            <div class="comments-number text-center mr-4">
                                +3,500
                                <div class="subtitle">users comments</div>
                            </div>
                            <div class="happy-number text-center ml-4">
                                100%
                                <div class="subtitle">happy clients</div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-6 py-5 px-5 col-over">
                    <h3>We <span class="green-text">Love</span> What We Do</h3>
                    <div class="divisor my-4"></div>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Est, doloremque autem quasi possimus sit perspiciatis! Iure nostrum culpa illo rem libero quam, fuga odio, provident ea omnis, neque optio eveniet!</p>
                    <ul class="pl-0">
                        <li>
                            <i class="fa-solid fa-check green-text mr-2"></i>Lorem ipsum, dolor sit amet consectetur adipisicing elit
                        </li>
                        <li>
                            <i class="fa-solid fa-check green-text mr-2"></i>Lorem ipsum, dolor sit amet consectetur
                        </li>
                        <li>
                            <i class="fa-solid fa-check green-text mr-2"></i>Lorem ipsum, dolor sit amet consectetur adipisicing elit
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'FeedbacksSection'
}
</script>

<style lang="scss" scoped>
section {
    background-color: rgb(248, 248, 248);
    padding: 12rem 0;
}
.text-box {
    z-index: 1;
}
.col-under {
    transform: translate(2.3rem, -3rem);
    background-image: url(/src/assets/img/person-with-long-curly-hair-PZ99QM2-2x.jpg);
    background-size: cover;
    border-radius: 0.4rem;
    position: relative;
    overflow: hidden;
}
.col-under::before {
    content: "";
    position: absolute;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    background: rgb(0,214,185);
    background: linear-gradient(45deg, rgba(0,214,185,0.9) 10%, rgba(154,226,0,0.9) 100%);
}
.col-over {
    transform: translate(-2.3rem);
    border-radius: 0.4rem;
    background-color: white;
    box-shadow: 0 0 10px 0 rgba(0, 0, 0, 0.05), 0 0 30px 0 rgba(0, 0, 0, 0.15);
}
</style>