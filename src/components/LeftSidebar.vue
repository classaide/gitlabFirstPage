<template>
<div id="sidebar">
    <el-col :span="4">
    <h5>服务器快速导航</h5>
    <el-menu mode="vertical" default-active="1" class="el-menu-vertical-demo">
      <el-menu-item-group title="持续集成">
        <el-menu-item index="1"><i class="el-icon-message"></i>Gitlab代码管理</el-menu-item>
        <el-menu-item index="2"><i class="el-icon-message"></i>导航二</el-menu-item>
      </el-menu-item-group>
      <el-menu-item-group title="分组二">
        <el-menu-item index="3"><i class="el-icon-message"></i>导航三</el-menu-item>
        <el-menu-item index="4"><i class="el-icon-message"></i>导航四</el-menu-item>
      </el-menu-item-group>
    </el-menu>
  </el-col>
</div>
</template>

<script>
    export default {
    name: 'leftsidebar',
    data (){
      
    }
  }
</script>