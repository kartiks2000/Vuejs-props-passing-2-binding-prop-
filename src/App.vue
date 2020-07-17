<template>
  <div class="kk">
    <h1>Hello!! I am the parent....</h1>
    <!-- <button @click="passit">Pass name</button> -->
    <input type="text" v-model="childname">
    <Child :childname="childname"></Child>
  </div>
</template>

<script>
import child from './child';
export default {
  components:{
    Child : child
  },
  data : function (){
    return{
      childname : "kartik"
    }
  }, 
}
</script>

<style scoped>
  h1{
    color: red;
  }
  div{
    /* border: 2px solid brown; */
    margin: 3rem;
  }
  .kk{
    background-color: cornsilk;
    padding: 3rem;
  }
</style>>

</style>
