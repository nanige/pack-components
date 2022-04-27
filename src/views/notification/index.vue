<template>
  <div>
    <pack-notification :value="50">
      <template #default>
        <pack-list @clickItem="clickItem" @clickAction="clickAction" :list="list" :actions="actions"></pack-list>
      </template>
    </pack-notification>
  </div>
</template>

<script lang='ts' setup>
import { list, actions } from './data'

let clickItem = (val: any) => {
  console.log(val)
}
let clickAction = (val: any) => {
  console.log(val)
}
</script>

<style lang='scss' scoped>
</style>