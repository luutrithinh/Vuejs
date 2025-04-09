<script setup>
const Testing = "test Javascript"
console.log(Testing)
</script>

<template>
    <div class="Cate">
        <h1 class="Cate_title">Browse By Category</h1>
        <div class="arrow">
            <img src="../assets/Arrow.png" alt=""> 
            <img src="../assets/Arrow1.png" alt="">
        </div>
    </div>
    <div class="Cate_Card">
        <div class="Card">
            <div class="Card_content">
                <img src="../assets/Cart_icon/Cameras.png" alt="">
                <p>Camera</p>
            </div>
            <div class="Card_content">
                <img src="../assets/Cart_icon/Cameras.png" alt="">
                <p>Camera</p>
            </div>
            <div class="Card_content">
                <img src="../assets/Cart_icon/Cameras.png" alt="">
                <p>Camera</p>
            </div>
            <div class="Card_content">
                <img src="../assets/Cart_icon/Cameras.png" alt="">
                <p>Camera</p>
            </div>
            <div class="Card_content">
                <img src="../assets/Cart_icon/Cameras.png" alt="">
                <p>Camera</p>
            </div>
            <div class="Card_content">
                <img src="../assets/Cart_icon/Cameras.png" alt="">
                <p>Camera</p>
            </div>
            <!-- <img src="../assets/Cart_icon/Computers.png" alt="">
            <img src="../assets/Cart_icon/Gaming.png" alt="">
            <img src="../assets/Cart_icon/Headphones.png" alt="">
            <img src="../assets/Cart_icon/Phones.png" alt="">
            <img src="../assets/Cart_icon/Smart Watches.png" alt=""> -->
        </div>
    </div>
</template>

<style>
.Cate {
    display: flex;
    margin-left: 160px;
    margin-top: 80px;
}

.Cate_title {
    font-size: 25px;
}

.arrow {
    display: flex;
    width: 32px;
    height: 32px;
    padding-top: 15px;
    margin-left: 801px;
}
.Card{
    display: flex;
}
.Card_content{
    padding-top: 24px;
    text-align: center;
    background-color: #EDEDED;
    width: 160px;
    height: 120px;
    border-radius: 10px;
    margin-left: 32px;
}
.Cate_Card{
    margin-left: 100px;
}
</style>