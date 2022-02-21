<template>
   <div class="menu">
       <img src="../assets/img/dc-logo.png" alt="">
       <nav>
            <ul>
                <li v-for="(link, index) in links" :key="index">
                    <a href="#">{{link.text}}</a>
                </li>
                <!-- 
                <li>
                    <a href="#">COMICS</a>
                </li>
                <li>
                    <a href="#">MOVIES</a>
                </li>
                <li>
                    <a href="#">TV</a>
                </li>
                <li>
                    <a href="#">GAMES</a>
                </li>
                <li>
                    <a href="#">COLLECTIBLES</a>
                </li>
                <li>
                    <a href="#">VIDEOS</a>
                </li>
                <li>
                    <a href="#">FANS</a>
                </li>
                <li>
                    <a href="#">NEWS</a>
                </li>
                <li>
                    <a href="#">SHOP</a>
                </li>
                -->
            </ul>
        </nav>
       
    </div>
    
</template>

<script>
export default {
  name: 'myHeader',
  data() {
      return{
          links: [
            {
                text:"CHARACTERS",
                url:"#",
                current:false,
            },
            {
                text:"COMICS",
                url:"#",
                current: true,
            },
            {
                text:"MOVIES",
                url:"#",
                current:false,
            },
            {
                text:"TV",
                url:"#",
                current:false,
            },
            {
                text:"GAMES",
                url:"#",
                current:false,
            },
            {
                text:"COLLECTIBLES",
                url:"#",
                current:false,
            },
            {
                text:"VIDEOS",
                url:"#",
                current:false,
            },
            {
                text:"FANS",
                url:"#",
                current:false,
            },
            {
                text:"NEWS",
                url:"#",
                current:false,
            },
            {
                text:"SHOP",
                url:"#",
                current:false,
            },
            ],

        }
    }
  
}
</script>

<style lang="scss">

.menu {
    width: 80%;
    margin: 0px auto;
    display: flex;
    justify-content: space-between;
    align-items: center;

    li {
        list-style: none;
        display:inline-block;
    }
    a {
        text-decoration: none;
        padding: 0px 10px;
        color:black;
    }
}


</style>
