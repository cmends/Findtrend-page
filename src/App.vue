<template>
  <div class="backg">
    <Nav></Nav>
    <AppHero></AppHero>
    <MainSection></MainSection>
    <div class="section3">
      <p>Findtrend helps you to increase your
        productivity and reduce your computer's
        memory load,<span class="grey-text"> an application that can
          fulfill your daily browsing needs.</span> </p>
    </div>
    <CardSection></CardSection>
    <MediaSection></MediaSection>
  </div>
</template>

<script>
import Card from "@/components/Card.vue"
import Button from "@/components/Button.vue"
import Nav from "@/components/Nav.vue"
import AppHero from "@/components/AppHero.vue"
import MainSection from "@/components/MainSection.vue"
import CardSection from "@/components/CardSection.vue"
import  MediaSection from "@/components/MediaSection.vue"

export default {
  name: 'App',
  components: { Button, Nav, AppHero, MainSection, Card, CardSection,MediaSection },
  data(){}
}
</script>

<style>
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
/* .backg{
    background-image: url("@/assets/Bg-hero.svg");
    background-size: cover;
     background:no-repeat;

} */
.section3{
  background-color: white;
  text-align: center;
  font-family: 'Effra';
    font-style: normal;
    font-weight: 700;
    font-size: 64px;
    line-height: 76px;
    color: #000000;
    padding: 140px;
}
.grey-text{
  font-family: 'Effra';
    font-style: normal;
    font-weight: 700;
    font-size: 64px;
    line-height: 76px;
    color: #ADADAD;
}




/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 60px;
} */
</style>
