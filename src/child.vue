<template>
  <div>
    <h1>Hello!! I am the child....</h1>
    <h2>my name is {{childname}}</h2>
  </div>
</template>

<script>
export default {
  props :["childname"]
}
</script>

<style scoped>
    h1{
        color: blue;
    }
    div{
        background-color: burlywood;
    }
</style>>

</style>
