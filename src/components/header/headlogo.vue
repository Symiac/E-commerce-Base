<template>
 
         <!-- 头部 -->
<div class="headerlogo">
        <div class="logo">
             
             <img  src="../img/school.png" alt="电子商务logo" />

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

<style scoped>
.header {
   position: relative;
     
   
    width: 90%;
  /*  background-color: rgb(118, 179, 196);*/
  /*  padding-top: 10px;
    padding-bottom: 10px;*/
    height: 80px;
    clear: left;
    /*border-bottom:  solid rgb(118, 179, 196);*/
    text-align: center;
	background: antiquewhite;




}
.logo{
    float: left;
    margin-left:5%;
    display: block;
    margin-top: 20px;
 

}
.logo img{
   
    width: 100%;
    height:100%;
}
.hright{
    width: 300px;
    height: 100px;
    float: right;
    display: block;
    margin-top: 30px;
    margin-right: 5%;
}

input{
     margin:0 10px;
    border-radius: 30px;
}
button{
   
    margin:0 10px;
    border-radius: 30px;
}
.linklist{
    text-align: right;
    margin-bottom: 20px;
}
.search{
    text-align: right;
}

p{
       color: #FFFFFF;	
}
</style>
