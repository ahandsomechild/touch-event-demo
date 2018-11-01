<template>
  <div class="hello">
  <dragElement></dragElement>
  </div>
</template>

<script>
import dragElement from './dragging-elements/'
export default {
  name: 'HelloWorld',
  components:{
    dragElement
  },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
