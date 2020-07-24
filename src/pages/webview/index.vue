<template>
    <div style="height:100%;width: 100%">
      <!--<web-view src="https://android.myapp.com/myapp/detail.htm?apkName=com.pc.finance&apkCode=108"></web-view>-->
      <!--<web-view src="https://blog.csdn.net/j244233138/article/details/90723741"></web-view>-->
      <!--<button open-type="contact">打开</button>-->
      <!--<cover-image :src="qrcodeSrc"></cover-image>-->
      <img @click="view" data-src="https://finsuit-test.oss-cn-beijing.aliyuncs.com/Yiye/a13ec638-9850-4707-acbd-8f13477e8088.jpg" style="width:100%;height:400px" src="../../../static/images/qrcode.jpg" alt="">
      <!--<img @click="view" data-src="https://finsuit-test.oss-cn-beijing.aliyuncs.com/Yiye/0b87e80a-0a7d-4ea0-84c4-d9b86fc75ed2.jpg" style="width:100%;height:400px" src="../../../static/images/qrcode.jpg" alt="">-->
    </div>
</template>
<script>
//  import QRCode from "qrcode"
    export default {
        name: '',
        props: [],
        data() {
            return {
              qrcodeSrc: ''
            }
        },
        methods: {
          view(e){
            console.log(1);
            console.log(e.target.dataset.src);
            var current = e.target.dataset.src;   //这里获取到的是一张本地的图片
              wx.previewImage({
              current: current,//需要预览的图片链接列表
              urls: [current]  //当前显示图片的链接
            })
          },          // 生成二维码
          generateQRCode() {
            // 二维码&链接
            let _this = this;
            let url = 'http://www.baidu.com';
            QRCode.toDataURL(
              url,
              {
                margin: 1
              },
              function(err, url) {
                console.log(_this.qrcodeSrc)
                _this.qrcodeSrc = url;
              }
            );
          },
        },
        computed: {},
        watch: {},
        created() {
        },
        mounted() {
          this.$nextTick(() => {
//            this.generateQRCode()
          })
        },
        destroyed() {
        },
    }
</script>
<style lang="scss" scoped>

</style>
