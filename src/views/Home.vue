/* eslint-disable no-undef */
<template>
<!-- <Head /> -->
<div class="advantage">
  <el-container>
    <!-- <h2><span>我们能做什么？</span></h2> -->
    <el-row :gutter="10" class="advantage__list">
      <el-col :xs="12" :sm="12" :md="12" :lg="8" :xl="8" >
        <div class="grid-content bg-purple">
          <img src="../assets/img/chat.png" alt="">
          <h3>保护你的聊天内容</h3>
          <p>所有的聊天内容都可以加密 让聊天更放心</p>
          <span>立即体验</span>
        </div>
        </el-col>
      <el-col :xs="12" :sm="12" :md="12" :lg="8" :xl="8">
        <div class="grid-content bg-purple-light">
            <div class="grid-content bg-purple">
            <img src="../assets/img/chat.png" alt="">
            <h3>保护你的聊天内容</h3>
            <p>所有的聊天内容都可以加密 让聊天更放心</p>
            <span>立即体验</span>
          </div>
        </div>
        </el-col>
      <el-col :xs="12" :sm="12" :md="12" :lg="8" :xl="8">
        <div class="grid-content bg-purple-light">
            <div class="grid-content bg-purple">
            <img src="../assets/img/chat.png" alt="">
            <h3>保护你的聊天内容</h3>
            <p>所有的聊天内容都可以加密 让聊天更放心</p>
            <span>立即体验</span>
          </div>
        </div>
        </el-col>
        <el-col :xs="12" :sm="12" :md="12" :lg="8" :xl="8">
          <div class="grid-content bg-purple-light">
              <div class="grid-content bg-purple">
              <img src="../assets/img/chat.png" alt="">
              <h3>保护你的聊天内容</h3>
              <p>所有的聊天内容都可以加密 让聊天更放心</p>
              <span>立即体验</span>
            </div>
          </div>
        </el-col>
        <el-col :xs="12" :sm="12" :md="12" :lg="8" :xl="8">
          <div class="grid-content bg-purple-light">
              <div class="grid-content bg-purple">
              <img src="../assets/img/chat.png" alt="">
              <h3>保护你的聊天内容</h3>
              <p>所有的聊天内容都可以加密 让聊天更放心</p>
              <span>立即体验</span>
            </div>
          </div>
        </el-col>
        <el-col :xs="12" :sm="12" :md="12" :lg="8" :xl="8">
          <div class="grid-content bg-purple-light">
              <div class="grid-content bg-purple">
              <img src="../assets/img/chat.png" alt="">
              <h3>保护你的聊天内容</h3>
              <p>所有的聊天内容都可以加密 让聊天更放心</p>
              <span>立即体验</span>
            </div>
          </div>
        </el-col>
  </el-row>
  </el-container>
</div>
<div class="reason">
  <el-container>
    <el-row :gutter="10">
      <el-col :xs="24" :sm="24" :md="12" :lg="12" :xl="12" class="reason__left">
        <div class="grid-content bg-purple">
          <img src="../assets/img/pic01.png" alt="">
        </div>
      </el-col>
      <el-col :xs="24" :sm="24" :md="12" :lg="12" :xl="12" class="reason__right">
        <div class="grid-content bg-purple">
          <h3><span>为什么选我们？</span></h3>
          <p>AIM是一款专门为企业开发的聊天工具，功能包括聊天系统、通讯录信息提取、 个性圈子（内含语音、视频、图片、文件和文档展示等功能）、实时会议和语音。 我们的优势在于聊天内容可加密，阅后即焚功能，数据库由你掌控， 为贵公司的商业机密保驾护航。</p>
          <a href="">立即体验</a>
        </div>
      </el-col>
    </el-row>
  </el-container>
</div>
<div class="download">
  <el-container>
    <el-row :gutter="10">
      <el-col :xs="24" :sm="24" :md="12" :lg="12" :xl="12" class="download__left">
         <div class="grid-content bg-purple">
          <h3><span>沟通，是肆无忌惮地 畅所欲言？</span></h3>
          <p>AIM，有阅后即焚和聊天加密功能来保驾护航， 从此不再担心内部资料泄密，你的数据你掌控。</p>
          <div class="download__btn">
            <p>
              <span>2021-07-30</span>
              <a href="../assets/img/pic01.png"><img src="">下载</a>
            </p>
             <p>
              <span>2021-07-30</span>
              <a href=""><img src="">下载</a>
            </p>
          </div>
        </div>
      </el-col>
      <el-col :xs="24" :sm="24" :md="12" :lg="12" :xl="12" class="download__right">
        <div class="grid-content bg-purple">
          <img src="../assets/img/pic01.png" alt="">
        </div>
      </el-col>
    </el-row>
  </el-container>
</div>


</template>

<script>
// import Head from '../views/Head';

export default {
  name: 'Home',
  setup (){
    
  }
  
}
</script>

<style lang="scss" scoped>
.el-container {
    margin-right: auto;
    margin-left: auto;
}
.advantage{
  opacity: 1;
  position: relative;
  padding: 30px 0;
  color: #cdbfe3;
  text-align: center;
  background-color: #F7F8FB;
  background-repeat: repeat-x;
  &__list{
    // margin-top: 66px;
  }
  .grid-content{
    h3{
      font-size: 18px;
      font-family: PingFang SC;
      font-weight: 400;
      line-height: 27px;
      color: #1A47B0;
      opacity: 1;
      margin-top: 36px;
    }
    img{
      border:1px dashed #999;
    }
    p{
      font-size: 16px;
      font-family: PingFang SC;
      font-weight: 400;
      line-height: 21px;
      color: #595F6F;
      opacity: 1;
      margin-top: 8px;
    }
    span{
      width: 200px;
      height: 50px;
      background: #FA2851;
      box-shadow: 0px 6px 24px rgba(214, 14, 53, 0.3);
      opacity: 1;
      border-radius: 5px;
      display: inline-block;
      text-align: center;
      line-height: 50px;
      font-size: 16px;
      font-family: PingFang SC;
      font-weight: 400;
      color: #FFFFFF;
      opacity: 1;
      margin-top: 62px;
      display: none;
    }
  }
  .el-col{
    padding-left: 8% !important;
    padding-right: 8% !important;
    padding-top: 2%;
    padding-bottom: 2%;
  }
}
h2{
  width: 236px;
  height: 24px;
  background: linear-gradient(127deg, #24E8C7 0%, #24D4E8 100%);
  opacity: 0.5;
  border-radius: 2px;
  text-align:center;
  margin: auto;
  span{
    font-size: 32px;
    font-family: PingFang SC;
    font-weight: 600;
    line-height: 33px;
    color: #2C2F43;
    opacity: 1;
  }
}
.clear{
  clear: both;
}
.el-row{
  margin-right: auto !important;
  margin-left: auto !important;
}

.reason{
  opacity: 1;
  position: relative;
  padding: 30px 0;
  color: #cdbfe3;
  text-align: center;
  background-color: #fff;
  background-repeat: repeat-x;
  .grid-content img{
    max-width: 100%;
  }
  h3{
    width: 236px;
    height: 24px;
    background: linear-gradient(127deg, #24E8C7 0%, #24D4E8 100%);
    opacity: 0.5;
    border-radius: 2px;
    text-align:center;
    margin: auto;
    span{
      font-size: 32px;
      font-family: PingFang SC;
      font-weight: 600;
      line-height: 33px;
      color: #2C2F43;
      opacity: 1;
    }
  }
  p{
    font-size: 16px;
    font-family: PingFang SC;
    font-weight: 400;
    line-height: 30px;
    color: #595F6F;
    opacity: 1;
    margin-top: 64px;
  }
  a{
    display: inline-block;
    text-decoration:none;
    width: 200px;
    height: 50px;
    background: #FA2851;
    box-shadow: 0px 6px 24px rgba(214, 14, 53, 0.3);
    opacity: 1;
    border-radius: 5px;
    display: inline-block;
    text-align: center;
    line-height: 50px;
    font-size: 16px;
    font-family: PingFang SC;
    font-weight: 400;
    color: #FFFFFF;
    opacity: 1;
    bottom: 0;
    left: 0;
  }

}

.el-container {
  margin-right: auto;
  margin-left: auto;
}
@media (min-width: 768px) {
  .el-container {
    width: 750px;
  }
}
@media (min-width: 992px) {
  .el-container {
    width: 970px;
  }
  .reason .reason__right{
    position: relative;
  }
   .reason .reason__right a{
    position: absolute;
    bottom: 5px;
    left: 0;
  }
  .reason p{
    margin-top: 28px;
  }
  .reason .reason__right{
    position: relative;
    padding-left: 50px !important;
  }
   .reason .reason__right a{
    position: absolute;
    bottom: 5px;
    left: 50px;
  }
}
@media (min-width: 1200px) {
  .el-container {
    width: 1170px;
  }
  .reason .reason__right{
    position: relative;
    padding-left: 50px !important;
  }
   .reason .reason__right a{
    position: absolute;
    bottom: 5px;
    left: 50px;
  }
}
</style>