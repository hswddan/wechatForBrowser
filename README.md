## 项目简介

微信打开提示使用浏览器打开，自动识别判断环境，只有微信内打开才自动弹窗，普通浏览器打开可直接看到页面内容。

### 关键技术点

js判断浏览器

```markdown
var is_weixin = (function(){return navigator.userAgent.toLowerCase().indexOf('micromessenger') !== -1})();


```

具体案例 [test.html](https://hswddan.github.io/wechatForBrowser/test.html)

案例2 [2.html](https://hswddan.github.io/wechatForBrowser/2.html)

案例3 [202005.html](https://hswddan.github.io/wechatForBrowser/202005.html)

### 项目地址

GitHub地址 [wechatForBrowser](https://github.com/hswddan/wechatForBrowser)

### 我的GitHub项目

欢迎关注我的开源项目 [hswddan](https://github.com/hswddan) 
