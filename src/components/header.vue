<script setup>

</script>
<template>
    <div class="Top">
        <img class="Logo" width="65.4" height="22.87" src="../assets/Logo.png" alt="">
        <div class="input-item">
            <i><img src="../assets/Search.png" alt=""></i>
            <input type="text" class="search" placeholder="Search">
        </div>
        <div class="navigation">
            <p>Home</p>
            <p>About</p>
            <p>Contact Us</p>
            <p>Blog</p>
        </div>
        <div class="Icon">
            <img class="Icon_Fav" src="../assets/Favorites.png" alt="">
            <img class="Icon_Cart" src="../assets/Cart.png" alt="">
            <img class="Icon_User" src="../assets/User.png" alt="">
        </div>
        
    </div>

</template>
<style>
.Top {
    display: flex;
    margin: auto;
    width: 1440px;
    height: 88px;    
}
.Logo{
    padding-left: 160px;
    padding-top: 32.56px;
    padding-bottom: 32.56px;
    padding-right:49.12px ;
}
.input-item i{
    position: absolute;
}
i{
        padding-top: 35px;
        padding-left: 16px;
}

.search {
    background-color: #F5F5F5;
    width: 372px;
    height: 56px;
    border-radius: 5px;
    padding-left: 48px;
    margin-top: 16px;
    margin-bottom: 16px;
}

.navigation{
    display: flex;  
    text-align: center;
    width: 390px;
    height: 19px;
    margin-top: 21.5px;
    margin-left: 56.53px;
    padding-right: 40px;
}
.navigation p{
    padding-left: 52px;
    font-size: 16px;
}
.Icon{
    margin-top: 28px;
    padding-right: 24px;
}
.Icon_Fav{
    padding-right: 24px;
}
.Icon_Cart{
    padding-right: 24px;
}
.Icon_User{
    padding-right:24px;
}
</style>