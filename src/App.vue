<template>
  <div id="app">
    <ChuanHeader></ChuanHeader>
    <MyMenu></MyMenu>
    <lunbotu></lunbotu>
    <div style="margin:0px;height:550px;">
      <el-row>
      <el-col span='2'>
        <span style="color:white;">1</span>
      </el-col>
      <el-col span='12'>
        <NewsFocus></NewsFocus>
      </el-col>
      <el-col span='1'>
        <span style="color:white;">1</span>
      </el-col>
      <el-col span='7'>
      <NewsEvents></NewsEvents>
      </el-col>
      <el-col span='2'>
        <span style="color:white;">1</span>
      </el-col>
      </el-row>
    </div>
  <div style="height:300px;">
    <el-row>
      <el-col span='2'>
        <br>
      </el-col>
      <el-col span='20'>
    <biaoqianye></biaoqianye>
    </el-col>
    <el-col span='2'>
      <br>
    </el-col>
  </el-row>
  </div>
  <div>
    <el-row>
      <el-col span='2'>
        <br>
      </el-col>
      <el-col span='22'>
  <imagewall></imagewall>
      </el-col>
</el-row>
</div>
<div style="margin-top:30px;margin-bottom:30px;">
  <el-row>
    <el-col span='2'>
      <br>
    </el-col>
    <el-col span='20'>
  <baichuanjiangtan></baichuanjiangtan>
    </el-col>
    <el-col span='2'>
      <br>
    </el-col>
  </el-row>
</div>

<div style="margin:0px;height:600px;">
  <el-row>
  <el-col span='2'>
    <span style="color:white;">1</span>
  </el-col>
  <el-col span='12'>
    <radd></radd>
  </el-col>
  <el-col span='1'>
    <span style="color:white;">1</span>
  </el-col>
  <el-col span='7'>
  <cdrw></cdrw>
  </el-col>
  <el-col span='2'>
    <span style="color:white;">1</span>
  </el-col>
  </el-row>
</div>
<imagewallex></imagewallex>
<br><br>
<div style="margin:0px;height:550px;">
  <el-row>
  <el-col span='2'>
    <span style="color:white;">1</span>
  </el-col>
  <el-col span='7'>
    <videoos></videoos>
  </el-col>
  <el-col span='1'>
    <span style="color:white;">1</span>
  </el-col>
  <el-col span='12'>
  <newmedia></newmedia>
  </el-col>
  <el-col span='2'>
    <span style="color:white;">1</span>
  </el-col>
  </el-row>
</div>
<Chuanfooter></Chuanfooter>
  </div>
</template>

<script>
import ChuanHeader from '@/components/ChuanHeader'
import MyMenu from '@/components/menu'
import lunbotu from '@/components/lunbotu'
import NewsFocus from '@/components/NewsFocus'
import NewsEvents from '@/components/NewsEvents'
import biaoqianye from '@/components/biaoqianye'
import imagewall from '@/components/imagewall'
import baichuanjiangtan from '@/components/baichuanjiangtan'
import radd from '@/components/radd'
import cdrw from '@/components/cdrw'
import imagewallex from '@/components/imagewallex'
import videoos from '@/components/videoos'
import newmedia from '@/components/newmedia'
import Chuanfooter from '@/components/Chuanfooter'

export default {
  name: 'App',
  components: {
    ChuanHeader,
    MyMenu,
    lunbotu,
    NewsFocus,
    NewsEvents,
    biaoqianye,
    imagewall,
    baichuanjiangtan,
    radd,
    cdrw,
    imagewallex,
    videoos,
    newmedia,
    Chuanfooter
  }
}
</script>

<style>
*{
  margin:0;
  padding:0;
}
#app {
  margin-top: 0;
  width:100%;
  height:100%;
}
</style>
