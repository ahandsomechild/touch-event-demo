<template>
  <div class="hello">
    <div style="height: 500px; width: 300px; border: 1px solid red; position: relative;">
      <dragElement :parent="true" ></dragElement>
    </div>
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
