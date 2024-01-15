<template>
  <div class="box">
    <el-button :icon="Edit">测试按钮</el-button>
    <SvgIcon name="refresh" color="green"></SvgIcon>
  </div>
</template>

<script setup lang="ts">
import { Edit } from "@element-plus/icons-vue";
</script>

<style scoped lang="scss">
.box {
  height: 600px;
}
</style>
