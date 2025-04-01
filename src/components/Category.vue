<script setup>
const Testing = "test Javascript"
console.log(Testing)
</script>

<template>
    <div>
        <div class="Title_Cate">
            <p>Browse By Category</p>
            <div class="pagination">
            <img src="../assets/Arrow1.png" alt="">
            <img src="../assets/Arrow.png" alt="">
        </div>
        </div>
        <div class="Cate_Card">
            <div class="card"><img src="../assets/Cart_icon/Phones.png" alt=""></div>
            <div class="card"><img src="../assets/Cart_icon/Smart Watches.png" alt=""></div>
            <div class="card"><img src="../assets/Cart_icon/Cameras.png" alt=""></div>
            <div class="card"><img src="../assets/Cart_icon/Headphones.png" alt=""></div>
            <div class="card"><img src="../assets/Cart_icon/Computers.png" alt=""></div>
            <div class="card"><img src="../assets/Cart_icon/Gaming.png" alt=""></div>

        </div>
    </div>
</template>

<style>
.Title_Cate{
    display: flex;
}
</style>