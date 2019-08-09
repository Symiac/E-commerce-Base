<template>
 <div class="home">
 <!-- <p>{{msg}}</p>-->

    <!-- 头部 -->
    <div class="header">
        <div class="logo">
             <img  src="./img/school.png" alt="电子商务logo" />
        </div>
        <div class="hright">
            <div class="linklist">
                <ul>
                    <button>反馈</button>
                    <button>登陆</button>
                </ul>
                
            </div>
             <div class="search">
                 <input type="text" value="关键字搜索"/>
                 <span>
                     <button>🔍搜索</button>
                 </span>
             </div>
        </div>
       
    </div>
    <!-- 导航条 -->
    <div class="menu">
                <ul>
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
    </div>
    <!--页面主体 -->
    <div class="content">
        <div class="left">公告通知栏</div>
        <div class="certens">电商时事</div>
        <div class="right">电商风采</div>
    </div>
    <!--页脚 -->
    <div class="footer">
        <p>电商基地@right</p>
    </div>

 </div>
</template>

<script type="text/ecmascript-6">
export default {
 data() {
 return {
     msg:"home",
 }
 },
 components: {

 }
}
</script>

<style scoped >
.home{
    margin: 0 0 0 0 ;
}
.header {
   position: relative;
    width: 100%;
  /*  background-color: rgb(118, 179, 196);*/
  /*  padding-top: 10px;
    padding-bottom: 10px;*/
    height: 80px;
    clear: left;
    /*border-bottom:  solid rgb(118, 179, 196);*/
    text-align: center;
		




}
.logo{
    float: left;
    display: block;
    margin-top: 20px;

}
.logo img{
    width: 60%;
    height:70%;
}
.hright{
    width: 300px;
    height: 100px;
    float: right;
    display: block;
}

button{
    margin:0 10px;
}
p{
       color: #FFFFFF;	
}
.menu{
    position:fixed;
    width: 100%;
    height: 50px;
    text-align:center;
    background:#8bb0d3;
    position: relative;
  /*  z-index: 9;*/
    margin: 0 0 0 0 ;
    clear: both;
}
.menu ul{
    width: 100%;
    margin: 0 0 0 0 ;
    padding:  0 0 0 0;
}


.menu ul li{
    list-style-type:none;       /* ul前面的点  */
    display: inline;
  
    
}

.menu ul li a {
    line-height:50px; 		    /* 选中的文字块的行高,选择跟导航栏高度一致即可  */
    text-decoration: none;      /* 去掉连接下划线  */
    font-size:20px;			    /* 字体大小 */
    color: #FFFFFF;			    /* 字体颜色 */
   padding: 10px;
}

.menu ul li a:hover {
    background-color: #7d9ebd;	/* 选中的文字块的颜色 */
}

.content{
    width: 80%;
    margin: 0 auto;
    height: auto;
    overflow: hidden;
    
}
.left{
    width: 25%;
    height: 550px;     /* 800px*/
    background-color: #e0e6c1;
    float: left;
}

.certens{
    width: 50%;
    height: 550px;
    background-color: #a4bfd8;
    float: left;
}

.right{
    width: 25%;
    height: 550px;
    background-color: #e0e6c1;
    float: right;
}


.footer {
position:fixed;
left:0px;
bottom:0px;
height:50px;
width:100%;
background:#7d9ebd;
}
</style>
