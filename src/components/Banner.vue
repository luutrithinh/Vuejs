<script setup>
const Ten = ["thanh", "thinh", "thong"];
console.log(Ten);
import '../assets/font/stylesheet.css'
</script>

<template>
    <div class="S-Banner">
        <div>
            <div class="Left-Banner">
                <img width="360" height="343" src="../assets/PlayStation.png" alt="">
                <div class="Wide-S">
                    <h1>Playstation 5</h1>
                    <p class="Text">Incredibly powerful CPUs, GPUs, and an SSD with integrated I/O will redefine your
                        PlayStation experience. </p>
                </div>
            </div>
            <div class="Squares">
                <img class="Headphone" src="../assets/headphone.png" alt="">
                <div class="Squares-w">
                    <div class="squares-Title-W">Apple AirPods <span>Max</span></div>
                    <p class="Text">Computational audio. Listen, it's powerful</p>
                </div>
                <img class="Vr" src="../assets/Vr.png" alt="">
                <div class="Squares-B">
                    <div class="squares-Title-B">Apple Vision <span>Pro</span></div>
                    <p class="Text">An immersive way to experience entertainment</p>
                </div>
            </div>
        </div>
        <div>
            <div class="Right-Banner">
                <div class="content_RB">
                    <div class="Mac">Macbook <br><span>Air</span></div>
                    <p class="Text">The new 15-inch MacBook Air makes room for more of what you love with a spacious
                        Liquid
                        Retina display.</p>
                    <button class="R-Banner"
                        onclick="document.location='https://www.youtube.com/watch?v=dQw4w9WgXcQ&list=RDdQw4w9WgXcQ&start_radio=1'">Shop
                        Now</button>
                </div>
                <img class="Pic_Mac" src="../assets/Macbook.png" alt="">

            </div>
        </div>
    </div>
</template>

<style>
.S-Banner {
    width: 1440px;
    height: 600px;
    display: flex;
}

.Left-Banner {
    display: flex;
    width: 720px;
    height: 328x;
}

.Wide-S {
    padding-top: 100px;
    font-family: "Inter";
}

.Text {
    font-size: 14px;
    color: #909090;
}

h1 {
    font-size: 49px;
}

*/ .ten {
    background-color: aqua;
}

.R-Banner {
    border-radius: 10px;
    border-color: black;
    color: black;
    width: 191px;
    height: 56px;
    background-color: transparent;
}

.Squares {
    display: flex;
    width: 720px;
    height: 272px;
}

.Squares-w {
    background-color: #EDEDED;
    padding-left: 200px;
    padding-right: 48px;
    padding-top: 64.5px;
    padding-bottom: 65.5px;

}

.Squares-B {
    background-color: #353535;
    padding-left: 200px;
    padding-right: 48px;
    padding-top: 64.5px;
    padding-bottom: 65.5px;
}

.squares-Title-W {
    font-size: 29px;
    color: black;
}

.squares-Title-B {
    font-size: 29px;
    color: rgb(255, 255, 255);
}

.Headphone {
    position: absolute;
}

.Vr {
    position: absolute;
    padding-left: 353px;
    padding-top: 50px;
}

.Right-Banner {
    width: 694px;
    height: 455px;
    background-color: #EDEDED;
    display: flex;
    padding-left: 56px;
    /* padding-right: 304px; */
    padding-top: 160px;
}

.Mac {
    font-size: 64px;
    font-family: "Inter";
}

.content_RB {
    padding-top: 10px;
    padding-right: 390px;

}

.Pic_Mac {
    position: absolute;
    right: 40px;
    top: 800px;
}
</style>