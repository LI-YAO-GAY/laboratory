<template>
 <div>
  <div class="container">
  <div class="box flex">
    <div class="left flex a-center">
     <div ><i class="iconfont icon-ai238 color-fff F20 m-l-15"></i></div>
     <div class="F20 color-fff">全部课程</div>
    </div>
    <div class="right flex a-center relative">
    <div class="r-left flex">
    <div class="F18 p-r-20 p-l-20 font">路径</div>
    <div class="F18 p-r-20 p-l-20 font">训练营</div>
    <div class="F18 p-r-20 p-l-20 font">楼+</div>
    <div class="F18 p-r-20 p-l-20 font">会员</div>
    <div class="r-img absolute"><img src="../../../../../image/hot.svg" alt=""></div>
    <div class="F18 p-r-20 p-l-20 font">社区
     <i class="iconfont icon-xiajiantou F20 relative"></i>
     </div>
    </div>
    <div class="r-right flex absolute a-center">
    <input type="text" placeholder="搜索 课程/问答">
    <div> <i class="iconfont icon-fangdajing F20 relative"></i></div>
    </div>
    </div>
  </div>
   
  </div>
  <div class="select bg-fff">
     <div class="bot-font">讨论</div>
     <div class="bot-font">教程库</div>
     <div class="bot-font">直播</div>
     <div class="bot-font">比赛</div>
     </div>
 </div>
</template>

<script>
 export default {
   name: '',
   props: {
   },
   components: {

   },
   data () {
     return {

     }
   },
   methods: {

   },
   mounted() {

   },
   watch: {

   },
   computed: {

   }
 }
</script>

<style scoped lang='scss'>
.left{
  width: 328px;
  height: 80px;
  background: rgb(8,191,145);
}
.font{
   &:hover{
    cursor: pointer;
    color: rgb(8,191,158);
  }
}
input{
  border:none;
  outline: none;
  border-radius: 5px;
  border: 1px solid #ccc;
  height: 30px;
  width: 250px;
}
.right {
  width: 1072px;
}
.r-right{
  right: 40px;
   &:hover{
     border-radius: 5px;
     border: 1px solid rgb(8,191,158);
  }
}
.r-img{
  top:10px;
  left:305px;
}
.icon-fangdajing{
  right: 30px;
}
.select{
  width: 188px;
  height: 272px;
  top:20px;
  height: 20px;
}
.bot-font{
  margin: 10px;
  &:hover{
    cursor: pointer;
    color: rgb(8,191,158);
  }
}
.icon-xiajiantou:hover ~ .select{
 display: block;
}
</style>