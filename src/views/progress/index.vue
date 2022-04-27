<template>
  <div>
    <pack-progress isAnimate :percentage="60"></pack-progress>
    <br />
    <pack-progress isAnimate status="success" :stroke-width="20" :percentage="60"></pack-progress>
    <br />
    <pack-progress :time="5000" type="circle" isAnimate :percentage="60"></pack-progress>
  </div>
</template>

<script lang='ts' setup>
</script>

<style lang='scss' scoped>
</style>