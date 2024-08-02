<template>
    <div class="head">
        <h2 class="head_h2">What creators are saying about Splice</h2>
        <div class="creators">
            <div class="first">
            <img src="../assets/perOne.svg" alt="Person">
            <p>I can always find what I’m looking for on Splice, whether it’s the exact sound I want or just a bit of inspiration.</p>
            <h5>Andrew Huang</h5>
        </div>

        <div class="first">
            <img src="../assets/perTwo.svg" alt="Person">
            <p>Finally a way to buy plugins that works. By paying a little at a time, producers can get legit access to the top VSTs.</p>
            <h5>KSHMR</h5>
        </div>

        <div class="first">
            <img src="../assets/perThree.svg" alt="Person">
            <p>It’s been fun to dive into Splice’s creator community and explore tools that support my own  creative process.</p>
            <h5>Kesha Lee</h5>
        </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.head{
    color: #fff;
    background: #000;
    padding-bottom: 150px;
}
.head_h2{
    padding-left: 50px;
    padding-bottom: 50px;
}
.creators{
    display: flex;
    align-items: center;
    text-align: center;
    justify-content: space-between;
    margin-left: 180px;
    margin-right: 180px;
}
.first{
    border: 1px solid #000;
    width: 340px;
    background: #fff;
    color: #000;
    border-radius: 10px;
    transition: background-color 0.3s ease, transform 0.3s ease; 
    cursor: pointer;
}
.first:hover{
    transform: scale(1.05); 
}
p{
    padding-top: 30px;
    padding-left: 10px;
    padding-right: 20px;
}
h5{
    padding-top: 20px;
    padding-bottom: 10px;
    color: #767676;
}
img{
    margin-top: 10px;
}
</style>