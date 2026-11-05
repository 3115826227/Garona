<template>
  <el-container class="app">
    <el-header class="header">Garona · 企业管理平台</el-header>
    <el-main><router-view /></el-main>
  </el-container>
</template>

<style scoped>
.app { min-height: 100vh; }
.header { display: flex; align-items: center; border-bottom: 1px solid #e5e7eb; font-weight: 600; }
</style>
