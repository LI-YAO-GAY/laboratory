<template>
 <div>
  <div class="container">
  <div class="box">
  <div class="top flex a-center j-between">
   <div class="t-left flex a-center">
   <div class="top-logo"><img src="../../../../../image/9f43b00.svg" alt=""></div>
   <div class="l-font F20">做实验，学编程</div>
   </div>
   <div class="t-right flex">
   <div class="top-item flex a-center">
   <div class="font">企业版</div>
   <div class="line m-lr-10"></div>
   <div class="font">学校版</div>
   <div class="font-b m-lr-20">登陆</div>
   <div class="register t-align-c color-fff">注册</div>
   </div>
   </div>
  </div>
  </div>
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
.box,.container{
  background: rgb(249,249,249);
}
.top{
  height: 114px;
}
.top-logo{
  width: 120px;
  &:hover{
    cursor: pointer;
  }
}
.font{
  color:rgb(153,165,192);
   &:hover{
    cursor: pointer;
    color: rgb(8,191,158);
  }
}
.l-font{
  color: rgb(78,95,109);
}
.font-b{
  color: rgb(8,191,158);
  &:hover{
    color: rgb(5,118,89);
  }
}
.line{
  width: 1px;
  height: 16px;
  background:rgb(78,95,109);
}
.register{
  background: rgb(8,191,145);
  width: 100px;
  height: 60px;
  line-height: 60px;
}
</style>