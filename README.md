# Something About Learning FrontEnd
---
## 1. 先做几个基础题
### 1.1. 页面布局：最上面是一个 banner，下面左边固定宽度，右边自适应宽度。
### 1.2. 在上面基础上添加功能。右边一共有上中下三块内容，第一块做图片自动/手动切换功能；第二块做两个输入框，第一个框输入一个关键字，第二个框任意输入文字，当出现关键字时，立即将关键字显示成红色；第三块做一个实时时间显示，做一个选择框可以选择时间显示方式，做一个下拉列表可选择显示时区（随便选几个时区）。
### 1.3. 加一个跟随窗口上下滚动，相对位置不变的导航，可以快速定位到网页每一块内容。
### 1.4. 附加题（有空可以做做）：加一个弹窗到页面上，弹窗可用键盘按键打开关闭，最多能打开一个。弹窗内用div标签的边框圆角画一个笑脸，用css3实现鼠标移到上面笑脸变成生气脸，移开还原成笑脸。让弹窗移动起来，弹窗碰到边界时按照物理中入射角等于反射角的方式反弹。
---
## 2. 一些常用的方法工具
### 2.1. Git 和 GitHub
#### Git 是最流行的分布式版本控制系统。廖雪峰的[教程](https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)还是不错的，上面也有视频演示。
#### GitHub 是一种软件项目的托管平台。先看官网的[教程](https://guides.github.com/activities/hello-world/)，把账号注册了（~~名字可以想个帅气点的~~），再把前面做的网页上传到上面，并且生成可以直接浏览的页面。方法大概像[这样](https://blog.csdn.net/zeroyulong/article/details/80499878)。遇到问题再去百度上找找。
### 2.2. NVM 和 Nodejs
#### NVM 是管理 Node 版本的工具。不同项目可能支持的 Node 版本不同，所以需要切换到不同到Node版本，所以可以先装一个 NVM，需要先卸载已安装的 Node。Windows 系统可以安照这个[教程](https://www.jianshu.com/p/d0e0935b150a),用 NVM 安装 Node 也比较方便。这里有一篇是 Node 的简单[介绍](https://www.jqhtml.com/7258.html)。
### 2.3. 好用的 Chrome
#### 不管是日常使用还是前端调试，都推荐使用 [Chrome](https://www.google.cn/intl/zh-CN/chrome/) 浏览器。这篇[《前端chrome浏览器调试总结》](https://www.jianshu.com/p/b25c5b88baf5)可以好好看看。
### 2.4. 简单但是强大的 Sublime Text3
#### 我一直是用这个文本编辑器的，所以就推荐这款。平时做一些笔记或者编写前端的HTML、JS代码都很方便。直接到[官网](http://www.sublimetext.com)下载，上不了再到其他网站上找资源。使用很简单，一些快捷键自己网上搜搜就有了，我说一个自己遇到的问题。 Sublime 要安装其他插件需要先安装一个 [Package Control](https://packagecontrol.io) ,可以先看一下[安装方法](https://www.cnblogs.com/yangzhuanzheng/p/8896380.html)。我最初使用粘贴命令方法下载，由于国外的网站所以一直下不成功，但是文件目录下已经出来一个 0kb 的 Package Control 文件，需要把它删除了，再进行下载。或者就到其他地方下载这个文件然后拷贝到软件的对应目录下。这个安装好后就可以安装[很多方便的插件](https://github.com/jaywcjlove/awesome-mac/blob/master/editor-plugin-zh.md#sublime-text-plugin)了。
### 2.5. Webstorm 还是 VS Code
#### [Webstorm](https://www.jetbrains.com/webstorm/) 是 JetBrains 公司旗下一款 JavaScript 开发工具。学生免费。我以前去官网认证，但是发现 *根本没有我们学校*。好吧，还是找办法破解吧。
#### [Visual Studio Code](https://code.visualstudio.com) 是微软推出的免费/开源编辑器。我最近开始用这个了，界面上就比Webstorm简单很多，可以安装[很多插件](https://github.com/jaywcjlove/awesome-mac/blob/master/editor-plugin-zh.md#vscode-plugin)。可以考虑直接用 VS Code。
### 2.6. JavaScript 还是 jQuery
#### 个人觉得都差不多。我学的时候是用 JavaScript 的，jQuery 粗粗的看了一下，jQuery 就是封装了很多 JavaScript 方法，用 $ 符号去创建绑定元素，并提供链式函数执行的方法。
### 2.7. JSON 和 RegExp
#### [JSON](http://www.runoob.com/json/json-tutorial.html) 是一种 JavaScript 对象书写格式，多种语言都能支持。前后端可以通过这种格式通信一些数据。
#### [RegExp(正则表达式)](http://www.w3school.com.cn/js/js_obj_regexp.asp) 对象用于规定在文本中检索的内容。用的好，处理一些文本筛选替换会比较方便。
### 2.8. Markdown语言
#### Markdown 是一种纯文本格式的标记语言。通过简单的标记语法，它可以使普通文本内容具有一定的格式。在GitHub上看别人的项目都会有一个 README.md 文件，作为项目的说明文档。包括你现在看到的这篇也是我用 Markdown 语言现学现写的，非常简单，网上教程也很多。
### 2.9. 其他
#### 其他一些软件就自己探索吧，Chrome 上有一个网页尺子的插件，取色的插件，PS什么的自己看情况研究研究。
---
## 3. 一些网站和文章
### 3.1. 一些学习网站和有趣的网站
#### · [菜鸟教程](http://www.runoob.com) --各种教程分块很清晰。
#### · [W3Cschool](http://www.w3school.com.cn) --和菜鸟差不多，可以当工具书一样去查。
#### · [MDN Web Docs](https://developer.mozilla.org/zh-CN/) --这个上面的文档可以好好看看，API 接口那块内容很多，每天看一点，有个了解就好。
#### · [慕课网](http://www.imooc.com) --我的基础是在这个上面边看教程边练习的，上面也有一些不错的教程。
#### · [掘金](https://juejin.im) --一个综合的技术分享网站，有挺多前端的内容。
#### · [DevDocs](https://devdocs.io) --集合了多个开发者文档到一个简洁的 Web 界面。
#### · [Vue](https://cn.vuejs.org) --前端框架 Vue 2.0 。
#### · [React](https://react.docschina.org) --前端框架 React 。
#### · [AngularJS](https://angularjs.org) --前端框架 AngularJS 。
#### · [ECharts](https://echarts.baidu.com) --数据可视化的一个开源库。
#### · [Scrimba](https://scrimba.com) --一个可编程交互视频网站。
#### · [Element](http://element-cn.eleme.io/#/zh-CN) --基于 Vue 2.0 的前端组件库。
#### · [CodePen](https://codepen.io) --一个在线的前端代码编辑运行的网站。
#### · [Web安全色](http://www.bootcss.com/p/websafecolors/) --Web安全色可以了解一下。
### 3.2. 几篇看过觉得还不错的博文
#### · [ECMAScript 6 入门](http://es6.ruanyifeng.com)
#### · [学习CSS布局](http://zh.learnlayout.com)
#### · [三张图搞懂JavaScript的原型对象与原型链](https://www.cnblogs.com/shuiyi/p/5305435.html)
#### · [Javascript面向对象三大特性（封装性、继承性、多态性）详解及创建对象的各种方法](https://www.cnblogs.com/yanayana/p/6781166.html)
#### · [js之事件冒泡和事件捕获详细介绍](https://www.cnblogs.com/wu-web/p/6804514.html)
#### · [JavaScript开发者应懂的33个概念 ](https://github.com/stephentian/33-js-concepts)
#### · [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)
#### · [初探Promise](https://segmentfault.com/a/1190000007032448)
#### · [Awesome Mac](https://github.com/jaywcjlove/awesome-mac/blob/master/README-zh.md)
### 3.3. 找到的一些特效
#### . [30种css3 animation页面加载等待动画特效](http://www.17sucai.com/pins/demo-show?id=13948)
### 3.4. 自己当时总结了些东西
#### . [前端面试的一些总结](https://github.com/BlackCarbo/something_about_learning_FrontEnd/blob/master/FaceTest.txt)
#### . [JS常用函数](https://github.com/BlackCarbo/something_about_learning_FrontEnd/blob/master/jsfun.txt)
#### . [JS数组操作](https://github.com/BlackCarbo/something_about_learning_FrontEnd/blob/master/JS数组操作.png)
#### . [其它一些问题](https://github.com/BlackCarbo/something_about_learning_FrontEnd/blob/master/Q&A.txt)
---
## 尾声
#### 前端之路漫漫，大家共同学习共同进步，看到什么比较好的文章、有了什么比较好的经验，多多交流分享。
---

**ps：** 师妹，难得放假，别沉迷学习啦！让文杰带你去看看电影吃吃饭呀！！！:smirk:
