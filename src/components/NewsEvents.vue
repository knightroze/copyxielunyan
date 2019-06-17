<template>
  <div class='NewsEvents'>
  <el-row>
    <el-col span='16'>
      <i class='el-icon-news'></i>
      <span style="font-size:25px">综合新闻</span>
      <span style="font-size:20px;color:#CCCCCC;">News Events</span>
    </el-col>
    <el-col span='8'>
      <div style='height:35px;display:table-cell;;vertical-align:bottom;'>更多>> 进入新闻网</div>
    </el-col>
  </el-row>
  <el-divider></el-divider>
  <el-row v-for="item in items" :key="item">
    <el-col v-html='item'></el-col>
    <el-col><br></el-col>
  </el-row>
  </div>
</template>

<script>
export default {
  name: 'NewsEvents',
  data () {
    return {
      items: [
        '<div><div style="float:left">川大学子在第十五届“挑战杯”...</div><div style="color:#7F7F7F;float:right;">2019-06-12</div></div>',
        '<div><div style="float:left">牛津大学肿瘤中心主任Mark R. Middleton..</div><div style="color:#7F7F7F;float:right;">2019-06-13</div></div>',
        '<div><div style="float:left">川大校友李坦荣登福布斯中国科技女性榜单</div><div style="color:#7F7F7F;float:right;">2019-06-09</div></div>',
        '<div><div style="float:left">外国语学院学子在全国大学生英语辩论..</div><div style="color:#7F7F7F;float:right;">2019-06-13</div></div>',
        '<div><div style="float:left">【梦想从川大起航】2019届毕业生：不...</div><div style="color:#7F7F7F;float:right;">2019-06-09</div></div>',
        '<div><div style="float:left">【梦想从川大起航】吴易阳：从匹兹堡...</div><div style="color:#7F7F7F;float:right;">2019-06-11</div></div>',
        '<div><div style="float:left">“继往开来：新中国史学发展的回顾与...</div><div style="color:#7F7F7F;float:right;">2019-06-12</div></div>',
        '<div><div style="float:left">学校举行“中华诵•庆祝新中国成立70...</div><div style="color:#7F7F7F;float:right;">2019-06-11</div></div>',
        '<div><div style="float:left">华西第二医院医学模拟中心揭牌</div><div style="color:#7F7F7F;float:right;">2019-06-10</div></div>',
        '<div><div style="float:left">华西医院在非洲圣普建立国际网络...</div><div style="color:#7F7F7F;float:right;">2019-06-09</div></div>',
        '<div><div style="float:left">外国语学院学子在全国大学生英语...</div><div style="color:#7F7F7F;float:right;">2019-06-09</div></div>'
      ]
    }
  }
}
</script>

<style>
</style>
