<template>
     <!-- 导航条 -->
<div class="menu">
               <!-- <ul>
                    <li> <a href="">标题一</a> </li>
                    <li> <a href="">标题二</a> </li>
                    <li> <a href="">标题三</a> </li>
                    <li> <a href="">标题四</a> </li>
                    <li> <a href="">标题五</a> </li>
                    <li> <a href="">标题六</a> </li>
                    <li> <a href="">标题七</a> </li>
                    <li> <a href="">标题八</a> </li> 
                     <li> <a href="">标题九</a> </li>  
                
                </ul>
    -->
  <!-- 
    <el-tabs v-model="activeName" @tab-click="handleClick">
    <el-tab-pane label="首页" name="first"></el-tab-pane>
    <el-tab-pane label="标签一" name="second"></el-tab-pane>
    <el-tab-pane label="标签二" name="third"></el-tab-pane>
    <el-tab-pane label="标签三" name="fourth"></el-tab-pane>
  </el-tabs>-->

  <el-menu :default-active="activeIndex" class="el-menu-demo" mode="horizontal"
   @select="handleSelect" text-color="#fff" background-color="#708ca8"   active-text-color="black">
  <el-menu-item index="1"> 
      首页
    </el-menu-item>
  <el-menu-item index="2">标签2</el-menu-item>
  <el-menu-item index="3">标签3</el-menu-item>
  <el-menu-item index="4">标签4</el-menu-item>
   <el-menu-item index="5">标签5</el-menu-item>
    <el-menu-item index="6">标签6</el-menu-item>
     <el-menu-item index="7">标签7</el-menu-item>
      
 
  </el-menu>


 </div>
</template>

<script type="text/ecmascript-6">
export default {
 data() {
      return {
      //  activeName: 'second'
      };
    },
    methods: {
    /*  handleClick(tab, event) {
         console.log(tab, event);
      }*/
    }
  };
</script>

<style scoped>

.menu{
   
    margin-top:70px;
    width: 90%;
    height: 50px;
    text-align:center;
  /*  background-color:black;*/
    position: relative;
  /*  z-index: 9;*/
    margin: 0 0 0 0 ;
    clear: both;
    display: block;
    margin:0 auto;
    font-size: 30px;
    font-weight:bold;
}

.el-menu{
    
    text-align: center;
}
.el-menu-item {
    
    font-size:16px;
    
}
/*
.menu ul{
    width: 100%;
    margin: 0 0 0 0 ;
    padding:  0 0 0 0;
}
*/
/*
.menu ul li{
    list-style-type:none;       /* ul前面的点  */
 /*   display: inline;
  
    
}

.menu ul li a {
    line-height:50px; 		    /* 选中的文字块的行高,选择跟导航栏高度一致即可  */
 /*   text-decoration: none;      /* 去掉连接下划线  */
  /*  font-size:20px;			    /* 字体大小 */
   /* color: #FFFFFF;			    /* 字体颜色 */
/*   padding: 10px;
}

.menu ul li a:hover {
    background-color: #7d9ebd;	/* 选中的文字块的颜色 */
/*}
*/
</style>
