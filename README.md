# jquery.notification [![spm version](http://spmjs.io/badge/jquery.notification)](http://spmjs.io/package/jquery.notification)

AUTHOR WEBSITE: [http://ydr.me/](http://ydr.me/)

jquery.notification 桌面通知

**五星提示：当前脚本未作优化、未完工，请勿用在生产环境**

__IT IS [A SPM PACKAGE](http://spmjs.io/package/jquery.notification).__





#USAGE
```
var $ = require('jquery');
require('jquery.notification')($);

// 1. show
$.notification(settings);
$.notification("title","body");

// 2. clear
$.notification(null);
```




#OPTIONS
```
$.fn.notification.defaults = {
    title: "通知标题",
    body: "通知内容",
    // 标签类别
    tag: "",
    // 通知图标
    icon: "http://festatic.aliapp.com/img/icon.png",
    // 显示通知
    onshow: function () {},
    // 关闭通知
    onclose: function () {},
    // 单击通知
    onclick: function () {},
    // 错误通知
    onerror: function () {}
};
```
