<template>
  <el-steps :active="1">
    <el-step title="Step 1" :icon="Edit" />
    <el-step title="Step 2" :icon="Upload" />
    <el-step title="Step 3" :icon="Picture" />
  </el-steps>
</template>

<script lang="ts" setup>
import { Edit, Upload, Picture } from '@element-plus/icons-vue'
</script>
