<template>
  <div class="item1 item">
  <div class="page-section page-section-spacing swiper">
    <swiper style="height: 100vh" :circular="true" :vertical="true" indicator-active-color="#fff" :indicator-dots="true" indicator-color="rgba(255,255,255,0.5)">
      <swiper-item>
        <div class="content">
        <img class="m1" src="../../../static/images/item/1/1573191754662.png" alt="">
        <img class="m2" src="../../../static/images/item/1/1573202424677.png" alt="">
        <img class="m3" src="../../../static/images/item/1/1573199175927.gif" alt="">
        <img class="m4" src="../../../static/images/item/1/1573199287528.png" alt="">
        <div class="m5"></div>
        <img class="m6" src="../../../static/images/item/1/1573202280896.png" alt="">
        <img class="m7" src="../../../static/images/item/1/1573202280154.png" alt="">
        <img class="m8" src="../../../static/images/item/1/1573198707529.gif" alt="">
        <img class="m10" src="../../../static/images/item/1/1573199895762.png" alt="">
        <img class="m11" src="../../../static/images/item/1/1573199895762.png" alt="">
        </div>
        <img class="m9" src="../../../static/images/item/1/1573191565856.png" alt="">
      </swiper-item>
      <swiper-item>
        <div class="content list2">
          <img class="m1" src="../../../static/images/item/1/1573191754662.png" alt="">
          <img class="m2" src="../../../static/images/item/1/1573202424677.png" alt="">
          <img class="m3" src="../../../static/images/item/1/1573199175927.gif" alt="">
          <img class="avator" src="../../../static/images/item/1/zsj.png" alt="">
          <div class="gerenjianjie">
             <div class="left">
                <div>
                  <span>张树军</span>
                  <img src="https://file.rrxh5.cc/g2/c1/2019/11/08/1573207955583.png@!user_image_700x1" alt="">
                </div>
                 <div>
                   <span>1992.03.19</span>
                   <img src="https://file.rrxh5.cc/g2/c1/2019/11/08/1573207955274.png@!user_image_700x1" alt="">
                 </div>
                 <div @click="goMapFn">
                   <span>中国 北京</span>
                   <img class="position" src="https://file.rrxh5.cc/g2/c1/2019/11/08/1573207955570.png@!user_image_700x1" alt="">
                 </div>
             </div>
              <div class="middle">
                <div class="zfx"></div>
                <div class="line"></div>
              </div>
              <div class="right">
                <div>
                  <img src="https://file.rrxh5.cc/g2/c1/2019/11/08/1573207955120.png@!user_image_700x1" alt="">
                  <span>13522745253</span>
                </div>
                <div>
                  <img src="https://file.rrxh5.cc/g2/c1/2019/11/08/1573207953894.png@!user_image_700x1" alt="">
                  <span>13522745253</span>
                </div>
                <div>
                  <img src="https://file.rrxh5.cc/g2/c1/2019/11/08/1573207955743.png@!user_image_700x1" alt="">
                  <span>375002979</span>
                </div>
              </div>
          </div>
          <div class="gerenjianjie1">
              <div>
                <span>毕业院校:</span>
                <span>忻州师范学院</span>
              </div>
            <div>
              <span>专业:</span>
              <span>计算机</span>
            </div>
          </div>
          <div class="gerenjianjie2">
            <span>个人简介</span>
            <div></div>
            <span>about me</span>
          </div>
          <!--<img class="m4" src="../../../static/images/item/1/1573199287528.png" alt="">-->
          <!--<div class="m5"></div>-->
          <!--<img class="m6" src="../../../static/images/item/1/1573202280896.png" alt="">-->
          <!--<img class="m7" src="../../../static/images/item/1/1573202280154.png" alt="">-->
          <img class="m8" src="../../../static/images/item/1/1573198707529.gif" alt="">
          <img class="m10" src="../../../static/images/item/1/1573199895762.png" alt="">
          <img class="m11" src="../../../static/images/item/1/1573199895762.png" alt="">
        </div>
        <img class="m9" src="../../../static/images/item/1/1573191565856.png" alt="">
      </swiper-item>
      <swiper-item>
        <div class="content list3">
          <img class="m1" src="../../../static/images/item/1/1573191754662.png" alt="">
          <img class="m3" src="../../../static/images/item/1/1573199175927.gif" alt="">
          <div class="m5"></div>
          <img class="m6" src="../../../static/images/item/1/1573202280896.png" alt="">
          <img class="m8" src="../../../static/images/item/1/1573198707529.gif" alt="">
          <img class="m10" src="../../../static/images/item/1/1573199895762.png" alt="">
          <img class="m11" src="../../../static/images/item/1/1573199895762.png" alt="">
          <div class="gerenjianjie2">
          <span>工作经历</span>
          <div></div>
          <span>work experience</span>
          </div>
          <div class="gongzuojingli">
            <div class="it3">
              <span>2014.10-2016.12</span>
              <span>金品岛科技有限公司,担任前端开发工程师</span>
            </div>
            <div class="it3">
              <span>2017.01-2019.04</span>
              <span>北京友创科技有限公司，担任前端工程师</span>
            </div>
            <div class="it3">
              <span>2019.04-至今</span>
              <span>北京数据科技有限公司，担任h5开发工程师</span>
            </div>
          </div>
          <div class="fenge">
            <div class="zfx"></div>
            <div class="line"></div>
          </div>
          <div class="fenge fenge1">
            <div class="zfx"></div>
            <div class="line"></div>
          </div>
          <div class="fenge fenge2">
            <div class="zfx"></div>
            <div class="line"></div>
          </div>
          <div class="fenge fenge3">
            <div class="zfx"></div>
            <div class="line"></div>
          </div>
          <div class="fenge fenge4">
            <div class="zfx"></div>
            <div class="line"></div>
          </div>
        </div>
        <img class="m9" src="../../../static/images/item/1/1573191565856.png" alt="">
      </swiper-item>
      <swiper-item>
        <div class="content list3 list4">
          <img class="m1" src="../../../static/images/item/1/1573191754662.png" alt="">
          <img class="m3" src="../../../static/images/item/1/1573199175927.gif" alt="">
          <div class="m5"></div>
          <img class="m6" src="../../../static/images/item/1/1573202280896.png" alt="">
          <img class="m8" src="../../../static/images/item/1/1573198707529.gif" alt="">
          <img class="m10" src="../../../static/images/item/1/1573199895762.png" alt="">
          <img class="m11" src="../../../static/images/item/1/1573199895762.png" alt="">
          <div class="gerenjianjie2">
            <span>求职意向</span>
            <div></div>
            <span>job hunting intention</span>
          </div>
          <div class="qiuzhiyixiang">
            <div class="it4">
              <span>工作意向: </span>
              <span>全职</span>
            </div>
            <div class="it4">
              <span>应聘岗位:</span>
              <span>前端工程师</span>
            </div>
            <div class="it4">
              <span>期望行业:</span>
              <span>互联网金融</span>
            </div>
            <div class="it4">
              <span>工作地区:</span>
              <span>北京</span>
            </div>
            <div class="it4">
              <span>期望月薪:</span>
              <span>面议</span>
            </div>
            <div class="it4">
              <span>目前状态:</span>
              <span>离职状态 可立即返岗</span>
            </div>
          </div>
          <div class="fenge">
            <div class="zfx"></div>
            <div class="line"></div>
          </div>
          <div class="fenge fenge1">
            <div class="zfx"></div>
            <div class="line"></div>
          </div>
          <div class="fenge fenge2">
            <div class="zfx"></div>
            <div class="line"></div>
          </div>
          <div class="fenge fenge3">
            <div class="zfx"></div>
            <div class="line"></div>
          </div>
          <div class="fenge fenge4">
            <div class="zfx"></div>
            <div class="line"></div>
          </div>
          <div class="fenge fenge5">
            <div class="zfx"></div>
            <div class="line"></div>
          </div>
          <div class="fenge fenge6">
            <div class="zfx"></div>
            <div class="line"></div>
          </div>
        </div>
        <img class="m9" src="../../../static/images/item/1/1573191565856.png" alt="">
      </swiper-item>
      <swiper-item>
        <div class="content list3 list5">
          <img class="m1" src="../../../static/images/item/1/1573191754662.png" alt="">
          <img class="m3" src="../../../static/images/item/1/1573199175927.gif" alt="">
          <div class="m5"></div>
          <img class="m6" src="../../../static/images/item/1/1573202280896.png" alt="">
          <img class="m8" src="../../../static/images/item/1/1573198707529.gif" alt="">
          <img class="m10" src="../../../static/images/item/1/1573199895762.png" alt="">
          <img class="m11" src="../../../static/images/item/1/1573199895762.png" alt="">
          <div class="gerenjianjie2">
            <span>技能掌握</span>
            <div></div>
            <span>skill  mastery</span>
          </div>
          <div class="jinengzhangwo">
            <div class="it5">
                <span>1、精通Vue,Vuex,Vux,ElementUI等全家桶 </span>
                <span>2、熟练Git源代码管理以及协同开发  </span>
                <span>3、熟悉：Node.js开发 </span>
                <span>4、熟练使用Phpotoshop，能够独立设计、制作图片及切图开发等 </span>
                <span>5、掌握各种js函数库和框架，包括jQuery,Ajax </span>
                <span>6、HTML5新特性，视频和音频播放控制，了解Canvas绘图统计图表/数据可视化 </span>
                <span>7、熟练JS、DOM、BOM等原生js代码，编写页面逻辑和交互和动态效果 </span>
                <span>8、熟练mpvue,微信小程序开发 </span>
            </div>
          </div>
        </div>
        <img class="m9" src="../../../static/images/item/1/1573191565856.png" alt="">
      </swiper-item>
      <swiper-item>
        <div class="content list3 list6">
          <img class="m1" src="../../../static/images/item/1/1573191754662.png" alt="">
          <img class="m3" src="../../../static/images/item/1/1573199175927.gif" alt="">
          <div class="m5"></div>
          <img class="m6" src="../../../static/images/item/1/1573202280896.png" alt="">
          <img class="m8" src="../../../static/images/item/1/1573198707529.gif" alt="">
          <img class="m10" src="../../../static/images/item/1/1573199895762.png" alt="">
          <img class="m11" src="../../../static/images/item/1/1573199895762.png" alt="">
          <div class="gerenjianjie2">
            <span>项目经历</span>
            <div></div>
            <span>project experience</span>
          </div>
          <div class="xiangmujingli">
            <div class="it6">
              <span>公司名称： </span>
              <span>北京数据科技有限公司</span>
            </div>
            <div class="it6">
              <span>项目时间： </span>
              <span>2019.04-至今 </span>
            </div>
            <div class="it6">
              <span>所用技术： </span>
              <span>VUE，VUEX，Element-ui，AXIOS，Vue-router，Webpack, Scss, Less, Git，Vue-quill-editor，BetterScroll等</span>
            </div>
            <div class="it6">
              <span>项目描述： </span>
              <span>亚财是将比财在国内的模式复制到香港，即以api的方式对接香港的银行，整合香港银行、资管机构的存款和资管产品，做直销银行产品的比价服务。 </span>
            </div>
            <div class="it6">
              <span>个人职责： </span>
              <span>整个亚财的项目，pc + app都是由我一手搭建并开发，并上线，期间,还参与了比财活动开发，为活动构建了多入口启动打包的框架 </span>
            </div>
          </div>
        </div>
        <img class="m9" src="../../../static/images/item/1/1573191565856.png" alt="">
      </swiper-item>
      <swiper-item>
        <div class="content list3 list6">
          <img class="m1" src="../../../static/images/item/1/1573191754662.png" alt="">
          <img class="m3" src="../../../static/images/item/1/1573199175927.gif" alt="">
          <div class="m5"></div>
          <img class="m6" src="../../../static/images/item/1/1573202280896.png" alt="">
          <img class="m8" src="../../../static/images/item/1/1573198707529.gif" alt="">
          <img class="m10" src="../../../static/images/item/1/1573199895762.png" alt="">
          <img class="m11" src="../../../static/images/item/1/1573199895762.png" alt="">
          <div class="gerenjianjie2">
            <span>项目经历</span>
            <div></div>
            <span>project experience</span>
          </div>
          <div class="xiangmujingli">
            <div class="it6">
              <span>公司名称： </span>
              <span>北京友创时代科技有限公司</span>
            </div>
            <div class="it6">
              <span>项目时间： </span>
              <span>2018.11-2019.04 </span>
            </div>
            <div class="it6">
              <span>所用技术： </span>
              <span>VUE，VUEX，Element-ui，AXIOS，Vue-router，Webpack, Scss, Less, Git，Vue-quill-editor，BetterScroll, VideoPlayer, VueScroller, Vue-fullcalenda, VueI18n, Map, Echarts等</span>
            </div>
            <div class="it6">
              <span>项目描述： </span>
              <span>这是一个外包公司，一共做了5个项目，餐饮采购平台 ，蜀海菜品公众号 ，落后店（移动端和管理端） ，神秘客(移动端和管理端) ，菜品溯源(移动端和管理端) ，本项目是给海底捞供应链蜀海平台打造的</span>
            </div>
            <div class="it6">
              <span>个人职责： </span>
              <span>负责项目页面的布局和数据渲染，完成与后端的接口对接并配合联调，整体把握项目的进度与扩展 </span>
            </div>
          </div>
        </div>
        <img class="m9" src="../../../static/images/item/1/1573191565856.png" alt="">
      </swiper-item>
      <swiper-item>
        <div class="content list3 list6">
          <img class="m1" src="../../../static/images/item/1/1573191754662.png" alt="">
          <img class="m3" src="../../../static/images/item/1/1573199175927.gif" alt="">
          <div class="m5"></div>
          <img class="m6" src="../../../static/images/item/1/1573202280896.png" alt="">
          <img class="m8" src="../../../static/images/item/1/1573198707529.gif" alt="">
          <img class="m10" src="../../../static/images/item/1/1573199895762.png" alt="">
          <img class="m11" src="../../../static/images/item/1/1573199895762.png" alt="">
          <div class="gerenjianjie2">
            <span>项目经历</span>
            <div></div>
            <span>project experience</span>
          </div>
          <div class="xiangmujingli">
            <div class="it6">
              <span>公司名称： </span>
              <span>金品岛科技有限公司</span>
            </div>
            <div class="it6">
              <span>项目时间： </span>
              <span>2014.10-2016.12 </span>
            </div>
            <div class="it6">
              <span>所用技术： </span>
              <span>VUE，VUEX，Element-ui，AXIOS，Vue-router，Webpack, Scss, JQ,  Less, Git，Vue-quill-editor，Echarts等</span>
            </div>
            <div class="it6">
              <span>项目描述： </span>
              <span>金品岛是一家特卖商城，产品囊括家电、3C、百货等品类，实现了用户模块（注册,登录）、商品模块(详情查看)、购物车模块等等 移动端和管理端所用到技术 </span>
            </div>
            <div class="it6">
              <span>个人职责： </span>
              <span>负责项目页面的布局和数据渲染，完成与后端的接口对接并配合联调  </span>
            </div>
          </div>
        </div>
        <img class="m9" src="../../../static/images/item/1/1573191565856.png" alt="">
      </swiper-item>
      <swiper-item>
        <div class="content list3 list7">
          <img class="m1" src="../../../static/images/item/1/1573191754662.png" alt="">
          <img class="m3" src="../../../static/images/item/1/1573199175927.gif" alt="">
          <div class="m5"></div>
          <img class="m6" src="../../../static/images/item/1/1573202280896.png" alt="">
          <img class="m8" src="../../../static/images/item/1/1573198707529.gif" alt="">
          <img class="m10" src="../../../static/images/item/1/1573199895762.png" alt="">
          <img class="m11" src="../../../static/images/item/1/1573199895762.png" alt="">
          <div class="gerenjianjie2">
            <span>自我评价</span>
            <div></div>
            <span>self evaluation</span>
          </div>
          <div class="ziwopingjia">
            有5年以上经验，有良好的人际沟通能力，良好的工作协调能力，踏实肯干的工作精神，不断学习新技术，对知识有强烈的求知欲，良好的前端编程能力和编程习惯，致力于代码的整体结构规范及优化。自学完成PS、AxureRp、CyberlinkPowerDirector
          </div>
        </div>
        <img class="m9" src="../../../static/images/item/1/1573191565856.png" alt="">
      </swiper-item>
      <swiper-item>
        <div class="content list3 list8">
          <img class="m1" src="../../../static/images/item/1/1573191754662.png" alt="">
          <img class="m3" src="../../../static/images/item/1/1573199175927.gif" alt="">
          <div class="m5"></div>
          <img class="m6" src="../../../static/images/item/1/1573202280896.png" alt="">
          <img class="m8" src="../../../static/images/item/1/1573198707529.gif" alt="">
          <img class="m10" src="../../../static/images/item/1/1573199895762.png" alt="">
          <img class="m11" src="../../../static/images/item/1/1573199895762.png" alt="">
          <div class="gerenjianjie2">
            <span>期待您的联系</span>
            <div></div>
            <span>I look forward to your contact</span>
          </div>
          <div class="lianxi">
            <div class="erweima">
              <img src="../../../static/images/item/1/erweima.jpg" alt="">
              <p>期待您的联系</p>
            </div>
            <a href="tel:13522745253" @click="callFn">拨打我的电话</a>
          </div>
        </div>
        <img class="m9" src="../../../static/images/item/1/1573191565856.png" alt="">
      </swiper-item>
    </swiper>
  </div>
    <div class="music" @click="tipsMusicFn">
      <div v-if="isOff" class="music-play music-play1"></div>
      <div v-if="isOff" class="music-play music-play2"></div>
      <div v-if="isOff" class="music-play music-play3"></div>
      <div :class="[isOff ? 'music-on' : 'music-off']"></div>
    </div>
    <div class="arrow-down"></div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      isOff: true,
      audio: {}
    }
  },
  methods: {
    goMapFn () {
      wx.navigateTo({url: '/pages/map/main?map=123'})
    },
    callFn () {
      wx.makePhoneCall({
        phoneNumber: '13522745253',
        success: function () {
          wx.showToast({
            title: '拨打电话成功',
            icon: 'success',
            duration: 2000
          })
        },
        fail: function () {
          wx.showToast({
            title: '拨打电话失败',
            icon: 'success',
            duration: 2000
          })
        }
      })
    },
    tipsMusicFn () {
      this.isOff = !this.isOff
      if (this.isOff) {
        this.audio.src = 'http://m10.music.126.net/20200314014047/646911628cd0c2b3aab43dea4ff0bc8c/ymusic/25f5/77be/0264/427ec62ea7b1030f6fe5f9a4b84c9c83.mp3'
        this.audio.play()
      } else {
        this.audio.pause()
      }
    },
    initTask () {
      this.audio = wx.getBackgroundAudioManager()
      // console.log(wx)
      this.audio.src = 'http://m10.music.126.net/20200314014047/646911628cd0c2b3aab43dea4ff0bc8c/ymusic/25f5/77be/0264/427ec62ea7b1030f6fe5f9a4b84c9c83.mp3'
      this.audio.title = '承诺长大' // 注意必填
      this.audio.epname = '多米~'
      this.audio.singer = '多米'
      this.audio.controls = false
      this.audio.coverImgUrl = 'http://y.gtimg.cn/music/photo_new/T002R300x300M000003rsKF44GyaSk.jpg?max_age=2592000'
    }
  },
  created () {
    console.log('show')
    console.log(this.isShow)
    this.initTask()
  },
  mounted () {
  }
}
</script>

<style>
  .input{
    position: fixed;
    width: 100%;
    height: 50px;
    background: rgba(0, 0, 0, 0.63);
    color: rgba(255, 255, 255, 0.69);
    border: none;
    top: 0px;
    padding: 0 20px;
  }
  .item1{
    background: rgb(0, 0, 0);
    height: 100vh;
  }
  .item1 img{
    vertical-align: top;
    -webkit-user-drag: none;
  }
  .item1 .content{
    text-align: center;
    position: relative;
    height: 100vh;
  }
  img.m1{
    width: 100%;
    height: 33px;
    margin-left: 0px;
    margin-top: 0.1px;
    position: absolute;
    top: 0px;
    left: 0px;
    z-index: 5;
  }
  img.m2{
    width: 184px;
    height: 25.2px;
    margin-left: -0.8235px;
    margin-top: 0px;
    margin: 0 auto;
    position: absolute;
    top: 80px;
    left: 50%;
    transform: translateX(-50%);
    z-index: 10;
  }
  img.m3{
    display: inline-block;
    position: absolute;
    top: 1px;
    left: 50%;
    transform: translateX(-50%);
    width: 300px;
    height: 300px;
    margin: auto;
    z-index: 3;
  }
  img.m4{
    width: 220px;
    height: 205px;
    position: absolute;
    top: 142px;
    left: 50%;
    transform: translateX(-50%);
    z-index: 40;
  }
  div.m5{
    width: 0;
    height: 0;
    border-left: 100px solid transparent;
    border-right: 100px solid transparent;
    border-top: 200px solid rgb(17, 145, 255);
    position: absolute;
    top: 212px;
    left: 50%;
    transform: translateX(-50%);
    z-index: 30;
  }
  img.m6{
    width: 253px;
    height: 46px;
    position: absolute;
    top: 252px;
    left: 50%;
    transform: translateX(-50%);
    z-index: 42;
  }
  img.m7{
    width: 140px;
    height: 35px;
    position: absolute;
    top: 302px;
    left: 50%;
    transform: translateX(-50%);
    z-index: 41;
  }
  img.m8{
    width: 450px;
    height: 280px;
    position: absolute;
    top: 280px;
    left: 50%;
    transform: translateX(-50%);
    z-index: 0;
  }
  img.m9{
    width: 100%;
    height: 55px;
    position: absolute;
    bottom: 0px;
    left: 0px;
  }
  img.m10{
    width: 43px;
    height: 45px;
    position: absolute;
    top: 60px;
    left: 20px;
    z-index: 100;
  }
  img.m11{
    width: 33px;
    height: 35px;
    position: absolute;
    top: 120px;
    left: 120px;
    z-index: 100;
  }
  .music{
    width: 22px;
    height: 22px;
    position: fixed;
    z-index: 1000;
    right: 10px;
    top: 10px;
  }
  .music-on,.music-off{
    position: absolute;
    width: 20px;
    height: 20px;
  }
  .music-on{
    background: url(../../../static/images/item/1/icon_music_on2.png)no-repeat;
    background-size: 100% 100%;
  }
  .music-off{
    background: url(../../../static/images/item/1/icon_music_off2.png)no-repeat;
    background-size: 100% 100%;
  }
  .music-play{
    position: absolute;
    width: 18px;
    height: 18px;
    background: url(../../../static/images/item/1/icon_music.png)no-repeat;
    background-size: 100% 100%;
  }
  .music-play1{
    -webkit-animation: ani-music1 2s ease-out infinite;
    animation: ani-music1 2s ease-out infinite;
  }
  .music-play2{
    -webkit-animation: ani-music2 2.5s ease-out infinite;
    animation: ani-music2 2.5s ease-out infinite;
  }
  .music-play3{
    -webkit-animation: ani-music3 3s ease-out infinite;
    animation: ani-music3 3s ease-out infinite;
  }
  .arrow-down{
    position: fixed;
    bottom: 10px;
    left: 50%;
    width: 48px;
    height: 48px;
    transform: translateX(-40%);
    -webkit-animation: ani-arrow 1.5s infinite ease-in-out;
    -moz-animation: ani-arrow 1.5s infinite ease-in-out;
    animation: ani-arrow 1.5s infinite ease-in-out;
    background-image: url(../../../static/images/item/1/icon_arrow2.png);
    background-position: center center;
    background-repeat: no-repeat;
    z-index: 110;
  }
  @keyframes ani-music1 {
    0% {
      transform: translate(0,0) rotate(0deg);
      opacity: 0;
    }
    30% {
    transform: translate(-10px,-5px) rotate(15deg);
    opacity: 1;
   }
    100% {
      transform: translate(-15px,-15px) rotate(0deg);
      opacity: 0;
    }
  }
  @keyframes ani-music2 {
    0% {
      transform: translate(0,0) rotate(0deg);
      opacity: 0;
    }
    30% {
      transform: translate(-25px,-65px) rotate(30deg);
      opacity: 1;
    }
    100% {
      transform: translate(-25px,-25px) rotate(180deg);
      opacity: 0;
    }
  }
  @keyframes ani-music3 {
    0% {
      transform: translate(0,0) rotate(0deg);
      opacity: 0;
    }
    30% {
      transform: translate(-5px,-15px) rotate(45deg);
      opacity: 1;
    }
    100% {
      transform: translate(-35px,-35px) rotate(0deg);
      opacity: 0;
    }
  }
  @keyframes  ani-arrow{
    0%, 30% {
      opacity: 0;
      transform: translate(0,5px);
    }
    60% {
      opacity: 1;
      transform: translate(0,0);
    }
    100% {
      opacity: 0;
      transform: translate(0,-4px);
    }
  }

  .gerenjianjie{
    position: absolute;
    width: 100%;
    z-index: 1000;
    display: flex;
    flex-wrap: nowrap;
    color: #fff;
    font-size: 15px;
    top: 300px;
  }
  .gerenjianjie1{
    position: absolute;
    width: 100%;
    z-index: 1000;
    display: flex;
    color: #fff;
    font-size: 15px;
    top: 450px;
    flex-direction: column;
  }
  .gerenjianjie1 div{
    margin-top: 10px;
  }
  .gerenjianjie1 div span:nth-child(1){
    display: inline-block;
    width: 100px;
    text-align: left;
    margin-right: 10px;
  }
  .gerenjianjie img{
    width: 18px;
    height: 17px;
    vertical-align: middle;
  }
  .gerenjianjie .left{
    flex: 0.45;
  }
  .gerenjianjie .left div{
    margin-top: 20px;
  }
  .gerenjianjie .right div{
    margin-top: 20px;
  }
  .gerenjianjie .left div span{
    text-align: right;
    display: inline-block;
    width: 100px;
    margin-right: 10px;
  }
  .gerenjianjie .right div span{
    margin-left: 10px;
    text-align: left;
    display: inline-block;
    width: 100px;
  }
  .gerenjianjie .middle{
    flex: 0.1;
    top: 450px;
  }
  .gerenjianjie .middle .zfx{
    width: 25px;
    height: 25px;
    background: #fff;
    transform: rotate(45deg);
  }
  .gerenjianjie .middle .line{
    height: 100px;
    width: 3px;
    background: #fff;
    margin-left: 12px;
  }
  .gerenjianjie .right{
    flex: 0.45;
  }
  .list2 .m8{
    top: 420px;
    margin-left: -12px;
  }
  .avator{
    position: absolute;
    z-index: 1000;
    max-width: 100px;
    max-height: 100px;
    top: 100px;
    left: 50%;
    transform: translateX(-50%);
  }
  .gerenjianjie2{
    display: flex;
    justify-content: center;
    flex-direction: column;
    position: absolute;
    width: 100%;
    top: 240px;
    left: 50%;
    transform: translateX(-50%);
    z-index: 10000;
    color:#fff;
    text-align: center;
  }
  .gerenjianjie2 div{
    width: 80%;
    height: 1px;
    margin: 5px auto;
    background: #fff;
  }
  .list3 .m3{
    top: -50px;
  }
  .list3 .m5{
    top: 0px;
  }
  .list3 .m6{
    top: 0px;
  }
  .list3 .gerenjianjie2{
    top: 60px;
  }
  .list3 .gongzuojingli{
    display: flex;
    flex-wrap: nowrap;
    position: absolute;
    z-index: 1000;
    top: 200px;
    flex-direction: column;
    color:#fff;
  }
  .list3 .gongzuojingli .it3{
    display: flex;
    margin-top: 20px;
  }
  .list3 .gongzuojingli .it3 span:nth-child(1){
    flex: 0.4;
    display: inline-block;
    text-align: right;
  }
  .list3 .gongzuojingli .it3 span:nth-child(2){
    flex: 0.6;
    display: inline-block;
    text-align: left;
    margin-left: 30px;
  }
  .list3 .m8{
    top: 420px;
    margin-left: -12px;
  }
  .fenge{
    display: flex;
    flex-direction: column;
    position: absolute;
    z-index: 1000;
    top: 200px;
    left: 140px;
    width: 100%;
  }
  .fenge .zfx{
    width: 15px;
    height: 15px;
    background: #fff;
    transform: rotate(45deg);
  }
  .fenge .line{
    height: 50px;
    width: 2px;
    background: #fff;
    margin-left: 7px;
  }
  .fenge1{
    margin-top: 50px;
  }
  .fenge2{
    margin-top: 50px;
  }
  .fenge3{
    margin-top: 100px;
  }
  .fenge4{
    margin-top: 150px;
  }
  .fenge5{
    margin-top: 200px;
  }
  .fenge6{
    margin-top: 250px;
  }
  .qiuzhiyixiang{
    display: flex;
    flex-wrap: nowrap;
    position: absolute;
    z-index: 1000;
    top: 200px;
    flex-direction: column;
    color:#fff;
    margin-left: 50px;
  }
  .qiuzhiyixiang .it4{
    text-align: left;
    margin-top: 20px;
  }
  .qiuzhiyixiang .it4 span:nth-child(1){
    margin-right: 10px;
  }
  .list4 .fenge{
    left: 20px;
  }
  .list5 .jinengzhangwo{
    display: flex;
    flex-wrap: nowrap;
    position: absolute;
    z-index: 1000;
    top: 200px;
    flex-direction: column;
    color:#fff;
    margin: 0 10px;
  }
  .list5 .jinengzhangwo .it5 span{
    display: block;
    text-align: left;
    margin-top: 10px;
  }
  .xiangmujingli{
    display: flex;
    flex-wrap: nowrap;
    position: absolute;
    z-index: 1000;
    top: 200px;
    flex-direction: column;
    color:#fff;
    margin: 0px 10px;
  }
  .xiangmujingli .it6{
    margin-top: 10px;
    text-align: left;
  }
  .list7 .ziwopingjia{
    display: flex;
    flex-wrap: nowrap;
    position: absolute;
    z-index: 1000;
    top: 200px;
    flex-direction: column;
    color:#fff;
    text-align: left;
    padding: 0 30px;
    line-height: 30px;
    margin-top: 30px;
  }
  .list8 .lianxi{
    display: flex;
    flex-wrap: nowrap;
    position: absolute;
    z-index: 1000;
    top: 200px;
    flex-direction: column;
    color:#fff;
    padding: 0 30px;
    margin-top: 30px;
    text-align: center;
    left:50%;
    transform: translateX(-50%);
    text-align: center;
  }
  .list8 .lianxi .erweima img{
    width: 200px;
    height: 200px;
    margin-bottom: 10px;
  }
  .list8 .lianxi a{
    display: block;
    height: 20px;
    line-height: 20px;
    width: 100px;
    background: #2ba3ff;
    padding: 8px 15px;
    border-radius: 5px;
    margin-left: 32px;
    margin-top: 32px;
  }
  .position{
    -webkit-animation: poi 1.5s infinite ease-in-out;
  }
  @keyframes poi {
    0%{
      transform: scale(0.5);
    }
    50%{
      transform: scale(1);
    }
    100%{
      transform: scale(0.5);
    }
  }
</style>
