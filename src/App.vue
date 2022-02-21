<template>
  <div id="app">
    <myHeader></myHeader>
    <myMain></myMain>
    <myFooter></myFooter>
  </div>
</template>

<script>
import myHeader from './components/myHeader.vue'
import myMain from './components/myMain.vue'
import myFooter from './components/myFooter.vue'

export default {
  name: 'App',
  components: {
    myHeader,
    myMain,
    myFooter
  }
}
</script>

<style lang="scss">

</style>
