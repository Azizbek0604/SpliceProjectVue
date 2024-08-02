<template>
    <div class="Card">
        <h1>Try Splice today</h1>
        <button class="btn">Start Now</button>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.Card{
    background-image: url('../assets/last.svg');
    width: 100%;
    height: 700px;
    background-size: cover;
    color: #fff;
}
h1{
    align-items: center;
    text-align: center;
    padding-top: 330px;
    font-weight: 400;
    font-size: 56px;
}
button{
    margin-top: 30px;
    margin-left: 710px;
}
.btn {
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

.btn:hover {
    transform: scale(1.05); 
}
</style>