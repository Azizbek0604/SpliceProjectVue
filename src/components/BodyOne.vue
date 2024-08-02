<template>
    <div class="main">
        <h1 class="main_h1">Step into the <br>
        producer's <br>
        playground </h1>
        <p class="main_p">Explore the world’s best sample library and an <br>
        unmatched marketplace of plugins and DAWs.</p>

        <button class="main_button">Try Free</button>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.main{
    background-image: url('../assets/main.svg');
    width: 100%;
    height: 730px;
    background-size: cover;
}
.main_h1{
    padding-left: 70px;
    font-size: 100px;
    font-weight: 400;
    padding-top: 190px;
    color: #fff;
}
.main_p{
    color: #fff;
    padding-left: 70px;
    font-size: 26px;
    padding-top: 20px;
}
.main_button {
    width: 125px;
    height: 56px;
    border-radius: 8px;
    margin-left: 70px;
    margin-top: 40px;
    cursor: pointer;
    background: #0033ff;
    color: #fff;
    border: none;
    transition: background-color 0.3s ease, transform 0.3s ease; 
}
.main_button:hover {
    background-color: #0056ff;
    transform: scale(1.05); 
}

</style>