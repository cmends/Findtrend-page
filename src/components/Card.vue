<template>
  <div>
    <div class="cards">
        <figure>
            <img :src="cardImage" alt="">
        </figure>
    </div>
  </div>
</template>

<script>
export default {
    name: 'Card',
    props:["cardImage"],

}
</script>

<style scoped>



/* .cards{
height: 120px;
    width: 266px;
    border-radius: 8px;
    background: #F5F5F5;
    text-align: center;
    padding: 40px;
   
} */

</style>