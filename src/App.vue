<template>
  <div>
    <h1>My name is {{ prefix }} Mohamed Amin</h1>
    <h2>My name is {{ prefix2 }} Mohamed Amin</h2>
    <Home-Selector></Home-Selector>
  </div>
</template>

<script>
export default {
  data: function() {
    return{
      prefix : 'Mr',
      prefix2: 'Mss'
    }
  }
}
</script>

<style lang="scss">
  h1{
    color: red;
  }
  h2{
    color: blue;
  }
</style>
