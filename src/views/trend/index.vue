<template>
  <div>
    <el-divider>正常趋势</el-divider>
    <div class="flex">
      <div>
        <pack-trend text="营业额"></pack-trend>
      </div>
      <div>
        <pack-trend text="销售额" type="down"></pack-trend>
      </div>
    </div>
        <br />
    <el-divider>颜色翻转</el-divider>
    <div class="flex">
    <div><pack-trend text="销售额" reverseColor></pack-trend></div>
    <div><pack-trend text="营业额" type="down" reverseColor></pack-trend></div>
    </div>
    <br />
    <el-divider>自定义图标颜色</el-divider>
    <div class="flex">
      <div>
        <pack-trend text="营业额" upIconColor="blue"></pack-trend>
      </div>
      <div>
        <pack-trend text="销售额" type="down" downIconColor="#123456"></pack-trend>
      </div>
    </div>

    <br />
    <el-divider>自定义文字颜色</el-divider>
    <div class="flex">
    <div><pack-trend text="营业额" upTextColor="blue"></pack-trend></div>
    <div><pack-trend text="销售额" type="down" downTextColor="yellow"></pack-trend></div>
    </div>
    <br />
    <el-divider>自定义图标</el-divider>
    <div class="flex">
    <div><pack-trend upIcon="CaretTop">营业额</pack-trend></div>
    <div><pack-trend type="down" downIcon="CaretBottom">销售额</pack-trend></div>
  </div>
   </div>
</template>

<script lang='ts' setup>
</script>

<style lang='scss' scoped>
.flex {
  display: flex;
  div {
    margin-right: 10px;
  }
}
</style>