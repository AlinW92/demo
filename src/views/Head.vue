<template>
  <el-container>
    <el-header>
      <el-menu>
        <el-menu-item class="logo" index="0" route="/home">
          <img class="logoimg" src="../assets/img/logo.png" alt="logo" />
          <span>AIM APP</span>
        </el-menu-item>
        <el-menu-item>
          <ul>
            <li><a href="">首页</a></li>
            <li><a href="">下载手机版</a></li>
            <li><a href="">下载PC版</a></li>
            <li><a href="">联系我们</a></li>
          </ul>
        </el-menu-item>
      </el-menu>   
    </el-header>
    <el-main>Main</el-main>
</el-container>
</template>

<script>

export default {
  name: 'Home',
  setup () {
   
  }
}
</script>

<style lang="scss" scoped>
@import '../style/base.scss';

.el-container {
  background: url(../assets/img/header_bg.png) 100% 100%;
  .el-menu{
    background-color:transparent;
    border-right:none;
  }
  .el-menu-item{
      float: left;
  }
}
</style>