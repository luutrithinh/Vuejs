<script setup>
const thinh ="thằng nào đọc cái này là gay";
console.log(thinh);
import '../assets/font/stylesheet.css'
import S_Banner from './Banner.vue'
import Category from './Category.vue';
</script>

<template>
   <div class="Banner">
    <div class="Content">
        <p class="Pro">Pro.Beyond</p>
        <p class="Title">IPhone 14 <span>Pro</span></p>
        <p class="Cre">Created to change everything for the better. For everyone</p>
        <button onclick="document.location='https://www.youtube.com/watch?v=dQw4w9WgXcQ&list=RDdQw4w9WgXcQ&start_radio=1'">Shop Now</button>
    </div>
    <div>
    <img class="Iphone" src="../assets/Iphone Image.png" alt="">
   </div>
</div>
<div>
    <S_Banner></S_Banner>
    <br>
    <Category></Category>
</div>
   
</template>
<style>
.Banner{
    color: #5c5a5a;
    display: flex;
    font-family: "Inter";
    padding-left: 30px;    
    background-color: #211C24;
    width: 1440px;
    height: 632px;
}
.Pro{
    font-size: 25px;
    margin-top: 10px;
}
.Title{
    font-size: 96px;
    margin: 0;
}
.Cre{
    margin-top: 8px;
}
span{
    font-weight: bold;
}
.Content{
   padding-left: 160px;
   padding-top: 188px;
   padding-bottom: 188px;
}
.Title{
    color: white;
}
span{
    font-weight: bolder;
}
.Iphone{
    position: absolute;
    right: 160px;
}
button{
    border-radius: 10px;
    border-color: aliceblue;
    color: aliceblue;
    width: 191px;
    height: 56px;
    background-color: transparent;
}
</style>