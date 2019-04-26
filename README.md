## 项目简介

微信打开提示使用浏览器打开，自动识别判断环境，只有微信内打开才自动弹窗，普通浏览器打开可直接看到页面内容。

### 关键技术点

js判断浏览器

```markdown
var is_weixin = (function(){return navigator.userAgent.toLowerCase().indexOf('micromessenger') !== -1})();


```

具体案例 [test](https://hswddan.github.io/wechatForBrowser/test.html).

### 项目地址

GitHub地址 [wechatForBrowser](https://github.com/hswddan/wechatForBrowser)

### 我的GitHub项目

欢迎关注我的开源项目 [documentation](https://github.com/hswddan) 
