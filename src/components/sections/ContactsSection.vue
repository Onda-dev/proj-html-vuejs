<template>
    <section class="contacts">
        <div class="container text-center">
            <div class="row justify-content-around">
                <div class="col-5 first-card py-5">
                    <h4>Are You Ready?</h4>
                    <h2>Start a New Project</h2>
                    <form class="d-flex justify-content-center mt-5">
                        <input type="text" placeholder="Enter Your Email Address">
                        <button type="button">submit</button>
                    </form>
                </div>
                <div class="col-5 second-card py-5">
                    <h4>What Are You Waiting For?</h4>
                    <h2>Let's Talk About Work</h2>
                    <button type="button" class="grey-button mt-5">
                        start now
                    </button>
                </div>
            </div>
            <div class="row align-items-center mt-5">
                <div class="col-2">
                    <img src="@/assets/img/client-1.png" alt="">
                </div>
                <div class="col-2">
                    <img src="@/assets/img/client-2.png" alt="">
                </div>
                <div class="col-2">
                    <img src="@/assets/img/client-3.png" alt="">
                </div>
                <div class="col-2">
                    <img src="@/assets/img/client-4.png" alt="">
                </div>
                <div class="col-2">
                    <img src="@/assets/img/client-5.png" alt="">
                </div>
                <div class="col-2">
                    <img src="@/assets/img/client-6.png" alt="">
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'ContactSection'
}
</script>

<style lang="scss" scoped>
section {
    margin: 10rem 0;
}
.first-card {
    background-color: rgb(51, 51, 51);
    border-radius: .625rem;
    button {
        border-top-left-radius: 0;
        border-bottom-left-radius: 0;
        color: rgb(140, 140, 140);
        background-color: rgb(64, 64, 64);
        height: 2.6rem;
    }
}
.second-card {
    background-color: lawngreen;
    border-radius: .625rem;
}
input {
    width: 14rem;
    border-top-left-radius: 3.125rem;
    border-bottom-left-radius: 3.125rem;
    height: 2.6rem;
    border: none;
    background-color: rgb(64, 64, 64);
    padding-left: 1.25rem;
}
img {
    width: 50%;
}
</style>