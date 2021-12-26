# 💻 前言

这不仅是一个技术博客，也会涉及到文学或者其他方向的东西，偶尔也会写生活（`正经人谁写日记啊`）:smirk:

笔者在学习过程中，有一段时间不知道该如何深入下去，活能干，就是不知道该学啥该怎么学，比较迷茫不知所措。相信这个问题有很多读者朋友也遇到过。
所以笔者想从基础开始整理出一条路线，在整理的过程中把好的资料分享给跟我碰到过一样问题的读者朋友。笔者坚信：**慢慢来、会很快** :octocat:

希望所有人都能被温柔以待~
# :book: 目录

> ## Javascript

- [var、let、const三者区别](https://juejin.cn/post/6925641096152399880)
- [继承的七种方式](../../issues/53)
- [new运算符的执行过程](../../issues/55)
- [Promise源码学习](../../issues/1)
- [防抖和节流](../../issues/2)
- [数组扁平化处理](../../issues/3)
- [实现数组去重](../../issues/4)
- [可迭代对象](../../issues/5)
- [实现跨域的方式](../../issues/6)
- 类型转换
    - [== 和 === 区别](../../issues/11)
    - [Object.is() 与 ===、== 区别](../../issues/30)
    - [JS中原始类型有哪几种？null 是对象吗？原始数据类型和复杂数据类型有什么区别？](../../issues/43)
    - [类型转换规则](../../issues/23)
    - [判断数据类型](../../issues/8)
    - [typeof 、instanceof是否正确判断类型? instanceof 原理](../../issues/51)
    - [让 (a == 1 && a == 2 && a == 3) 的值为true](../../issues/45)
- [for of , for in 和 forEach,map 的区别](../../issues/9)
- [类数组和数组的区别](../../issues/10)
- [原型](../../issues/52)
- [this指向](../../issues/12)
- [LHS和RHS查询](../../issues/13)
- [String() 与 new String() 的差异](../../issues/14)
- [内存空间](../../issues/15)
- [4类常见内存泄漏及如何避免](../../issues/16)
- [如何处理十万级别的大量数据 ？](../../issues/18)
- [原型链解决的是什么问题？prototype 和__proto__区别是什么？](../../issues/19)
- [ES6新的特性](../../issues/20)
- [async / await](../../issues/21)
- [requestAnimationFrame 和 setTimeout/setInterval 区别](../../issues/22)
- [模块化：ES6、Commond、AMD、CMD](../../issues/24)
- [浏览器事件代理机制的原理](../../issues/25)
- [跨页面通信](https://juejin.cn/post/6844903811232825357#heading-3)
- [自定义事件](../../issues/26)
- [js异步加载方式](../../issues/27)
- [预编译、作用域与执行上下文](../../issues/28)
- [Proxy 与 Object.defineProperty区别](../../issues/29)
- [深拷贝和浅拷贝](../../issues/39)
- [反射机制](https://www.cnblogs.com/Leophen/p/14838608.html)[及Reflect](https://zhuanlan.zhihu.com/p/92700557)
- [for...in、Object.keys、Object.getOwnPropertyNames 之间区别](../../issues/40)
- [10 个 Ajax 同时发起请求，全部返回展示结果，并且至多允许三次失败](../../issues/41)
- [基于 Localstorage 设计一个 1M 的缓存系统，需要实现缓存淘汰机制](../../issues/42)
- [空值合并运算符 '??'](https://zh.javascript.info/nullish-coalescing-operator)
- [使用Promise实现红绿灯交替重复亮](../../issues/46)
- [0.1 + 0.2不等于0.3](../../issues/17)

> ## HTML
- [对HTML5语义化的理解](../../issues/44)
- [meta、link之预加载图片、文件](../../issues/49)
- [SPA单页面优缺点及SPA首屏加载速度慢解决办法](../../issues/68)
- [HTML meta标签](https://segmentfault.com/a/1190000004279791)
- [disabled和readonly的区别](../../issues/72)

> ## CSS
- [link和@import的区别](../../issues/48) 
- [link为什么要放在body前](https://zhuanlan.zhihu.com/p/46387951)
- [display、visibility、opacity、position隐藏元素的区别](../../issues/75)
- [块级元素和行内元素及其区别](../../issues/73)
- [inline、block、inline-block和float区别](../../issues/37) 
- [盒模型与box-sizing](https://www.jianshu.com/p/51e5bb7e9fa2)
- [position的五个属性值](https://www.ruanyifeng.com/blog/2019/11/css-position.html)
- [margin-left: auto元素右对齐以及margin: 0 auto水平居中的原理](../../issues/74)
- [Grid vs Flex](https://zhuanlan.zhihu.com/p/46757975)
- [BFC、IFC、margin塌陷、margin合并](../../issues/47)
- [清除浮动](../../issues/50)
- [响应式布局](../../issues/32)
- [样式的继承性和权重计算](../../issues/33)
- [元素居中显示](../../issues/36) 
- [less基本知识](../../issues/34) 

> ## HTTP
- [HTTP headers和HTTP request methods](../../issues/7)
- [HTTP/0.9、HTTP/1.0、HTTP/1.1、HTTP/2之间的区别](../../issues/57)
- [Session、Cookie、Token区别](https://juejin.cn/post/6844904115080790023)、[分布式Session一致性的4种解决方案](https://segmentfault.com/a/1190000022404396)
- [Axios 详解](https://juejin.cn/post/6863745313711226887)

> ## 浏览器
#### 架构
- [浏览器架构，共四部分](https://cloud.tencent.com/developer/article/1806716)
#### 渲染
- [浏览器的渲染原理](https://coolshell.cn/articles/9666.html)
- [回流与重绘 (Reflow & Repaint)](https://juejin.cn/post/6844903569087266823)
#### JS执行机制
- [事件循环EvenLoop](../../issues/31)
- [从浏览器多进程到JS单线程](https://segmentfault.com/a/1190000012925872)
#### 缓存
- [彻底理解浏览器的缓存机制](https://juejin.cn/post/6844903593275817998)
- [图解 Http 缓存控制之 max-age=0、no-cache、no-store 区别](https://zhuanlan.zhihu.com/p/55623075)
#### 整体流程
- [从输入 URL 到页面加载完成的过程中都发生了什么事情？](https://fex.baidu.com/blog/2014/05/what-happen/)
- [当你在浏览器中输入 google.com 并且按下回车之后发生了什么？](https://github.com/skyline75489/what-happens-when-zh_CN)
#### 浏览器安全
- [Web 安全](https://segmentfault.com/a/1190000023396707)
#### 垃圾回收
- [V8垃圾回收机制、内存泄露](../../issues/56)

> ## 设计模式
- [工厂模式、构造函数模式、寄生构造函数模式、稳妥构造函数模式](../../issues/54)
- [观察者模式与发布订阅模式](../../issues/61)

> ## Vue
- [Vue中的diff算法](../../issues/71)
- [Vue生命周期](../../issues/65)；[父子组件、兄弟组件、宏mixins组件生命周期](https://juejin.cn/post/6844903602356502542)
- [Vue 组件为何采用异步渲染-nextTick的实现原理](https://juejin.cn/post/6899822303022956552)
- [Mixins （混入）](https://segmentfault.com/a/1190000015698391)
- [数据响应(数据劫持)](../../issues/58)
- [vue中8种组件通信方式](https://juejin.cn/post/6844903887162310669)
- [vue-router](../../issues/38)
- [按需加载的3种方式：vue异步组件require()、es提案的import()、webpack的require.ensure()](../../issues/62)
- [插件 Vue.use(plugin) 的原理和使用](../../issues/64)
- [Vue 自定义指令Vue.directive、directives](https://shq5785.blog.csdn.net/article/details/103874164)
- [为什么使用key](../../issues/66)
- [为什么避免 v-if 和 v-for 一起用](../../issues/70)
- [Vue 动态绑定样式的方式](../../issues/67)
- [Vue 插槽(slot)](https://juejin.cn/post/6844903920037281805)
- [Vue2.0和Vue3.0的区别](../../issues/69)
- [Vuex 简单介绍](../../issues/63)
- [Vue中keep-alive](https://juejin.cn/post/6844903918313406472)
- [Vue动态组件实现tab页切换](https://segmentfault.com/a/1190000018018502)

> ## Node
- [Node 定时器、Event Loop详解](http://www.ruanyifeng.com/blog/2018/02/node-event-loop.html)
- [PM2实用入门指南](https://www.cnblogs.com/chyingp/p/pm2-documentation.html)
- [Node.js 与 log4js](https://zhuanlan.zhihu.com/p/22110802)

> ## Koa
- [Koa与Express的区别](https://segmentfault.com/a/1190000024541526)

> ## Babel
- [Babel快速上手使用指南](https://juejin.cn/post/6844903858632654856)
- [Babel原理及插件开发](https://juejin.cn/post/6844903603983892487)
- [自己手写一个简单的babel插件](https://github.com/TieMuZhen/babel-plugin-debug)

> ## Webpack
- [Webpack整体大纲](../../issues/59)
- [Loader](../../issues/35)

> ## TypeScript
- [TypeScript 入门教程](https://ts.xcatliu.com/)
- [TypeScript 的另一面：类型编程](https://juejin.cn/post/6989796543880495135)

> ## Redis

> ## 图形处理
- [threejs](https://github.com/puxiao/threejs-tutorial)

> ## 监控
- [monitor](https://github.com/clouDr-f2e/monitor)，用于收集页面的用户点击行为、路由跳转、接口报错、代码报错、并上报服务端
- [如何进行 web 性能监控？](http://www.alloyteam.com/2020/01/14184/#prettyPhoto)
- [美团可视化埋点方案](https://tech.meituan.com/2019/08/15/mtflexbox-automation-buried-point-exploration.html)

> ## 微前端
- [微前端实践讲解](https://juejin.cn/post/6844903943873675271)

> ## Nginx
- [Nginx基本梳理](../../issues/60)

> ## 性能优化
- [QPS、TPS、并发用户数、吞吐量关系](https://zhuanlan.zhihu.com/p/111914041)
- [最新性能指标](https://juejin.cn/post/6850037270729359367)
- [前端性能优化 24 条建议（2020）](https://juejin.cn/post/6892994632968306702)
- [前端性能优化之旅](https://alienzhou.github.io/fe-performance-journey/)

> ## 工具
- [Swagger API规范](https://swagger.io/)
- [Jenkins 持续集成](https://www.jenkins.io/zh/doc/pipeline/tour/getting-started/)

> ## 图书馆
#### 前端
- [《你不知道的JavaScript（上卷）》](./图书馆/编程/你不知道的JavaScript（上卷）.pdf)
- [《你不知道的JavaScript（中卷）》](./图书馆/编程/你不知道的JavaScript（中卷）.pdf)
- [《你不知道的JavaScript（下卷）》](./图书馆/编程/你不知道的JavaScript（下卷）.pdf)
- [《JavaScript函数式编程》](./图书馆/编程/JavaScript函数式编程.pdf)
#### 后端
- [Kafka](./图书馆/编程/尚硅谷大数据技术之Kafka.pdf)
#### 人工智能
- [《智能Web算法中文版》](./图书馆/编程/人工智能/智能Web算法中文版.pdf)
- [《人工智能游戏编程真言》](./图书馆/编程/人工智能/人工智能游戏编程真言.pdf)
- [《游戏人工智能编程案例精粹》](./图书馆/编程/人工智能/游戏人工智能编程案例精粹.pdf.pdf)
#### 文学
- [《周易正读》](./图书馆/文学/周易正读_徐丛.pdf)
- [《北京折叠》](./图书馆/文学/北京折叠.txt)
- [《遥远的救世主》](./图书馆/文学/遥远的救世主.TXT)，强烈推荐该书拍成的电视剧《天道》
- [《天幕红尘》](./图书馆/文学/天幕红尘.txt)
- [《背叛》](./图书馆/文学/背叛.txt)
- [《追风筝的人》](./图书馆/文学/追风筝的人.pdf)
#### 英语
- [《硅谷第一季中英剧本》](./图书馆/英语/硅谷第一季中英剧本.pdf)
