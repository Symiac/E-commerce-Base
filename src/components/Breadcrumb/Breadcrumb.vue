<template>
 <div class="Breadcrumb">
    <el-breadcrumb separator="/">
     <el-breadcrumb-item :to="{ path: '/' }">首页</el-breadcrumb-item>
     <el-breadcrumb-item><a href="/">标题一</a></el-breadcrumb-item>
     <el-breadcrumb-item>子页面</el-breadcrumb-item>
   <!--  <el-breadcrumb-item>活动详情</el-breadcrumb-item> -->
    </el-breadcrumb>
 
 </div>
</template>

<script type="text/ecmascript-6">
export default {
 data() {
 return {

 }
 },
 components: {

 }
}
</script>

<style scoped >
.Breadcrumb{
    width: 100%;
    margin-top:10px;
    height: 40px;
    text-align: left;
    padding-left: 70px;
    font-size: 13px;
}
</style>
