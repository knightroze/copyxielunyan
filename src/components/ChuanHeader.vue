<template>
  <div class="ChuanHeader">
    <el-row class="outone">
      <el-col :span="6">
        <el-image :src="urlchuan"></el-image>
      </el-col>
      <el-col :span="5" :offset="8">
        <el-row class="inone">
          <el-col :span="6" :offset="6">信息公开</el-col>
          <el-col :span="6">投稿系统</el-col>
          <el-col :span="6">ENGLISH</el-col>
        </el-row>
        <el-row class="inone">
          <el-col :span="6" :offset="6">信息门户</el-col>
          <el-col :span="6">办公服务</el-col>
          <el-col :span="6">邮件系统</el-col>
        </el-row>
      </el-col>
      <el-col :span="5">
        <span class="fangdajing"></span>
        <el-divider direction="vertical"></el-divider>
        <el-image :src="urlsearch" style="top:7px;left:10px;"></el-image>
      </el-col>
    </el-row>
  </div>
</template>

<script>//
export default {
  name: 'ChuanHeader',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App',
      urlchuan: 'http://www.scu.edu.cn/images/logo.png',
      urlsearch: 'http://www.scu.edu.cn/images/search.png'
    }
  }
}
</script>

<style>
.ChuanHeader {
  background-color : #BA2A17;
}
.ChuanHeader .outone {
  background-image: url('http://www.scu.edu.cn/images/top-bg.png');
  height: 100px;
  left:120px;
}
.ChuanHeader .inone {
  color: white;
}
.ChuanHeader .el-col {
  margin-top: 10px;
}
.ChuanHeader .fangdajing {
  font-size: 40px;
}
.ChuanHeader .el-divider {
  height: 40px;
}
</style>
