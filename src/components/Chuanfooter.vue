<template>
  <div class="Chuanfooter" style="background-color:#333333;padding-top:50px;color:#999999;height:300px;">
<el-row>
  <el-col span='5' offset='2'>
    <div class='footerone' style='margin-left:50px;'>
      <div>
        <span>校内链接</span>
        <span>友情链接</span>
      </div>
      <br>
      <div>
        <el-image src='http://www.scu.edu.cn/images/icons/ft_wb.png'></el-image>
        <el-image src='http://www.scu.edu.cn/images/icons/ft_wx.png'></el-image>
        <el-image src='http://www.scu.edu.cn/images/icons/ft_vd.png'></el-image>
        <el-image src='http://www.scu.edu.cn/images/icons/ft_vr.png'></el-image>
      </div>
    </div>
  </el-col>
  <el-col span='1'>
    <div class="vdivider">
    <el-divider direction="vertical"></el-divider>
  </div>
  </el-col>
  <el-col span='8'>
    <div class='footertwo'>
      <el-image src='http://www.scu.edu.cn/images/footer-logo.png'></el-image>
    </div>
  </el-col>
  <el-col span='1'>
    <el-divider direction="vertical"></el-divider>
  </el-col>
  <el-col span='5'>
    <div class="footerthree" style="font-size:18px;line-height:2">
      <el-row class="inone">
        <el-col :span="6" :offset="4">信息公开</el-col>
        <el-col :span="6">投稿系统</el-col>
        <el-col :span="6">ENGLISH</el-col>
      </el-row>
      <el-row class="inone">
        <el-col :span="6" :offset="4">信息门户</el-col>
        <el-col :span="6">办公服务</el-col>
        <el-col :span="6">邮件系统</el-col>
      </el-row>
    </div>
  </el-col>
</el-row>
<el-divider></el-divider>
<el-row>
  <el-col span='7' offset='1'>
    <div class='footerfour' style='margin-left:50px;color=#999999;line-height:2'>
      <div>
        （望江校区）成都市一环路南一段24号 邮编：610065
        （华西校区）成都市人民南路三段17号 邮编：610041
        （江安校区）成都市双流区川大路 邮编：610207
      </div>
    </div>
  </el-col>
  <el-col span='8'>
    <div class='footerfive' style='margin-left:50px;color=#999999;line-height:2'>
      Copyright©2002-2018四川大学版权所有
      <br>
      蜀ICP备05006382号
      <br>
      访问量： 119797644
    </div>
  </el-col>
  <el-col span='5'>
    <div class="footersix" style="font-size:18px;line-height:2">
      <el-input v-model="input" placeholder="请输入查询内容" suffix-icon="el-icon-search"></el-input>
    </div>
  </el-col>
</el-row>
  </div>
</template>

<script>//
export default {
  name: 'Chuanfooter',
  data () {
    return {
    }
  }
}
</script>

<style>
.Chuanfooter .el-row .el-divider{
  height: 90px;
}
.el-input{
  background-color: #999999;
}
</style>
