<template>
  <el-row>
    <el-col :span="24"><el-menu :default-active="1" class="el-menu-demo" mode="horizontal" background-color="#34495e" text-color="#fff" active-text-color="#ffd04b" @select="handleSelect">
      <el-menu-item index="1">航路查询</el-menu-item>
      <el-menu-item index="2">气象查询</el-menu-item>
    </el-menu></el-col>
    <el-col :span="24">
      <el-alert title="数据版本: " type="info" />
    </el-col>
  </el-row>
</template>

<script>
export default {
  name: 'RouteFinder'
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

blockquote {
  margin-top: 15px;
  margin-bottom: 10px;
  padding-left: 15px;
  padding-top: 10px;
  padding-right: 10px;
  padding-bottom: 10px;
  border-left: 3px solid #ccc;
  background-color: #f1f1f1
}
</style>
