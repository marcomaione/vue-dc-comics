<template>
  <div id="app">
    <myHeader></myHeader>
    <myJumbotron></myJumbotron>
    <myMain></myMain>
    <myFooter></myFooter>
  </div>
</template>

<script>
import myHeader from './components/myHeader.vue'
import myJumbotron from './components/myJumbotron.vue'
import myMain from './components/myMain.vue'
import myFooter from './components/myFooter.vue'

export default {
  name: 'App',
  components: {
    myHeader,
    myJumbotron,
    myMain,
    myFooter
  }
}
</script>

<style lang="scss">

</style>
