<template>
  <div class="second">
    <div class="info">
    <h3 class="sec_h3">Gear</h3>
    <h1 class="sec_h1">Build a drool-worthy studio, <br> affordably.</h1>
    <p class="sec_p">The industry’s top software, all in one place, on payment <br> plans built to work for you..</p>

    <button class="sec-btn">Explore Gear</button>
    </div>

    <div class="img">
    <img src="../assets/third.svg" alt="">
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
    padding-left: 70px;
    background: #000;
    padding-top: 100px;
    padding-bottom: 50px;
}
.info{
    color: #fff;
}
.img{
    margin-left: 290px;
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
.sec-btn {
    margin-top: 20px;
    width: 140px;
    height: 40px;
    border-radius: 10px;
    background: #0033ff;
    border: none;
    color: #fff;
    font-weight: 400;
    font-size: 16px;
    cursor: pointer;
    transition: background-color 0.3s ease, transform 0.3s ease; 
}

.sec-btn:hover {
    transform: scale(1.05); 
}

</style>