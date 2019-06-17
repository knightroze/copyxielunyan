<template>
  <div class='NewsFocus'>
  <el-row style="top:10px;">
    <el-col span='17'>
      <i class='el-icon-news'></i>
      <span style="font-size:25px">焦点新闻</span>
      <span style="font-size:20px;color:#CCCCCC;">NewsFocus</span>
    </el-col>
    <el-col span='3'>
      <div style='height:35px;display:table-cell;;vertical-align:bottom;'>更多>></div>
    </el-col>
  </el-row>
  <el-divider></el-divider>
  <el-row>
    <el-col span='11'>
      <el-card body-style="padding:0px;">
        <el-image src='http://www.scu.edu.cn/__local/4/F9/22/0D6EAF30052FD9F16C839376C5E_AE339354_106D83.jpg'
        style='height:250px;'>
        </el-image>
        <p>中石化总经理马永生院士为我校师生作《为美好生活加油 为中华民族争气》专题报告</p>
      </el-card>
    </el-col>
    <el-col span='2'>
      <span style="color:white;">1</span>
    </el-col>
    <el-col span='11'>
      <el-card  body-style="padding:0px;">
        <el-image src='http://www.scu.edu.cn/__local/9/AF/4D/1EEFAA3774576A40A3F5D7DE6C9_B42CB873_32220.jpg'
        style='height:250px;'>
        </el-image>
        <p>学校召开第五届全球青年学者论坛 面向全球招揽“熊猫人才”</p>
      </el-card>
    </el-col>
  </el-row>
  <el-row style="top:40px;">
    <el-col span='11'>
        <p>国家重大科研仪器研制项目————“深部岩石原位保真取芯与保真测试分析系统”项...</p>
    </el-col>
    <el-col span='2'>
      <span style="color:white;">1</span>
    </el-col>
    <el-col span='11'>
        <p>2019年转化医学国家重大科技基础设施联盟会议在我校召开</p>
    </el-col>
  </el-row>
  </div>
</template>

<script>
export default {
  name: 'NewsFocus',
  data () {
    return {

    }
  }
}
</script>

<style>

</style>
