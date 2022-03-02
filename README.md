# 💻 前言

这不仅是一个技术博客，也会涉及到文学或者其他方向的东西，偶尔也会写生活（`正经人谁写日记啊`）:smirk:

笔者在学习过程中，有一段时间不知道该如何深入下去，活能干，就是不知道该学啥该怎么学，比较迷茫不知所措。相信这个问题有很多读者朋友也遇到过。
所以笔者想从基础开始整理出一条路线，在整理的过程中把好的资料分享给跟我碰到过一样问题的读者朋友。笔者坚信：**慢慢来、会很快** :octocat:

希望所有人都能被温柔以待~
# :book: 目录

> ## Javascript

- [var、let、const三者区别](https://juejin.cn/post/6925641096152399880)
- [new的原理是什么？通过new的方式创建对象和通过字面量创建有什么区别？](../../issues/55)
- [防抖和节流](../../issues/2)
- [可迭代对象](../../issues/5)
- [实现跨域的方式](../../issues/6)
- 数组
    - [类数组和数组的区别](../../issues/10)
    - [数组方法分类](../../issues/82)
    - [数组扁平化处理](../../issues/3)
    - [实现数组去重](../../issues/4)
    - [for...in、Object.keys、Object.getOwnPropertyNames 之间区别](../../issues/40)
    - [for of , for in 和 forEach,map 的区别](../../issues/9)
    - [深拷贝和浅拷贝](../../issues/39)
- 类型转换
    - [undefined与null的区别](https://www.ruanyifeng.com/blog/2014/03/undefined-vs-null.html)
    - [== 和 === 区别](../../issues/11)
    - [Object.is() 与 ===、== 区别](../../issues/30)
    - [JS中原始类型有哪几种？null 是对象吗？原始数据类型和复杂数据类型有什么区别？](../../issues/43)
    - [类型转换规则](../../issues/23)
    - [typeof 、instanceof是否正确判断类型? instanceof 原理](../../issues/51)
    - [让 (a == 1 && a == 2 && a == 3) 的值为true](../../issues/45)  
- 作用域、作用域链、预编译、执行上下文、闭包
    - [预编译、作用域与执行上下文](../../issues/28)
    - [作用域链](../../issues/77)
    - [闭包](../../issues/78)  
- this指向
    - [this的绑定规则、场景](../../issues/12)
    - [call,aplly和bind的区别及实现原理](../../issues/79)
- 原型、原型链、继承
    - [原型](../../issues/52)
    - [原型链解决的是什么问题？prototype 和__proto__区别是什么？](../../issues/19)
    - [继承的七种方式](../../issues/53)
- Promise系列
    - [Promise源码学习](../../issues/1)
    - [使用Promise实现红绿灯交替重复亮](../../issues/46)
- 懒加载
    - [图片懒加载(lazyload)](../../issues/81)
    - [路由按需加载（懒加载）的3种方式：vue异步组件require()、es提案的import()、webpack的require.ensure()](../../issues/62)
- 代理拦截
    - [Proxy 与 Object.defineProperty区别](../../issues/29)
    - [反射机制](https://www.cnblogs.com/Leophen/p/14838608.html)[及Reflect](https://zhuanlan.zhihu.com/p/92700557)
- 二进制
    - [Blob、ArrayBuffer和Buffer](https://juejin.cn/post/6992205283732766750)
- 存储
    - [前端存储之 cookie、localStorage、sessionStorage 和 indexedDB](../../issues/83)
    - [LHS和RHS查询](../../issues/13)
    - [基于 Localstorage 设计一个 1M 的缓存系统，需要实现缓存淘汰机制](../../issues/42)
- [String() 与 new String() 的差异](../../issues/14)
- [内存空间](../../issues/15)
- [4类常见内存泄漏及如何避免](../../issues/16)
- [如何处理十万级别的大量数据 ？](../../issues/18)
- [ES6新的特性](../../issues/20)
- [async / await](../../issues/21)
- [requestAnimationFrame 和 setTimeout/setInterval 区别](../../issues/22)
- [模块化：ES6、Commond、AMD、CMD](../../issues/24)
- [浏览器事件代理机制：捕获、冒泡](../../issues/25)
- [跨页面通信](https://juejin.cn/post/6844903811232825357#heading-3)
- [自定义事件](../../issues/26)
- [js异步加载方式](../../issues/27)
- [立即执行函数（IIFE）](../../issues/76)
- [10 个 Ajax 同时发起请求，全部返回展示结果，并且至多允许三次失败](../../issues/41)
- [空值合并运算符 '??'](https://zh.javascript.info/nullish-coalescing-operator)
- [0.1 + 0.2不等于0.3](../../issues/17)
- [JS文件：读取与拖拽、转换bsae64、预览、FormData上传、七牛上传、分割文件](https://github.com/amandakelake/blog/issues/40)

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

> ## 计算机网络
- [网络模型及其每层有哪些协议](../../issues/86)
- [HTTP 常见的状态码和适用场景](../../issues/87)
- [TCP、UDP的区别，TCP如何实现可靠传输，UDP如何改进实现可靠传输](../../issues/88)
- [三次握手、四次挥手及其涉及的相关问题](https://juejin.cn/post/6844903958624878606)
- [简单请求、复杂请求、预检请求](https://github.com/amandakelake/blog/issues/62)
- [HTTP headers和HTTP request methods](../../issues/7)
- [HTTP/0.9、HTTP/1.0、HTTP/1.1、HTTP/2、HTTP/3、websocket之间的区别](../../issues/57)
- [Session、Cookie、Token、JWT区别](https://juejin.cn/post/6844904115080790023)、[分布式Session一致性的4种解决方案](https://segmentfault.com/a/1190000022404396)
- [ajax、axios、fetch对比](https://zhuanlan.zhihu.com/p/58062212)
- [Axios 详解](https://juejin.cn/post/6863745313711226887)
- [HTTPS](https://segmentfault.com/a/1190000021494676)
#### 缓存
- [彻底理解浏览器的缓存机制](https://juejin.cn/post/6844903593275817998)
- [图解 Http 缓存控制之 max-age=0、no-cache、no-store 区别](https://zhuanlan.zhihu.com/p/55623075)

> ## 浏览器
#### 架构
- [浏览器架构，共四部分](https://cloud.tencent.com/developer/article/1806716)
#### 渲染
- [浏览器的渲染原理](https://coolshell.cn/articles/9666.html)
- [回流与重绘 (Reflow & Repaint)](https://juejin.cn/post/6844903569087266823)
#### JS执行机制
- [事件循环EvenLoop](../../issues/31)
- [从浏览器多进程到JS单线程](https://segmentfault.com/a/1190000012925872)
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
- [MVC、MVP、MVVM的区别](https://www.ruanyifeng.com/blog/2015/02/mvcmvp_mvvm.html)
- [Vue2.0和Vue3.0的区别](../../issues/69)
- [v-if和v-show的区别](../../issues/85)
- [watch和computed的区别](../../issues/84)
- [Vue中的diff算法](../../issues/71)
- [Vue生命周期](../../issues/65)；[父子组件、兄弟组件、宏mixins组件生命周期](https://juejin.cn/post/6844903602356502542)
- [为什么data属性是一个函数而不是一个对象？](../../issues/91)
- [动态给vue的data添加一个新的属性时界面不刷新？怎样解决？](https://github.com/febobo/web-interview/issues/10)
- [Vue 组件为何采用异步渲染-nextTick的实现原理](https://juejin.cn/post/6899822303022956552)
- [Mixins（混入）](https://segmentfault.com/a/1190000015698391)[及源码分析](https://github.com/febobo/web-interview/issues/15)
- 双向绑定原理
    - [数据响应(数据劫持)](../../issues/58)
- [vue中8种组件通信方式](https://juejin.cn/post/6844903887162310669)
- [vue-router](../../issues/38)
- [按需加载的3种方式：vue异步组件require()、es提案的import()、webpack的require.ensure()](../../issues/62)
- [插件 Vue.use(plugin) 的原理和使用](../../issues/64)
- [Vue 自定义指令Vue.directive](https://github.com/febobo/web-interview/issues/21)
- [为什么使用key](../../issues/66)
- [为什么避免 v-if 和 v-for 一起用](../../issues/70)
- [Vue 动态绑定样式的方式](../../issues/67)
- [Vue 插槽(slot)](https://github.com/febobo/web-interview/issues/16)
- [keep-alive缓存组件](https://juejin.cn/post/6844903918313406472)[、keep-alive缓存后怎么更新](../../issues/92)
- [Vue动态组件实现tab页切换](https://segmentfault.com/a/1190000018018502)
- [Vuex 简单介绍](../../issues/63)

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

> ## 操作系统
- [线程与进程的区别，各自之间如何通信](../../issues/89)
- [死锁的产生原因和解决办法](../../issues/90)

> ## 工具
- [Swagger API规范](https://swagger.io/)
- [Jenkins 持续集成](https://www.jenkins.io/zh/doc/pipeline/tour/getting-started/)

> ## 其它
- [MockingBird 只要5秒的原始讲话录音，就能克隆该声音，让它说出任意给定文本](https://github.com/babysor/MockingBird/blob/main/README-CN.md)
- [web前端面试](https://vue3js.cn/interview/)

> ## 图书馆
#### 文学
- [《周易正读》](./图书馆/文学/周易正读_徐丛.pdf)
- [《北京折叠》](./图书馆/文学/北京折叠.txt)
- [《遥远的救世主》](./图书馆/文学/遥远的救世主.TXT)，强烈推荐该书拍成的电视剧《天道》
- [《天幕红尘》](./图书馆/文学/天幕红尘.txt)
- [《背叛》](./图书馆/文学/背叛.txt)
- [《追风筝的人》](./图书馆/文学/追风筝的人.pdf)
- [词文摘录](../../issues/80)
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
#### 英语
- [《硅谷第一季中英剧本》](./图书馆/英语/硅谷第一季中英剧本.pdf)
