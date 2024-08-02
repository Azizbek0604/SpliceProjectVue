<template>
   <header class="head">
         <img src="../assets/logo.svg" alt="img">
        <ul>
            <li><a href="#">Sounds</a></li>
            <li><a href="#">Skills</a></li>
            <li><a href="#">Plugins</a></li>
            <li><a href="#">Studio</a></li>
            <li><a href="#">Community</a></li>
            <li><a href="#">Blog</a></li>
            <li><a href="#">Pricing</a></li>
        </ul>
       
       <div class="nav-right">
            <button class="btnOne">Login</button>      
            <button class="btnTwo">Sign Up</button>      
       </div>
   </header> 
</template>

<script>
export default {
  
}
</script>

<style scoped>
.head{
    background: #000;
    display: flex ;
    width: 100%;
    height: 71px;
    align-items: center;
}
img{
    margin-left: 50px;
}
ul{
    display: flex;
    list-style: none;
}
a {
    text-decoration: none;
    margin-left: 30px;
    color: #A6A8AD;
    font-weight: 500;
    font-size: 17px;
    transition: color 0.3s ease, transform 0.3s ease; 
    display: inline-block; 
}
a:hover {
    color: #fff; 
    transform: scale(1.2); 
}
.nav-right{
    margin-left: 650px;
}
.btnOne{
    width: 95px;
    height: 35px;
    border-radius: 20px;
    border: none;
    background: none;
    color: #A6A8AD;
    cursor: pointer;
    font-weight: 500;
    font-size: 16px;
}
.btnOne:hover{
    background: #fff;
    color: #000;
}
.btnTwo{
    margin-left: 20px;
    width: 95px;
    height: 35px;
    border-radius: 20px;
    border: none;
    cursor: pointer;
    font-weight: 500;
    font-size: 16px;
    transition: background-color 0.3s ease, transform 0.3s ease; 
}
.btnTwo:hover {
    transform: scale(1.05); 
}
</style>