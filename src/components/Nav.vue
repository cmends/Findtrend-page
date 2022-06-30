<template>
    <header>
        <div class="nav-container">
            <div>
                <nav class="navbar">
                    <figure>
                        <img src="@/assets/Vector.png" alt="">
                        <p id="left-text">Findtrend</p>
                    </figure>
                </nav>
            </div>

            <div id="nav-links">
                <ul class="right-nav">
                    <li v-for="link in links" :key="link"><a class='right-links'>{{link}}</a></li>
                </ul>

            </div>
            <div class="right-side">
                <p class=" right-text">Login</p>
                <Button id="nav-btn" text="Register"></Button>
            </div>

        </div>

    </header>
</template>

<script>
import Button from "@/components/Button.vue"
export default {
    name: 'Nav',
    components: { Button },
    data() {
        return {
            links:['About Us','How it Works','Pricing','Solution','Features']
        }
    }
}
</script>

<style scoped>
.nav-container{
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding-left: 80px;
    padding-right: 80px;
}
figure{
    display: flex;
    align-items: center;
}
header {
    height: 100px;
    background-image: url("@/assets/Bg-hero.svg");
    /* background-color: #000000; */
    /* display: flex;
    text-align: center; */
    /* margin-bottom: 10px;  */
    /* margin-top: -50px; */
}
.navbar{
    display: flex;
    /* justify-content: space-between; */
    align-items: center;
    /* width: 100%; */
        height: 99px;
        /* left: 80px; */
        /* top: 0px; */     
}
.right-nav{
    display: flex;
   list-style: none;
   gap:40px;
}
/* .right-nav li{
    margin-left: 120px;
} */
.right-links{
    font-family: 'Effra';
        font-style: normal;
        font-weight: 400;
        font-size: 18px;
        line-height: 100%;
        /* identical to box height, or 18px */
        text-align: center;
        color: white;
        width: 488px;
            height: 18px;
            left: 396px;
            top: 40px;
}
#left-text{
font-family: 'Inter';
    font-style: normal;
    font-weight: 700;
    font-size: 24px;
    line-height: 100%;
    /* identical to box height, or 24px */
    text-align: center;
    color:white;
    height: 24px;
        width: 114px;
        /* left: 51px;
        top: 8px; */
}
#nav-btn{
        background: #FFFFFF;

        font-family: Effra;
            font-size: 18px;
            font-weight: 400;
            line-height: 18px;
            letter-spacing: 0em;
            text-align: center;

            height: 42px;
                width: 129px;
                /* left: 1151px;
                top: 28px; */
                border-radius: 40px;
                /* padding: 12px, 32px, 12px, 32px;
                gap: 10px; */
            
}
.right-text{
    font-family: Effra;
        font-size: 18px;
        font-weight: 400;
        line-height: 18px;
        letter-spacing: 0em;
        text-align: center;
        color: #FFFFFF;
        height: 18px;
            width: 44px;
            margin-right: 50px;
        
}
.right-side{
    display: flex;
    align-items: center;
}


</style>