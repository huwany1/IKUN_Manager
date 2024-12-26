<template>
  <div class="page-header">
  <h1 class="title">员工管理</h1>
    <div class="button-container">

    <el-button type="primary" :icon="Edit" />
    <el-button type="primary" :icon="Share" />
    <el-button type="primary" :icon="Delete" />
    <el-button type="primary" :icon="Search">Search</el-button>
  </div>
  </div>
  <el-table :data="tableData" style="width: 100%">
    <el-table-column prop="入职时间" label="入职时间" width="180" />
    <el-table-column prop="姓名" label="姓名" width="180" />
    <el-table-column prop="住址" label="住址" />
  </el-table>
</template>

<script lang="ts" setup>
import { Edit, Share, Delete, Search } from '@element-plus/icons-vue'
const tableData = [
  {
    入职时间: '2016-05-03',
    姓名: 'Mr.Xiong',
    住址: '翻斗花园2栋2单元',

  },
  {
    入职时间: '2016-05-02',
    姓名: 'Mr.Zhao',
    住址: '坤坤老家',
  },
  {
    入职时间: '2016-05-04',
    姓名: 'Mr.Zeng',
    住址: 'No. 189, Grove St, Los Angeles',
  },
  {
    入职时间: '2016-05-01',
    姓名: 'Mr.Chen',
    住址: 'Man!What can I say?',
  },
  {
    入职时间: '2016-05-01',
    姓名: 'Mr.Yin',
    住址: 'Earth',
  },
]
</script>

<style scoped>
.title {
  font-size: 20px;
  font-weight: bold;
}

.button-container {
  display: flex;
  justify-content: flex-end;
  margin-bottom: 50px;
}
</style>