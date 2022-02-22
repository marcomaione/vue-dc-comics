<template>
<div class="more">
    <button>LOAD MORE</button>
</div>
  
</template>

<script>
export default {
    name:'loadMore',

}
</script>


<style lang="scss">
.more {
    height: 50px;
    background-color: black;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    button {
        border: solid 1px #0282f9 ;
        background-color:#0282f9 ;
        color: white;
        height: 40px;
        cursor: pointer;

    }
}

</style>