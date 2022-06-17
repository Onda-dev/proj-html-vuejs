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
                    <button type="button" class="grey-button grey-button-shadow mt-5">
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
    background: rgb(54,54,54);
    background: linear-gradient(90deg, rgba(54,54,54,1) 20%, rgba(0,0,0,1) 100%);
    border-radius: .625rem;
    box-shadow: 0 10px 30px 0 rgba(0, 0, 0, 0.5), 0 0 30px 0 rgba(0, 0, 0, 0.15);
    button {
        border-top-left-radius: 0;
        border-bottom-left-radius: 0;
        color: rgb(140, 140, 140);
        background-color: rgb(63, 63, 63);
        height: 2.6rem;
    }
}
.second-card {
    background: rgb(0,214,185);
    background: linear-gradient(45deg, rgba(0,214,185,0.8) 10%, rgba(154,226,0,0.8) 100%);
    border-radius: .625rem;
    box-shadow: 0 10px 30px 0 rgba(0, 255, 119, 0.4), 0 0 30px 0 rgba(0, 255, 119, 0.2);
}
input {
    width: 14rem;
    border-top-left-radius: 3.125rem;
    border-bottom-left-radius: 3.125rem;
    height: 2.6rem;
    border: none;
    background-color: rgb(63, 63, 63);
    padding-left: 1.25rem;
}
img {
    width: 50%;
}
</style>