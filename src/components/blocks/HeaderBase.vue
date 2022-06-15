<template>
    <header>
        <div class="container">
            <div class="info-bar row justify-content-between">
                <div class="col-3 d-flex p-2 align-items-center">
                    <i class="fa-solid fa-phone"></i>
                    <div class="contact-numbers">
                        <span>(001)88451234</span>
                        <span>88451238</span>
                    </div>
                </div>
                <div class="col-3 d-flex p-2 justify-content-end align-items-center">
                    <i class="fa-brands fa-facebook-f"></i>
                    <i class="fa-brands fa-twitter"></i>
                    <i class="fa-brands fa-pinterest-p"></i>
                </div>
            </div>
            <div class="nav-bar">
                <div class="row">
                    <div class="col-3">

                    </div>
                    <div class="col-6">

                    </div>
                    <div class="col-3">

                    </div>
                </div>
            </div>
        </div>
    </header>
</template>

<script>
export default {
    name: 'HeaderBase'
}
</script>

<style lang="scss" scoped>
header {
    background-color: #232323;
}
.col-3 {
    gap: .625rem;
}
</style>