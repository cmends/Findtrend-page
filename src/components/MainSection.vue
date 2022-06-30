<template>
    <div class="section-container">
        <div>
            <h1 class="main-heading">Open new tabs is sh*t</h1>
            <img class="leftside-image"  src="@/assets/Group427321657.svg" alt="">
            <img  class="rightside-image" src="@/assets/Group427.svg" alt="">
        </div>

        <div class="white-section">
            <div>
                <img class="white-img" src="@/assets/Group17.svg" alt="">
            </div>
        </div>

        <p class="main-subheading">A solution for your browser tabs and don't make your device get slower over time. Get
            ease and faster to
            discover a trend with just one tab.</p>
    </div>
</template>

<script>
export default {
    name:'MainSection'

}
</script>

<style>

.white-img{
    width: 341.23px;
        height: 82px;
        margin-top: 60px;
        /* margin-left: 80.5px; */
}
.white-section{
    width: 502px;
        height: 202px;
        background: #F5F5F5;
        border-radius: 16px;
        text-align: center;
        margin-left: 150px;
        margin-top: -140px;
}

.section-container{
background-color:#A8FF35;;
text-align: center;
padding: 140px 345px
}

.main-heading{
    font-family: 'Effra';
        font-style: normal;
        font-weight: 700;
        font-size: 72px;
        line-height: 86px;
        text-align: center;
        color: #000000;
        margin-bottom:140px;   
}
.main-subheading{
    font-family: 'Effra';
        font-style: normal;
        font-weight: 400;
        font-size: 18px;
        line-height: 150%;
        text-align: center;
        color: #000000;
        margin-top: 60px;
}
.leftside-image{
    position: relative;
    right: 280px;
}
.rightside-image {
    position: relative;
    left: 250px;
}

</style>