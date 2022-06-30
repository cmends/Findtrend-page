<template>
    <div class="background">
        <div class="hero-header">
            <div class="header-text">
                <h1 class="heading">Minimize your tabs. <br>
                    Find the trends!</h1>
                <p class="subheading">Don't let your computer memories consumes all of those browser tabs. <br>
                    Findtrend let you gathers all of your favorite website into one place.</p>
                <Button class="hero-btn" id="btn-text" text="Get Started 🔥"></Button>
                <img src="@/assets/img-hero.svg">
            </div>
            <div id="hero-media">
                <img src="@/assets/Group11.svg" alt="">
            </div>
        </div>
    </div>


</template>

<script>
import Button from "@/components/Button.vue"

export default {
    name: 'AppHero',
components:{Button},
}
</script>

<style scoped>

.background{
    background-image: url("@/assets/Bg-hero.svg");
        background-size: cover;
}
.hero-header{
    /* display: flex; */
    width:100%;
    align-items: center;
    /* justify-content: space-between; */
}
.header-text{
   
    width: 100%;
        height: 337.63px;
        /* left: 370px;
        top: 198px; */
}
.heading{
    font-family: 'Effra';
        font-style: normal;
        font-weight: 900;
        font-size: 72px;
        line-height: 112%;
    
        text-align: center;
        color: white;
       
}
.subheading{
    font-family: 'Effra';
        font-style: normal;
        font-weight: 400;
        font-size: 18px;
        line-height: 150%;

        text-align: center;
        color: #8B8B8B;
        height: 54px;
            /* left: 387px;
            top: 384px; */
            margin-top: 24px;
}
.hero-btn{
    height: 57px;
        width: 180px;
        /* left: 630px;
        top: 478px; */
        border-radius: 40px;
        padding: 16px, 32px, 16px, 32px;
        background: #A8FF35;
        margin-top: 50px;
       align-items: center;
       margin-left:630px;
}
#btn-text{
    font-family: 'Effra';
    font-style: normal;
        font-size: 18px;
        font-weight: 700;
        line-height: 25px;
        letter-spacing: 0em;
        text-align: center;
        color: #000000;     
}
#hero-media{
    /* width: 348.65px;
        height: 90.54px;
        left: 186px;
        top: 654.8px; */
        margin-top: 95px;
        align-items: center;
        margin-left: 186px;
       
}


</style>