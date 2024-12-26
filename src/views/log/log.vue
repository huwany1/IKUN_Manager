<template>
    <el-row>
      <el-col :sm="12" :lg="6">
        <el-result
          icon="success"
          title="唱"
          sub-title="迎面走来的你让我如此蠢蠢欲动"
        >
          <template #extra>
            <el-button type="primary">Back</el-button>
          </template>
        </el-result>
      </el-col>
      <el-col :sm="12" :lg="6">
        <el-result
          icon="warning"
          title="跳"
          sub-title="这种感觉我从未有如此的CRASH ON YOU"
        >
          <template #extra>
            <el-button type="primary">Back</el-button>
          </template>
        </el-result>
      </el-col>
      <el-col :sm="12" :lg="6">
        <el-result
          icon="error"
          title="RAP"
          sub-title="你是我的，我是你的谁"
        >
          <template #extra>
            <el-button type="primary">Back</el-button>
          </template>
        </el-result>
      </el-col>
      <el-col :sm="12" :lg="6">
        <el-result icon="info" title="篮球">
          <template #sub-title>
            <p>鸡你太美</p>
          </template>
          <template #extra>
            <el-button type="primary">Back</el-button>
          </template>
        </el-result>
      </el-col>
    </el-row>
  </template>
  