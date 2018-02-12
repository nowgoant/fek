## 导航
- [前端代码规范](#前端代码规范)
- [前端开发IDE](#前端开发ide)
- [现代前端工具](#现代前端工具)
- [前端知识自我修养](#前端知识自我修养)
- [CSS](#css)
- [JS](#js)
- [动画](#动画)
- [Node使用工具](#NodeUtility)
- [XSS](#xss)
- [Frontend Boilerplate](#frontend-boilerplate)
- [Web性能优化](#web性能优化)
- [面试](#front-end-web-development-interview-question)
- [UED官网](#ued官网)
- [机器学习](#机器学习)
- [其他](#其他)
- [各种坑](https://github.com/nowgoant/fek/tree/master/keng)

### 前端代码规范
 - [Code Guide by @AlloyTeam-materliu](http://materliu.github.io/code-guide/)腾讯AlloyTeam团队贡献
 - [JavaScript Style Guide](https://github.com/airbnb/javascript) airbnb贡献

### 前端开发IDE
 1.[Sublime 3](http://www.sublimetext.com/3),[视频教程](http://www.imooc.com/index/search?words=sublime)
插件：
 - [Package Control](https://packagecontrol.io/packages/Package%20Control) 插件包管理（安装，查询，卸载）
 - [Emmet](https://packagecontrol.io/packages/Emmet) 支持[zen Coding](http://www.zjgsq.com/1062.html)快速编写HTML/CSS
 - [SideBarEnhancements](https://packagecontrol.io/packages/SideBarEnhancements) sidebar的扩展，增加（新建，新文件夹，打开当期文件位置等等）
 - [SublimeLinter](https://packagecontrol.io/packages/SublimeLinter)借助[ SublimeLinter 编写高质量的 JavaScript & CSS 代码](http://www.cnblogs.com/lhb25/archive/2013/05/02/sublimelinter-for-js-css-coding.html)需要借助于[Node](http://nodejs.org/)和[jshint](http://jshint.com/docs/#options)
 - 代码格式工具[Tag](https://packagecontrol.io/packages/Tag)只适用于HTML/XML;[HTML-CSS-JS Prettify](https://packagecontrol.io/packages/HTML-CSS-JS%20Prettify)见闻知意了，依赖于Node
 - [Tortoise​SVN](https://packagecontrol.io/packages/TortoiseSVN) ，你懂得
 - [Material Theme](https://github.com/equinusocio/material-theme) Material Theme, the most epic theme for Sublime Text 3 by Mattia Astorino

2.[Atom](https://atom.io/)
 - [awesome-atom](https://github.com/mehcode/awesome-atom) A curated list of delightful Atom packages and resources.
 
3.[webstorm](http://www.jetbrains.com/webstorm/)

### [现代前端工具](http://tooling.github.io/book-of-modern-frontend-tooling/)
 **国外篇**

 - [Yeoman](http://yeoman.io/)：现代WebApp脚手架工具，带有很多generator生成器，比如：generator-webapp,generator-mobile移动优先，[慕课网视频教程](http://www.imooc.com/learn/30)[老湿很牛](https://github.com/materliu) 
 - [Grunt](http://www.gruntjs.net/)：javasript的build工具，开发常用的例如压缩（minification）、编译、单元测试、linting等;
 - [Bower](http://www.baidu.com/s?wd=Bower&rsv_spt=1&issp=1&f=8&rsv_bp=0&rsv_idx=2&ie=utf-8&tn=baiduhome_pg&rsv_enter=1&inputT=2483)：javascript库管理工具
 - [Gulp](http://gulpjs.com/)：Grunt竞争对手，Grunt的插件职责不单一，Gulp针对这方面有所改进，后起之秀有架构方便的优势
 - [webpack](https://github.com/webpack/webpack) 
 - [gulp-starter](https://github.com/vigetlabs/gulp-starter)A delicious blend of gulp tasks combined into a configurable asset pipeline and static site builder
 
**国内篇**
 
  - [JDF](https://github.com/putaoshu/jdf) 京东前端集成解决方案
  - [F.I.S](http://fis.baidu.com/) 前端集成解决方案,百度FEX团队贡献，[视频教程（有惊喜）](http://www.imooc.com/learn/220)，相对Grunt和Gulp容易入手，访问没有限制
  - [Spirit](http://alloyteam.github.io/Spirit/)腾讯移动Web整体解决方案，腾讯Alloyteam团队贡献

 
### 前端知识自我修养
 **国内篇**
 
  - [前端技能](https://github.com/JacksonTian/fks),收集前端大部分知识
  - [mobileTech](https://github.com/RubyLouvre/mobileTech) 移动学习资料，大牛[@司徒正美](https://github.com/RubyLouvre) 参与贡献，[Avalon](http://avalonjs.github.io/)的创建人，[JavaScript架构设计](http://item.jd.com/11436424.html?utm_source=baidu&utm_medium=cpc&utm_campaign=&utm_term=baidu_370197436_0_s3222454d038f4a0ab54.64890394)的作者
  - [GMU](https://github.com/fex-team/GMU)基于zepto的ui组件库，适用于移动端
  - [fetool](https://github.com/nieweidong/fetool)大前端的瑞士军刀，只记录有用的
  - [skill-map](https://github.com/TeamStuQ/skill-map) StuQ 技能图谱

 
**国外篇**
 
  - [Awesome-javascript](https://github.com/sorrycc/awesome-javascript) 收集了很多适用、流行库，英文版，可惜没有中文
  - [You-Dont-Know-JS](https://github.com/getify/You-Dont-Know-JS) 深入介绍的作用域，闭包，异步，性能,ES6等等
  - [Awesome-nodejs](https://github.com/sindresorhus/awesome-nodejs) node插件集合
  - [Front-End-Dev](https://github.com/dypsilon/frontend-dev-bookmarks) 大就“任性”
  - [FrontEnd-stuff](https://github.com/moklick/frontend-stuff) 
  - [awesome](https://github.com/sindresorhus/awesome) 一个世界


### CSS
1.Animate

 ***国内篇***

- [Css3动画属性总汇](http://css3lib.alloyteam.com/uilib/animation/demo1/index.html)
- [CSS3 UI 库](http://css3lib.alloyteam.com/): Tencent Alloyteam

***国外篇***

- [Animate.css](https://github.com/daneden/animate.css):A cross-browser library of CSS animations. As easy to use as an easy thing.
- [bounce.js](https://github.com/tictail/bounce.js): Create beautiful CSS3 powered animations in no time
- [magic](https://github.com/miniMAC/magic) CSS3 Animations with special effects
- [font-awesome-animation](https://github.com/l-lin/font-awesome-animation) Simple animations using FontAwesome and some CSS3


2.FlexBox
 - [solved-by-flexbox](https://github.com/philipwalton/solved-by-flexbox) A showcase of problems once hard or impossible to solve with CSS alone, now made trivially easy with Flexbox.
 - [flexibility](https://github.com/10up/flexibility?utm_campaign=CodeTengu&utm_medium=web&utm_source=CodeTengu_23) Use flexbox while supporting older Internet Explorers
 - [FLEXBOX FROGGY](http://flexboxfroggy.com/?utm_campaign=CodeTengu&utm_medium=web&utm_source=CodeTengu_20) 用游戏学习 CSS Flexbox

3.Loading集合
 - [SpinKit](https://github.com/tobiasahlin/SpinKit)
 - [css-loaders](https://github.com/lukehaas/css-loaders)
 - [loaders](https://github.com/ConnorAtherton/loaders.css)
 - [loading-svg](https://github.com/jxnblk/loading)
 
4.Framework 
 - [Materialize](https://github.com/Dogfalo/materialize) Materialize, a CSS Framework based on Material Design
 

### JS
1.Scroll
  - [scrollreveal.js](https://github.com/jlmakes/scrollreveal.js) Easy scroll animations for web and mobile browsers. 
  - [scroller](https://github.com/zynga/scroller) Accelerated panning and zooming for HTML and Canvas
  - [syncscroll.js](https://github.com/asvd/syncscroll) Sync scroll
  
2.Chart
  - [awesome-d3](https://github.com/wbkd/awesome-d3)
  - [Circular canvas loader](http://codepen.io/pimskie/pen/rtijd)
  - [DwtHr](http://codepen.io/ZetaHunter/pen/DwtHr)
  
3.Drag and drop
  - [dragula](https://github.com/bevacqua/dragula) Drag and drop so simple it hurts 

4.animations
  - [dynamics.js](https://github.com/michaelvillar/dynamics.js) Javascript library to create physics-based CSS animations

5.剪切板
  - [clipboard](https://github.com/zenorocha/clipboard.js) Modern copy to clipboard. No Flash. Just 2kb

6.金融
  - [accounting.js](https://github.com/openexchangerates/accounting.js) A lightweight JavaScript library for number, money and currency formatting
  - [card](https://github.com/jessepollak/card) 银行卡格式化
  - [cleave.js](https://github.com/nosir/cleave.js) 银行卡、时间、数字、手机等格式化，支持CommonJS / AMD和React组件
  - [Numeral-js](https://github.com/adamwdraper/Numeral-js) A javascript library for formatting and manipulating numbers.
  - [mathjs](https://github.com/josdejong/mathjs) An extensive math library for JavaScript and Node.js

7.图片处理
  - [剪切](https://github.com/jwagner/smartcrop.js/) 剪切图片中主要内容
  - [grade](https://github.com/benhowdle89/grade) 提取图片主题色，并生成过渡的渐变
  - [gradients](https://github.com/sarcadass/granim.js) 渐变颜色
  - [guetzli](https://github.com/google/guetzli) Google，Perceptual JPEG encoder

8.SVG
  - [Snap.svg](https://github.com/adobe-webplatform/Snap.svg) The JavaScript library for modern SVG graphics.
  - [svg.js](http://svgjs.com/) A lightweight library for manipulating and animating SVG
  - [awesome-svg](https://github.com/willianjusten/awesome-svg)
  
9.滑动组件
  - [Swiper](https://github.com/nolimits4web/Swiper) Most modern mobile touch slider with hardware accelerated transitions
  - [iSlider](https://github.com/peunzhang/iSlider) Smooth mobile touch slider for Mobile WebApp, HTML5 App, Hybrid App
  - [fullpage](https://github.com/peunzhang/fullpage) For desktop(ie5.5+) or mobile webApp without jQuery,create full screen pages fast and simple.
  - [lightgallery.js](https://github.com/sachinchoolur/lightgallery.js)Full featured JavaScript image & video gallery. No dependencies  

10.上传
  - [uppie](https://github.com/silverwind/uppie) Cross-browser directory uploads made easy

11.WebSQL
  - [WebSqlSync](https://github.com/orbitaloop/WebSqlSync) Synchronize a local WebSQL DB to a server
  

12.正则表达式
  - [JSVerbalExpressions](https://github.com/VerbalExpressions/JSVerbalExpressions) JavaScript Regular expressions made easy
 
13.框架和库
  - [React](https://github.com/nowgoant/fek/tree/master/react)
  - [awesome-vue](https://github.com/vuejs/awesome-vue)

14.JSON
  - [lave](https://github.com/jed/lave) Why not just use JSON.stringify?


### 动画
  - [gka](https://github.com/gkajs/gka) 一款高效、高性能的帧动画生成工具


### NodeUtility
 - [query-string](https://github.com/sindresorhus/query-string) Parse and stringify URL query strings
 - [lodash](https://github.com/lodash/lodash) A modern JavaScript utility library delivering modularity, performance, & extras


### XSS
  - [js-xss](https://github.com/leizongmin/js-xss) 根据白名单过滤HTML(防止XSS攻击)
 

### 前端单元测试工具
 - [totoro](https://github.com/fengmk2/totoro) 简单稳定的前端单元测试工具
 - [PhantomJS](http://phantomjs.org/)支持web而不需浏览器支持，其快速，原生支持各种Web标准：DOM 处理, CSS 选择器, JSON, Canvas, 和SVG。PhantomJS可以用于页面自动化，网络监测，网页截屏，以及无界面测试等,[更多...](http://www.woiweb.net/phantomjs-quick-use-tutorials.html)
 - [Mocha](https://mochacn.github.io/)是一个基于node.js和浏览器的集合各种特性的Javascript测试框架，并且可以让异步测试也变的简单和有趣

### 在线图书/学校
 - [FreeCodeCamp](https://github.com/FreeCodeCamp/freecodecamp) The http://FreeCodeCamp.com open source codebase and curriculum. Learn to code and help nonprofits.
 - [free-programming-books-zh](https://github.com/vhf/free-programming-books/blob/master/free-programming-books-zh.md): 汇集了各种编程语言
 - 

### Web性能优化
  - [前端性能优化-基础知识认知](http://www.imooc.com/learn/580)
  - [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/) 使您的网页在所有设备上都能快速加载  
  - [Benchmark.js](https://github.com/bestiejs/benchmark.js) 性能测试
  - [jsperf](https://jsperf.com/browse) 提供了一个简便的方式来创建和共享测试用例
 
### GitHub
  - [GitHub秘籍](https://github.com/tiimgreen/github-cheat-sheet/blob/master/README.zh-cn.md)

### Frontend Boilerplate 
  - [Frontend Boilerplate](https://github.com/tj/frontend-boilerplate) webpack-react-redux-babel-autoprefixer-hmr-postcss-css-modules-rucksack-boilerplate
  - [react-boilerplate](https://github.com/mxstbr/react-boilerplate) :fire: Quick setup for performance orientated, offline-first React.js applications featuring Redux, hot-reloading, PostCSS, react-router, ServiceWorker, AppCache, FontFaceObserver and Mocha.

### Front-end-Web-Development-Interview-Question
 - [Front-end-Web-Development-Interview-Question](https://github.com/paddingme/Front-end-Web-Development-Interview-Question) 前端开发面试题大收集
 - [Front-end-Developer-Interview-Questions](https://github.com/h5bp/Front-end-Developer-Interview-Questions) A list of helpful front-end related questions you can use to interview potential candidates, test yourself or completely ignore.
 - [ont-end-questions-to-the-interview-stage](https://github.com/AutumnsWind/Front-end-questions-to-the-interview-stage) 最全前端开发面试问题及答案整理
 
### UED官网
---
  - [百度FEX](http://fex.baidu.com/)
  - [阿里UED](http://www.aliued.com/)
  - [淘宝UED](http://ued.taobao.org/blog/)
  - [腾讯isux](http://isux.tencent.com/)
  - [腾讯cdc](http://cdc.tencent.com/)
  - [去哪儿UED](http://ued.qunar.com/)
  - [其他](http://www.douban.com/group/topic/52385245/)
  - 

### 机器学习
---
  - [awesome-machine-learning-cn] (https://github.com/jobbole/awesome-machine-learning-cn)机器学习资源大全中文版，包括机器学习领域的框架、库以及软件

### 其他
----
  - [Awesome](https://github.com/sindresorhus/awesome) 收集了平台（Platforms),编程语言（Programming languages)，计算机科学（Computer science)，大数据（Big Data）等等技能
  - [HTML,CSS and JS最佳实践](https://github.com/bendc/frontend-guidelines)
  - 技术视频教程:[慕课网](http://www.imooc.com/)
  - [free-programming-books](https://github.com/vhf/free-programming-books) Freely available programming books，支持多种语言
  - [F2E-Tutorial-Collect](https://github.com/jobbole/awesome-machine-learning-cn) 前端资料整理
