<template>
  <div class="hello">
    <div style="height:800px; width: 600px; border: 1px solid red; position: margin:30px auto;">
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
