<template>
    <section>
        <div class="container">
            <div class="row justify-content-between align-items-center">
                <div class="col-6">
                    <img class="img-under" src="@/assets/img/busy-architect-PYVKWM4-1024x872.jpg" alt="">
                    <div class="div">
                        <div class="overlay"></div>
                        <img class="img-over" src="@/assets/img/businesswoman-analysing-document-P8WSNMC-1024x820.jpg" alt="">
                    </div>
                </div>
                <div class="col-5">
                    <h3>learn more about our missions</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam quo illo eius repellat, voluptate eos vitae fuga accusamus? Exercitationem illo dolorum vel porro voluptatum, natus esse asperiores veritatis quas nobis!</p>
                    <button type="button" class="green-button">
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
    margin: 8rem 0;
    padding: 10rem 0;
    background-color: rgb(238, 238, 238);
}
img {
    width: 100%;
}
.img-over {
    position: relative;
    border-radius: 0.7rem;
}
.img-under {
    border-radius: 1.25rem;
    position: absolute;
    left: -8rem;
    top: -5rem;
}
</style>