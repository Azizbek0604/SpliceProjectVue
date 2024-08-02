<template>
  <div>
    <Header/>
    <Reklama/>
    <BodyOne/>
    <BodyTwo/>
    <BodyThree/>
    <BodyFour/>
    <BodyFive/>
    <Creators/>
    <Card/>
    <Footer/>
  </div>
</template>

<script>
import Header from "./components/Header.vue"
import Reklama from "./components/Reklama.vue"
import BodyOne from "./components/BodyOne.vue"
import BodyTwo from "./components/BodyTwo.vue"
import BodyThree from "./components/BodyThree.vue"
import BodyFour from "./components/BodyFour.vue"
import BodyFive from "./components/BodyFive.vue"
import Creators from "./components/Creators.vue"
import Card from "./components/Card.vue"
import Footer from "./components/Footer.vue"
export default {
  components: {
    Header,
    Reklama,
    BodyOne,
    BodyTwo,
    BodyThree,
    BodyFour,
    BodyFive,
    Creators,
    Creators,
    Card,
    Footer
  }
}
</script>

<style scoped>

</style>