<template>
  <div class="MyMenu">
    <el-row>
      <el-col span="1" :offset="3">
        <el-image :src='url'></el-image>
      </el-col>
      <el-col span="20">
      <el-menu mode='horizontal' text-color='#000'>
      <el-submenu index='2'>
        <template slot="title">学校概况</template>
        <el-menu-item index="2-1">学校简介</el-menu-item>
        <el-menu-item index="2-2">历史沿革</el-menu-item>
        <el-menu-item index="2-3">领导架构</el-menu-item>
        <el-menu-item index="2-4">川大标识</el-menu-item>
      </el-submenu>
      <el-submenu index='3'>
        <template slot="title">新闻资讯</template>
        <el-menu-item index="3-1">川大新闻网</el-menu-item>
        <el-menu-item index="3-2">川大教育电视台</el-menu-item>
        <el-menu-item index="3-3">川大校报</el-menu-item>
        <el-menu-item index="3-4">川大官方微博</el-menu-item>
        <el-menu-item index="3-5">川大官方微信</el-menu-item>
        <el-menu-item index="3-6">川大官方微视</el-menu-item>
        <el-menu-item index="3-7">川大新媒体联盟</el-menu-item>
        <el-menu-item index="3-8">Newseltter</el-menu-item>
      </el-submenu>
      <el-submenu index='4'>
        <template slot="title">教育教学</template>
        <el-menu-item index="4-1">人才培养概况</el-menu-item>
        <el-menu-item index="4-2">本科生教学</el-menu-item>
        <el-menu-item index="4-3">研究生教学</el-menu-item>
        <el-menu-item index="4-4">留学生教育</el-menu-item>
        <el-menu-item index="4-5">成人职业教育</el-menu-item>
        <el-menu-item index="4-6">远程网络教育</el-menu-item>
        <el-menu-item index="4-7">出国预科教育</el-menu-item>
        <el-menu-item index="4-8">干部教育</el-menu-item>
        <el-menu-item index="4-9">课程教学资源</el-menu-item>
      </el-submenu>
      <el-submenu index='5'>
        <template slot="title">科学研究</template>
        <el-menu-item index="5-1">科学研究概况</el-menu-item>
        <el-menu-item index="5-2">科研平台</el-menu-item>
        <el-menu-item index="5-3">学科建设</el-menu-item>
        <el-menu-item index="5-4">人文社科</el-menu-item>
        <el-menu-item index="5-5">理学、工程与医学</el-menu-item>
        <el-menu-item index="5-6">实验室与研究基地</el-menu-item>
        <el-menu-item index="5-7">仪器设备开放共享</el-menu-item>
        <el-menu-item index="5-8">科研成果</el-menu-item>
        <el-menu-item index="5-9">科技产业</el-menu-item>
      </el-submenu>
      <el-submenu index='6'>
        <template slot="title">师资队伍</template>
        <el-menu-item index="6-1">师资队伍概况</el-menu-item>
        <el-menu-item index="6-2">两院院士</el-menu-item>
        <el-menu-item index="6-3">四川大学杰出教授</el-menu-item>
        <el-menu-item index="6-4">长江学者</el-menu-item>
        <el-menu-item index="6-5">高校教学名师奖获得者</el-menu-item>
        <el-menu-item index="6-6">国家杰出青年基金获得者</el-menu-item>
        <el-menu-item index="6-7">各类杰出人才</el-menu-item>
      </el-submenu>
      <el-submenu index='7'>
        <template slot="title">交流合作</template>
        <el-menu-item index="7-1">交流合作概况</el-menu-item>
        <el-menu-item index="7-2">国际交流</el-menu-item>
        <el-menu-item index="7-3">海外教育</el-menu-item>
        <el-menu-item index="7-4">出国培训</el-menu-item>
        <el-menu-item index="7-5">公派研究生信息</el-menu-item>
        <el-menu-item index="7-6">大川视界访学平台</el-menu-item>
        <el-menu-item index="7-7">中俄“长江——伏尔加”</el-menu-item>
      </el-submenu>
      <el-submenu index='8'>
        <template slot="title">招生就业</template>
        <el-menu-item index="8-1">招生就业概况</el-menu-item>
        <el-menu-item index="8-2">本科招生网</el-menu-item>
        <el-menu-item index="8-3">研究生招生信息在线</el-menu-item>
        <el-menu-item index="8-4">毕业生就业网</el-menu-item>
        <el-menu-item index="8-5">留学生招生信息</el-menu-item>
        <el-menu-item index="8-6">成人职业教育</el-menu-item>
        <el-menu-item index="8-7">远程网络教育</el-menu-item>
        <el-menu-item index="8-8">出国预科教育</el-menu-item>
        <el-menu-item index="8-9">外国培训</el-menu-item>
      </el-submenu>
      <el-submenu index='9'>
        <template slot="title">机构设置</template>
        <el-menu-item index="9-1">机关部处</el-menu-item>
        <el-menu-item index="9-2">学院设置</el-menu-item>
        <el-menu-item index="9-3">业务管理和办学实体单位</el-menu-item>
      </el-submenu>
      <el-submenu index='10'>
        <template slot="title">文化资源</template>
        <el-menu-item index="10-1">馆藏资源概况</el-menu-item>
        <el-menu-item index="10-2">图书馆</el-menu-item>
        <el-menu-item index="10-3">人文博物馆</el-menu-item>
        <el-menu-item index="10-4">自然博物馆</el-menu-item>
        <el-menu-item index="10-5">档案馆 校史展览馆</el-menu-item>
        <el-menu-item index="10-6">中国口腔医学博物馆</el-menu-item>
        <el-menu-item index="10-7">华西医学展览馆</el-menu-item>
        <el-menu-item index="10-8">风光人文</el-menu-item>
      </el-submenu>
      </el-menu>
      </el-col>
    </el-row>
  </div>
</template>

<script>
export default{
  name: 'menu',
  data () {
    return {
      url: 'http://www.scu.edu.cn/images/nav-home.png'
    }
  }
}
</script>

<style>
.MyMenu {
}
.MyMenu .el-image {
  top:15px;
}
.MyMenu .el-col {
}
.MyMenu .el-menu{
}
.MyMenu .el-submenu{
}
.MyMenu .el-menu-item:hover {
}
.MyMenu .template {
}

</style>
