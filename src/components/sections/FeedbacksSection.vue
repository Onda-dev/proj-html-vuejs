<template>
    <section>
        <div class="container">
            <div class="row">
                <div class="col-6 col-under px-0 d-flex flex-column justify-content-center align-items-center">
                    <div class="text-box">
                        <div class="projects-number text-center">
                            280
                            <div class="subtitle">projects</div>
                        </div>
                        <div class="d-flex">
                            <div class="comments-number text-center">
                                +3,500
                                <div class="subtitle">users comments</div>
                            </div>
                            <div class="happy-number text-center">
                                100%
                                <div class="subtitle">happy clients</div>
                            </div>
                        </div>
                    </div>
                    <div class="overlay">

                    </div>
                </div>
                <div class="col-6 py-5 px-5 col-over">
                    <h3>We Love What We Do</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Est, doloremque autem quasi possimus sit perspiciatis! Iure nostrum culpa illo rem libero quam, fuga odio, provident ea omnis, neque optio eveniet!</p>
                    <ul class="pl-0">
                        <li>
                            <i class="fa-solid fa-check"></i> Lorem ipsum, dolor sit amet consectetur adipisicing elit
                        </li>
                        <li>
                            <i class="fa-solid fa-check"></i> Lorem ipsum, dolor sit amet consectetur
                        </li>
                        <li>
                            <i class="fa-solid fa-check"></i> Lorem ipsum, dolor sit amet consectetur adipisicing elit
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
    background-color: rgb(219, 219, 219);
    padding: 10rem 0;
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
.overlay {
  content: "";
  position: absolute;
  top: 0; left: 0;
  width: 100%; height: 100%;
  background-color: rgb(100, 200, 79);
  filter: opacity(70%)
}
.col-over {
    transform: translate(-2.3rem);
    border-radius: 0.4rem;
    background-color: white;
}
</style>