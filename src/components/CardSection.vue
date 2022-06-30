<template>
    <h1 class="headie">Findtrend make +1000 Startup grow</h1>
    <div class="card-images">
        <Card class="actual-img" v-for="cardd in cardData" :key="cardd.id" :cardImage="cardd.image"></Card>
    </div>

</template>

<script>
import Card from "@/components/Card.vue"
export default {
    name: 'CardSection',
    components: { Card },
    
    data() {
        return {
            cardData: [
                {
                    id: "cardOne",
                    image:require('@/assets/image116.svg'),
                },
                 {
                    id: "cardTwo",
                    image: require('@/assets/image117.svg'),
                },
                {
                    id: "cardThree",
                    image: require('@/assets/image118.svg'),
                },
                {
                    id: "cardFour",
                    image: require('@/assets/image119.svg'),
                },
                {
                    id: "cardFive",
                    image: require('@/assets/image120.svg'),
                },
                {
                    id: "cardSix",
                    image: require('@/assets/image121.svg'),
                },
                {
                    id: "cardSeven",
                    image: require('@/assets/image122.svg'),
                },
                {
                    id: "cardEight",
                    image: require('@/assets/image124.svg'),
                },
                {
                    id: "cardNine",
                    image: require('@/assets/image125.svg'),
                },
                {
                    id: "cardTen",
                    image: require('@/assets/image126.svg'),
                },
                {
                    id: "cardEleven",
                    image: require('@/assets/image127.svg'),
                },
                {
                    id: "cardTwelve",
                    image: require('@/assets/image128.svg'),
                },
                {
                    id: "cardThirteen",
                    image: require('@/assets/image129.svg'),
                },
                {
                    id: "cardFourteen",
                    image: require('@/assets/image130.svg'),
                },
                {
                    id: "cardFifteen",
                    image: require('@/assets/image132.svg'),
                },
                {
                    id: "cardSixteen",
                    image: require('@/assets/image133.svg'),
                },
            ]
        }
        
    }

}
</script>

<style scoped>

.card-images{
    justify-content: space-evenly;
    display: flex;
    flex-wrap: wrap;
    padding: 140px;
    text-align: center;
    align-items: center;
    gap: 32px;
    /* margin-bottom: 80px; */
}
.headie{
    font-family: 'Effra';
        font-style: normal;
        font-weight: 700;
        font-size: 64px;
        line-height: 76px;
        text-align: center;
        color: #000000;
        margin-top: 140px;
}
.actual-img{
    height: 120px;
        width: 266px;
        border-radius: 8px;
        background: #F5F5F5;
        text-align: center;
        padding: 40px;
}

</style>