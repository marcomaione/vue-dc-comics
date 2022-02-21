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
            <div class="midle-left">
                <div class="DC-1">
                    <ul>
                        <h4>DC COMICS</h4>
                        <li>
                            <a href="#">Characters</a>
                        </li>
                        <li>
                            <a href="#">Characters</a>
                        </li>
                        <li>
                            <a href="#">Characters</a>
                        </li>
                        <li>
                            <a href="#">Characters</a>
                        </li>
                        <li>
                            <a href="#">Characters</a>
                        </li>
                        <li>
                            <a href="#">Characters</a>
                        </li>
                        <li>
                            <a href="#">Characters</a>
                        </li>
                        <h4>DC COMICS</h4>
                        <li>
                            <a href="#">Characters</a>
                        </li>
                        <li>
                            <a href="#">Characters</a>
                        </li>
                    </ul>
                </div>
                <div class="DC-2">
                    <ul>
                        <h4>DC</h4>
                        <li>
                            <a href="#">Characters</a>
                        </li>
                        <li>
                            <a href="#">Characters</a>
                        </li>
                        <li>
                            <a href="#">Characters</a>
                        </li>
                        <li>
                            <a href="#">Characters</a>
                        </li>
                        <li>
                            <a href="#">Characters</a>
                        </li>
                        <li>
                            <a href="#">Characters</a>
                        </li>
                        <li>
                            <a href="#">Characters</a>
                        </li>
                         <li>
                            <a href="#">Characters</a>
                        </li>
                        <li>
                            <a href="#">Characters</a>
                        </li>
                        <li>
                            <a href="#">Characters</a>
                        </li>
                    </ul>
                </div>
                <div class="DC-3">
                    <ul>
                        <h4>SITES</h4>
                        <li>
                            <a href="#">Characters</a>
                        </li>
                        <li>
                            <a href="#">Characters</a>
                        </li>
                        <li>
                            <a href="#">Characters</a>
                        </li>
                        <li>
                            <a href="#">Characters</a>
                        </li>
                        <li>
                            <a href="#">Characters</a>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="midle-right">
                <img src="../assets/img/dc-logo-bg.png" alt="">
            </div>
            
        </div>
        <div class="under">
            <div>
                <button>SIGN-UP NOW!</button>
            </div>
            <div>
                <img src="../assets/img/footer-facebook.png" alt="">
                <img src="../assets/img/footer-periscope.png" alt="">
                <img src="../assets/img/footer-pinterest.png" alt="">
                <img src="../assets/img/footer-twitter.png" alt="">
                <img src="../assets/img/footer-youtube.png" alt="">
            </div>
        </div>
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
        z-index: 999;
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
        height: 250px;
        overflow: hidden;
        
    }
    .midle-left {
        width: 40%;
        display: flex;
    }
    .midle-right {
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
        min-height: 100px;
        background-color:#303030;
        display: flex;
        justify-content: space-around;
        align-items: center;
    }
    .DC-1 {
        width:30% ;
        
    }
    .DC-2 {
        width:30% ;
        
    }
    .DC-3 {
        width:30% ;
       
    }
    h4 {
        color: white;
    }
    ul {
        list-style-type: none;
        color: rgb(155, 152, 152);
    }
    a {
        text-decoration: none;
        color:rgb(155, 152, 152) ;
    }
}

</style>