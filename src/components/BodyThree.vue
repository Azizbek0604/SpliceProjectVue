<template>
  <div class="second">
    <div class="img">
    <img src="../assets/second.svg" alt="">
    </div>

    <div class="info">
    <h3 class="sec_h3">Connected Experience</h3>
    <h1 class="sec_h1">A workflow that actually flows.</h1>
    <p class="sec_p">Preview samples in your track’s key and <br> tempo, drag and drop sounds into your DAW, and organize your favorite <br> samples, MIDI and presets in one place.</p>
    </div>
  </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.second{
    display: flex;
    align-items: center;
    background: #000;
    padding-top: 100px;
    padding-bottom: 50px;
}
.info{
    color: #fff;
    padding-left: 350px;
}
.sec_h3{
    font-weight: 400;
    font-size: 16px;
    color: #A6A8AD;
}
.sec_h1{
    font-size: 42px;
    font-weight: 600;
    padding-top: 20px;
}
.sec_p{
    font-weight: 500;
    font-size: 24px;
    padding-top: 20px;
}


</style>