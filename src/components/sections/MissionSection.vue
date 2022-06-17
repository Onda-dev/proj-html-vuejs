<template>
    <section class="mission">
        <div class="container">
            <div class="row justify-content-between align-items-center">
                <div class="col-6">
                    <div class="img-under"></div>
                    <div class="div">
                        <img class="img-over" src="@/assets/img/businesswoman-analysing-document-P8WSNMC-1024x820.jpg" alt="">
                    </div>
                </div>
                <div class="col-5">
                    <h3>learn more about our <span class="green-text">missions</span></h3>
                    <div class="divisor my-3"></div>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam quo illo eius repellat, voluptate eos vitae fuga accusamus? Exercitationem illo dolorum vel porro voluptatum, natus esse asperiores veritatis quas nobis!</p>
                    <button type="button" class="green-button green-button-shadown">
                        read more
                    </button>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'MissionSection'
}
</script>

<style lang="scss" scoped>
section {
    margin-top: 10rem;
    padding: 12rem 0;
    background-color: rgb(248, 248, 248);
}
img {
    width: 100%;
}
.img-over {
    position: relative;
    border-radius: 0.7rem;
}
.img-under {
    min-width: 34rem;
    min-height: 30rem;
    background-image: url(/src/assets/img/busy-architect-PYVKWM4-1024x872.jpg);
    background-size: cover;
    overflow: hidden;
    border-radius: 1.25rem;
    position: absolute;
    left: -8rem;
    top: -5rem;
}
.img-under::before {
    content: "";
    position: absolute;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    background: rgb(154,226,0);
    background: linear-gradient(45deg, rgba(154,226,0,0.8) 10%, rgba(0,214,185,0.8) 100%);
}
</style>