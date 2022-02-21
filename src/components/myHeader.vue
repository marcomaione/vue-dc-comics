<template>
   <div class="menu">
       <img src="../assets/img/dc-logo.png" alt="">
       <nav>
            <ul>
                <li>
                    <a href="#">CHARACTERS</a>
                </li>
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
            </ul>
        </nav>
       
    </div>
    
</template>

<script>
export default {
  name: 'myHeader',
  
}
</script>

<style lang="scss">

.menu {
    border: solid 1px black;
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
