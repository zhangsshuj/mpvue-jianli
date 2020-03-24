<template>
  <div>
    <map id="map"
         :markers="markers"
         :longitude="116.625634"
         :latitude="39.910347"
         show-location
         style="width: 100%; height:100vh;"
         subkey="MY5BZ-FVGL4-U6YUP-DW5ZB-C66F6-ICBDF"
    >
    </map>
    <input type="text" @click="inputFn(0)" disabled confirm-typetype="search" class="input ut1" placeholder="路线规划"/>
    <input type="text" @click="inputFn(1)" disabled confirm-typetype="search" class="input ut2" placeholder="地铁图"/>
    <input type="text" @click="inputFn(2)" disabled confirm-typetype="search" class="input ut3" placeholder="地图选点"/>
  </div>
</template>
<script>
  export default {
    data () {
      return {
        markers: [
          { id: '1',
            latitude: '39.910347',
            longitude: '116.625634',
            title: '张树军的家地址',
            iconPath: 'https://graph.baidu.com/resource/121f00ce835b05927c4a301585063412.jpg',
            width: '100',
            height: '50',
            callout: {
              content: '树军的家',
              borderRadius: 10,
              borderWidth: 1,
              borderColor: '#ddd',
              bgColor: '#000000',
              display: 'ALWAYS',
              color: '#fff',
              padding: 2
            },
            label: {
              content: '竹木厂',
              borderRadius: 10,
              borderWidth: 1,
              borderColor: '#ddd',
              bgColor: '#000000',
              display: 'ALWAYS',
              color: '#fff',
              padding: 2
            }
          }
        ]
      }
    },
    methods: {
      initFn () {
        wx.setNavigationBarTitle({title: '地图'})
      },
      inputFn (val) {
        let key,referer,endPoint,plugin
        switch (val) {
          case 0:
            plugin = requirePlugin('routePlan');
            key = 'MY5BZ-FVGL4-U6YUP-DW5ZB-C66F6-ICBDF';  //使用在腾讯位置服务申请的key
            referer = '多米哦';   //调用插件的app的名称
            endPoint = JSON.stringify({  //终点
              'name': '北京西站',
              'latitude': 39.894806,
              'longitude': 116.321592
            });
            wx.navigateTo({
              url: 'plugin://routePlan/index?key=' + key + '&referer=' + referer + '&endPoint=' +endPoint
            });
            break;
          case 1:
            plugin = requirePlugin('subway');
            key = 'MY5BZ-FVGL4-U6YUP-DW5ZB-C66F6-ICBDF';  //使用在腾讯位置服务申请的key
            referer = '多米哦';   //调用插件的app的名称
            wx.navigateTo({
              url: 'plugin://subway/index?key=' + key + '&referer=' + referer
            });
            break;
          case 2:
            key = 'MY5BZ-FVGL4-U6YUP-DW5ZB-C66F6-ICBDF';  //使用在腾讯位置服务申请的key
            referer = '多米哦';   //调用插件的app的名称
            const location = JSON.stringify({
              latitude: 39.89631551,
              longitude: 116.323459711
            });
            const category = '生活服务,娱乐休闲';
            wx.navigateTo({
              url: 'plugin://chooseLocation/index?key=' + key + '&referer=' + referer + '&location=' + location + '&category=' + category
            });
            break;
        }
      }
    },
    mounted () {
      // console.log(this.$root.$mp.query)
      // console.log(this.$root.$mp.appOptions)
      this.initFn()
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
  .ut2{
   top: 50px;
    background: rgba(255, 53, 26, 0.55);
  }
  .ut3{
    top: 100px;
    background: rgba(31, 255, 0, 0.55);
  }
</style>
