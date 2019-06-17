<template>
  <div class='lunbotu'>
    <el-row height='400px'>
      <el-col span='2'>
<span style="color:#E9E9E9;">1</span>
      </el-col>
      <el-col span='20'>
    <el-carousel arrow='always' height="350px">
      <el-carousel-item v-for="onesrc in srcList" :key="onesrc">
        <el-image :src='onesrc' fit='scale-down'></el-image>
      </el-carousel-item>
    </el-carousel>
    </el-col>
    <el-col span='2'>
<span  style="color:#E9E9E9;">1</span>
    </el-col>
  </el-row>
  </div>
</template>

<script>
export default{
  name: 'lunbotu',
  data () {
    return {
      srcList:
       ['http://www.scu.edu.cn/__local/8/C9/E3/5E44443C0214B62393986EFA7C1_824F5F00_3B1E7.jpg',
         'http://www.scu.edu.cn/__local/0/6B/8D/98B889E77CEABFA1D2CA68B623F_39D07EE5_B11FD.jpg',
         'http://www.scu.edu.cn/__local/0/06/DA/A8457A04E5577143D02A85D6EDE_07D919C0_4F11C.jpg',
         'http://www.scu.edu.cn/__local/3/C0/F6/2AD38F8BE37B51FFAFF007F0435_60236AE7_18A6A.jpg',
         'http://www.scu.edu.cn/__local/0/C9/17/48EC5B421F6852B5F7ABF2D304D_881B2DCE_58CCA.jpg',
         'http://www.scu.edu.cn/__local/1/A8/2E/12FEC4FD7E83E9548FAC7A2B344_FC3DCDB9_22E7A.jpg']
    }
  }
}
</script>

<style>
.lunbotu{

}
.lunbotu .el-row {
    background-color: #E9E9E9;
}
.el-carousel {
}
.el-carousel-item {
}
</style>
