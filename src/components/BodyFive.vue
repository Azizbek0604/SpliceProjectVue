<template>
  <div class="second">
    <div class="img">
    <img src="../assets/fourth.svg" alt="">
    </div>

    <div class="info">
    <h3 class="sec_h3">Technology</h3>
    <h1 class="sec_h1">Crate dig without the dust.</h1>
    <p class="sec_p">Our intelligent search tools help you discover sounds you would normally have to dig to find. Tech breaks the sweat, not you.</p>

    <button class="sec-btn">Discover CoSo</button>
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
    padding-left: 50px;
    background: #000;
    padding-top: 100px;
    padding-bottom: 50px;
}
.info{
    color: #fff;
    padding-left: 300px;
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