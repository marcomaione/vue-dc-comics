<template>
    <div class="container">
        <div class="up">
            <div class="items">
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <span>DIGITAL COMICS</span>
            </div>
            <div class="items">
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
                <span>DIGITAL COMICS</span>
            </div>
            <div class="items">
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                <span>DIGITAL COMICS</span>
            </div>
            <div class="items">
                <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                <span>DIGITAL COMICS</span>
            </div>
            <div class="items">
                <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                <span>DIGITAL COMICS</span>
            </div>
        </div>
        <div class="midle">
            <div class="midle-left"></div>
            <div class="midle-right">
                <img src="../assets/img/dc-logo-bg.png" alt="">
            </div>
            
        </div>
        <div class="under"></div>
    </div>
</template>

<script>
export default {
  name: 'myFooter',
  
}
</script>

<style lang="scss">

.container {
    width: 100%;
    background-color:#0282f9 ;
    .up {
        width: 80%;
        width: 100%;
        margin: 0px auto;
        display: flex;
        justify-content: center;
        align-items: center;
        min-height: 250px;
        background-color:#0282f9 ;
    }
    img {
        max-width: 60px;
    }
    span {
        margin:15px;
    }
    .items {
        display: flex;
        align-items: center;
    }
    .midle {
        min-height: 300px;
        background-image: url("../assets/img/footer-bg.jpg");
        display: flex;
        justify-content: center;
        width: auto;
        height: 200px;
    }
    .midle-left {
        border:solid 1px black;
        width: 40%;
    }
    .midle-right {
        border:solid 1px black;
        width: 40%;
        display: flex;
        align-items: center;
        justify-content: center;
    }
    .midle-right img {
        max-width:100%;
    }
    .under {
        width: 100%;
        min-height: 200px;
        background-color: black;
    }
}

</style>