<template>
    <section class="services">
        <div class="container">
            <div class="row">
                <div class="col-3 d-flex flex-column justify-content-center">
                    <h3>With <span class="green-text">Live Chat 24/7</span> Support</h3>
                    <div class="divisor my-4"></div>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias vel, aliquam ipsam ea necessitatibus facilis cupiditate atque.</p>
                </div>
                <div class="col-9 card-box d-flex justify-content-end">
                    <div class="cards" v-for="(service, index) in services" :key="index">
                        <ServiceCard :title="service.title" :subtitle="service.subtitle" :price="service.price" :service="service.service"/>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
<script>
import ServiceCard from '../commons/ServiceCard.vue'
export default {
  components: { ServiceCard },
    name: 'ServicesSection',
    data(){
        return {
            services: [
                {
                    "title": "designing",
                    "subtitle": "All Design",
                    "price": 13,
                    "service": "Design"
                },
                {
                    "title": "development",
                    "subtitle": "WordPress Project",
                    "price": 15,
                    "service": "Project"
                },
                {
                    "title": "seo",
                    "subtitle": "Web Products",
                    "price": 10,
                    "service": "Product"
                }
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
section {
    padding: 10rem 0;
    background-color: rgb(248, 248, 248);
}
.card-box {
    gap: 1.25rem;
}
</style>