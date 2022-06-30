<template>
    <h1 class="social-headie">All platforms connect to Findtrend</h1>
    <div class="social-cards">
        <Card class="social-imgs" v-for="social in socialData" :key="social.id" :cardImage="social.image"></Card>
    </div>

    <div class="tweets">
        <img src="@/assets/tweet1.svg" alt="">
        <img src="@/assets/tweet2.svg" alt="">
        <img src="@/assets/tweet3.svg" alt="">
    </div>
</template>

<script>
import Card from "@/components/Card.vue"
export default {
    name: 'MediaSection',
    components: { Card },

    data() {
        return {
            socialData: [
                {
                    id: "socialOne",
                    image:require('@/assets/image105.svg')
                },
                {
                    id: "socialTwo",
                    image: require('@/assets/image96.svg')
                },
                {
                    id: "socialThree",
                    image: require('@/assets/Rectangle6.svg')
                },
                {
                    id: "socialFour",
                    image: require('@/assets/image111.svg')
                },
                {
                    id: "socialFive",
                    image: require('@/assets/image113.svg')
                },
                {
                    id: "socialSix",
                    image: require('@/assets/image114.svg')
                },
                {
                    id: "socialSeven",
                    image: require('@/assets/image115.svg')
                },
                {
                    id: "socialEight",
                    image: require('@/assets/image112.svg')
                },
            ],
        }
    },
}
</script>

<style scoped>




.social-imgs{
    width: 124px;
        height: 124px;
        background:white;
        border-radius: 8px;
        margin-top: 80px ;
        
}

.social-cards {
    justify-content: space-evenly;
    display: flex;
    flex-wrap: wrap;
    padding: 80px;
    text-align: center;
    align-items: center;
    gap: 32px;
    /* margin-bottom: 80px; */
}
.social-headie {
font-family: 'Effra';
    font-style: normal;
    font-weight: 700;
    font-size: 64px;
    line-height: 76px;
    text-align: center;
    color: #000000;
    margin-top: 140px;
}
.tweets{
    text-align: center;
        align-items: center;
        margin-top:40px; 
        gap: 60px ;
}

</style>