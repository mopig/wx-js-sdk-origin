# 微信官方 sdk 的 npm 包

原链接：[http://res.wx.qq.com/open/js/jweixin-1.3.1.js](http://res.wx.qq.com/open/js/jweixin-1.3.0.js)

```javascript
import WechatPlugin from 'wx-js-sdk-origin';
Vue.use(WechatPlugin)

console.log(Vue.wechat, vm.$wechat) // 可以直接访问 wx 对象。
```