<template>
    <div class="service-card py-3">
        <h2 class="pt-4 pb-2">{{title}}</h2>
        <div class="subtitle pb-3">{{subtitle}}</div>
        <div class="price py-3 mb-5"><span class="currency">$</span>{{price}} <span class="service">/{{service}}</span></div>
        <ul>
            <li>
                <i class="fa-solid fa-check mr-2"></i>Lorem ipsum dolor sit
            </li>
            <li>
                <i class="fa-solid fa-check mr-2"></i>Lorem ipsum dolor sit
            </li>
            <li>
                <i class="fa-solid fa-check mr-2"></i>Lorem ipsum dolor sit
            </li>
            <li>
                <i class="fa-solid fa-check mr-2"></i>Lorem ipsum dolor sit
            </li>
            <li>
                <i class="fa-solid fa-check mr-2"></i>Lorem ipsum dolor sit
            </li>
        </ul>
    </div>
</template>

<script>
export default {
    name: 'ServiceCard',
    props: {
        title: String,
        subtitle: String,
        price: Number,
        service: String
    }
}
</script>

<style lang="scss" scoped>
ul {
    padding: 0;
    li {
        font-size: 0.8rem;
        margin: 0.8rem 0;
    }
}
.service-card {
    text-align: center;
    background:linear-gradient(180deg,rgb(59, 59, 59) 33%,rgb(255, 255, 255) 33%);
    border-radius: .625rem;
    h2 {
        text-transform: uppercase;
        font-size: 1.25rem;
        background-color: white;
        margin-bottom: 0;
    }
    .currency {
        font-size: 1.3rem;
    }
    .subtitle {
        font-size: .8rem;
        background-color: white;
    }
    .price {
        color: white;
        font-size: 2rem;
        background-color: rgb(59, 59, 59);
        padding: 0 4rem;
    }
    .service {
        font-size: .875rem;
    }
    box-shadow: 0 0 10px 0 rgba(0, 0, 0, 0.05), 0 0 30px 0 rgba(0, 0, 0, 0.15);
}
</style>