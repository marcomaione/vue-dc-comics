<template>
    <div class="container">
        <div class="up">
            <div class="items">
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <span>DIGITAL COMICS</span>
            </div>
            <div class="items">
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <span>DIGITAL COMICS</span>
            </div>
            <div class="items">
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <span>DIGITAL COMICS</span>
            </div>
            <div class="items">
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <span>DIGITAL COMICS</span>
            </div>
            <div class="items">
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <span>DIGITAL COMICS</span>
            </div>
        </div>
        <div class="midle">
            ciao
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
    .up {
        display: flex;
        justify-content: center;
        min-height: 250px;
        background-color:#0282f9 ;
    }
    .items {
        display: flex;
        align-items: center;
    }
    .midle {
        min-height: 300px;
        background-image: url("../assets/img/footer-bg.jpg");
    }
}

</style>