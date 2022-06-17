<template>
    <section class="review">
        <div class="overlay d-flex flex-row align-items-center">
            <div class="container d-flex flex-column align-items-center">
                <div class="text-box text-center">
                <i class="fa-solid fa-quote-left green-text"></i>
                <p class="my-5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum aut assumenda ex delectus non totam voluptatum deleniti, explicabo molestias sapiente consectetur, vel odit id molestiae cumque accusantium minima dolores debitis!</p>
                <div class="img-box mb-3"></div>
                <div class="client-name green-text">Lissa Durbin</div>
                <div class="subtitle">client</div>
            </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'ReviewSection'
}
</script>

<style lang="scss" scoped>
section {
    height: 70vh;
    background-image: url(/src/assets/img/four-businesspeople-in-a-boardroom-with-paperwork-PC4V8H4.jpg);
    background-size: cover;
    background-position: center;
    position: relative;
}
.img-box {
    background-image: url(/src/assets/img/businesswoman-analysing-document-P8WSNMC-1024x820.jpg);
    background-size: cover;
    background-position: center;
    width: 6.25rem;
    height: 6.25rem;
    border-radius: 50%;
    border: .1875rem solid white;
    margin: auto;
}
.text-box {
    max-width: 70%;
    color: white;
    i {
        font-size: 2rem;
    }
}
.overlay {
    position: absolute;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.5);
}
</style>