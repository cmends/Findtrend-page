<template>
  <button id="main-btn">{{text}}</button>
</template>

<script>

export default {
    name: "Button",
    props:["text"]

}
</script>

<style scoped>
#main-btn{
    width: 129px;
        height: 42px;
        left: 1151px;
        top: 28px;
        border-radius: 40px;

        font-family: 'Effra';
            font-style: normal;
            font-weight: 400;
            font-size: 18px;
            line-height: 100%;
            
            text-align: center;
            color: #000000;
            width: 129px;
                height: 42px;
                left: 1151px;
                top: 28px;
}

</style>