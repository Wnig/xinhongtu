<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
// import './font/style.css'
export default {
  name: 'App',
  components: {

  }
}
</script>

<style>
  /* CSS reset */
  html{color:#000;background:#fff;-webkit-tap-highlight-color:rgba(0,0,0,0);font-family: 'PingFangSC-Thin',"Microsoft YaHei","微软雅黑","sans-serif";font-size: 12px;}
  body,div,dl,dt,dd,ul,ol,li,h1,h2,h3,h4,form,input,button,textarea,p,th,td,strong{padding:0;margin:0;font-family: 'PingFangSC-Thin',"Microsoft YaHei","微软雅黑","sans-serif";}
  table{border-collapse:collapse;border-spacing:0;}
  img{border:0;}
  a{text-decoration:none; color:#999; outline:none;}/*此处待添加默认链接颜色*/
  var,em,strong{font-style:normal;}
  em,strong,th,var{font-style:inherit;font-weight:inherit;}
  li{list-style:none;}
  caption,th{text-align:left;}
  h1,h2,h3,h4{font-size:100%;font-weight:normal;}
  input,button,textarea,select,option{font-family:inherit; font-size:inherit;font-style:inherit;font-weight:inherit;}
  input,button,textarea,select{*font-size:100%;}
  .clearfix:after {content:"\200B"; display:block; height:0; clear:both; }
  .clearfix { *zoom:1; }

  html {
    position: relative;
    width: 100%;
    overflow: hidden;
    overflow-y: scroll;
  }
  #app {
  }
  .pc {
    width: 100%;
    overflow: hidden;
  }
  .selection {
    position: relative;
    width: 100%;
    height: 100vh;
    overflow: hidden;
  }
  
  .down-con {
    overflow: hidden;
    display: flex;
    justify-content: center;
    align-items: center;
    position: absolute;
    left: 0;
    right: 0;
    margin: 0 auto;
    width: 100%;
    bottom: 8.7vh;
    width: 3.65vw;
    height: 3.65vw;
    background: url('../src/assets/5.svg') center center no-repeat;
    background-size: 100% 100%;
    cursor: pointer;
  }
  .down-con:after {
    position: absolute;
    left: 0;
    top: 0;
    content: '';
    width: 99%;
    height: 101%;
    background: url('../src/assets/7.svg') center center no-repeat;
    background-size: 100% 100%;
    -webkit-animation: rotate 2.2s infinite ease-in-out;
    animation: rotate 2.2s infinite ease-in-out;
  }
  .down {
    overflow: hidden;
    position: relative;
    width: 3.3vw;
    height: 3.3vw;
    border-radius: 50%;
  }
  .down:after {
    position: absolute;
    left: 0;
    right: 0;
    bottom: 0;
    top: 1.6vh;
    margin: 0 auto;
    content: '';
    width: 1.93vw;
    height: 1.93vw;
    background: url('../src/assets/6.svg') center center no-repeat;
    background-size: 100% 100%;
    cursor: pointer;
    -webkit-animation: fall 1.2s infinite;
    animation: fall 1.2s infinite;
  }

  .title {
    position: relative;
    color: #000;
    text-align: left;
    font-size: 1.82vw;
    font-family: 'PingFangSC-Semibold';
  }
  
  .title:after {
    content: "";
    position: absolute;
    bottom: -2.5vh;
    left: 0;
    width: 1.88vw;
    height: 0.16vw;
    background: #5BB8DE;
  }

  .mob {
    display: none;
  }

  /*向下效果*/
  @-webkit-keyframes fall {
    0% {
      -webkit-transform: translateY(-10px);
      -moz-transform: translateY(-10px);
      -ms-transform: translateY(-10px);
      -o-transform: translateY(-10px);
    }
    60% {
      -webkit-transform: translateY(15px);
      -moz-transform: translateY(15px);
      -ms-transform: translateY(15px);
      -o-transform: translateY(15px);
    }
    100% {
      -webkit-transform: translateY(-10px);
      -moz-transform: translateY(-10px);
      -ms-transform: translateY(-10px);
      -o-transform: translateY(-10px);
    }
  }
  @keyframes fall {
    0% {
      -webkit-transform: translateY(-10px);
      -moz-transform: translateY(-10px);
      -ms-transform: translateY(-10px);
      -o-transform: translateY(-10px);
    }
    60% {
      -webkit-transform: translateY(15px);
      -moz-transform: translateY(15px);
      -ms-transform: translateY(15px);
      -o-transform: translateY(15px);
    }
    100% {
      -webkit-transform: translateY(-10px);
      -moz-transform: translateY(-10px);
      -ms-transform: translateY(-10px);
      -o-transform: translateY(-10px);
    }
  }
  
  /*第一屏圆圈360旋转*/
  @-webkit-keyframes rotate {
    0% {
      -webkit-transform: rotate(0deg);
      -moz-transform: rotate(0deg);
      -ms-transform: rotate(0deg);
      -o-transform: rotate(0deg);
    }
    60% {
      -webkit-transform: rotate(180deg);
      -moz-transform: rotate(180deg);
      -ms-transform: rotate(180deg);
      -o-transform: rotate(180deg);
    }
    100% {
      -webkit-transform: rotate(360deg);
      -moz-transform: rotate(360deg);
      -ms-transform: rotate(360deg);
      -o-transform: rotate(360deg);
    }
  }
  @keyframes rotate {
    0% {
      -webkit-transform: rotate(0deg);
      -moz-transform: rotate(0deg);
      -ms-transform: rotate(0deg);
      -o-transform: rotate(0deg);
    }
    60% {
      -webkit-transform: rotate(180deg);
      -moz-transform: rotate(180deg);
      -ms-transform: rotate(180deg);
      -o-transform: rotate(180deg);
    }
    100% {
      -webkit-transform: rotate(360deg);
      -moz-transform: rotate(360deg);
      -ms-transform: rotate(360deg);
      -o-transform: rotate(360deg);
    }
  }

  /*漂浮*/
  @-webkit-keyframes opac {
    0% {
      opacity: 1;
      -webkit-transform: translateY(-10px);
      -moz-transform: translateY(-10px);
      -ms-transform: translateY(-10px);
      -o-transform: translateY(-10px);
    }
    50% {
      opacity: 1;
      -webkit-transform: translateY(0px);
      -moz-transform: translateY(0px);
      -ms-transform: translateY(0px);
      -o-transform: translateY(0px);
    }
    100% {
      opacity: 1;
      -webkit-transform: translateY(-10px);
      -moz-transform: translateY(-10px);
      -ms-transform: translateY(-10px);
      -o-transform: translateY(-10px);
    }
  }
  @keyframes opac {
    0% {
      opacity: 1;
      -webkit-transform: translateY(-10px);
      -moz-transform: translateY(-10px);
      -ms-transform: translateY(-10px);
      -o-transform: translateY(-10px);
    }
    50% {
      opacity: 1;
      -webkit-transform: translateY(0px);
      -moz-transform: translateY(0px);
      -ms-transform: translateY(0px);
      -o-transform: translateY(0px);
    }
    100% {
      opacity: 1;
      -webkit-transform: translateY(-10px);
      -moz-transform: translateY(-10px);
      -ms-transform: translateY(-10px);
      -o-transform: translateY(-10px);
    }
  }
 

  @media screen and (max-width: 750px) {
    .mob {
      display: block;
    }
    .pc {
      display: none;
    }
    .down-con {
      bottom: 8.7vh;
      width: 14.67vw;
      height: 14.67vw;
    }
    .down-con:after {
      position: absolute;
      left: 0;
      top: 0;
      content: '';
      width: 99%;
      height: 101%;
    }
    .down {
      width: 14.67vw;
      height: 14.67vw;
    }
    .down:after {
      top: 1.6vh;
      width: 7.47vw;
      height: 7.47vw;
    }
    .title {
      line-height: 9.34vw;
      font-size: 8vw;
    }
    
    .title:after {
      bottom: -5.91vh;
      margin: 0 auto;
      width: 14.93vw;
      height: 0.53vw;
    }
    .discr {
      margin-top: 11.52vh;
      font-size: 5.33vw;
    }

    .swiper-container-horizontal>.swiper-pagination-bullets .swiper-pagination-bullet {
      width: 2.67vw;
      height: 2.67vw;
      margin: 0 3.73vw;
      display: inline-block;
      border-radius: 100%;
      background: rgba(193, 193, 193, 1);
      opacity: 0.3;
    }
    .swiper-container-horizontal>.swiper-pagination-bullets .swiper-pagination-bullet-active {
      opacity: 1;
      background: #62C8F2;
    }

    #swiper01 .swiper-pagination {
      bottom: 6vh;
    }
    #swiper02 .swiper-pagination {
      bottom: 0vh;
    }
    #swiper02 .swiper-pagination-bullets .swiper-pagination-bullet {
      margin: 0 1.86vw;
    }

    .selection-7 .swiper-container-horizontal>.swiper-pagination-bullets .swiper-pagination-bullet {
      width: 2.67vw;
      height: 2.67vw;
      margin: 0 3.73vw;
      display: inline-block;
      border-radius: 100%;
      background: #fff;
      opacity: 0.3;
    }
    .selection-7 .swiper-container-horizontal>.swiper-pagination-bullets .swiper-pagination-bullet-active {
      opacity: 1;
      background: #fff;
    }

  }
</style>
