<template>
  <div id="app">
    <div id="cover"></div>
    <Header/>
    <todo/>
    <Footer/>
  </div>
</template>
<script>
import Header from './todo/header.vue'
import Todo from './todo/todo.vue'
import Footer from './todo/footer.jsx'

export default {
  components: {
    Header,
    Todo,
    Footer
  }
}
</script>
<style lang="stylus">
#app
  position absolute
  left 0
  right 0
  top 0
  bottom 0
#cover
  position absolute
  left 0
  right 0
  top 0
  bottom 0
  background-color #999
  opacity .9
  z-index -1
</style>
