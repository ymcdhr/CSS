Welcome to the CSS

因为git上无法直接预览效果，请移步至：
http://www.qdfuns.com/notes/19478/b5fb6f9fd94d402de692c59ca784e798.html

#一、最常用的样式
1. 有哪些元素类型
2. 文字/容器的水平居中和垂直居中
3. position的使用/icon的简单实现
4. 要注意盒子模型
5. 文字是不是要截断/换行
6. -webkit-box、-webkit-flex的使用
7. 巧用继承inherit
8. pisition:sticky的使用

#二、别掉进这些坑
1. inline-block的坑
2. float的坑
3. 注意margin、padding的百分比
4. 小心使用！important

#三、CSS性能优化
1. 减少CSS/image文件的请求
* css压缩/css合并
* icon使用base64编码
* 图片的合并、压缩与映射（使用background-position即可）

2. CSS写法优化
* 禁止使用 * 选择器；避免使用id选择器（考虑重用性）
* 值为0时不需要任何单位（Zero values don‘t need units）
* 避免使用低性能选择器，例如标签选择器、多重选择器和后代选择器：  /* 性能较低的选择器 */ div { … } ul li a { … } body.profile ul.tabs.nav li a { … } 

#四、推荐阅读：CSS与设备屏幕的关系
1. 什么是PPI、DPI、以及与CSS的关系？
http://www.infoq.com/cn/articles/development-of-the-mobile-web-deep-concept

#五、推荐阅读：响应式布局
1. 响应式布局方案，参考：rem.html

#六、资料参考：
* https://developer.mozilla.org/zh-CN/docs/Web/CSS/Reference
* http://www.runoob.com/css/css-tutorial.html
* http://zh.html.net/tutorials/css/
* https://www.w3.org/community/webed/wiki/CSS
