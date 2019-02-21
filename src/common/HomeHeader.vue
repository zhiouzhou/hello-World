<template>
    <div id="homeHeader">
      <p>易酒批头部</p>
      <span>注销</span>
    </div>
</template>

<script>
    export default {
        name: "HomeHeader"
    }
</script>

<style scoped lang="stylus">
  #homeHeader{
    height:120px
    background: #ddd
    padding:0 20px
    display: flex
    flex-direction:row
    justify-content space-between
    align-items center
  }
</style>
