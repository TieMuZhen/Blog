# 💻 前言

这不仅是一个技术博客，也会涉及到文学或者其他方向的东西，偶尔也会写生活（`正经人谁写日记啊`）:smirk:

笔者在学习过程中，有一段时间不知道该如何深入下去，活能干，就是不知道该学啥该怎么学，比较迷茫不知所措。相信这个问题有很多读者朋友也遇到过。
所以笔者想从基础开始整理出一条路线，在整理的过程中把好的资料分享给跟我碰到过一样问题的读者朋友。笔者坚信：**慢慢来、会很快** :octocat:

希望所有人都能被温柔以待~
# :book: 目录

> ## Javascript
- [ES6新的特性](../../issues/20)
- [本地对象、内置对象、宿主对象](../../issues/195)
- [var、let、const三者区别](https://juejin.cn/post/6925641096152399880)
- [纯函数、函数式编程、柯里化](../../issues/136)
- [值的不可变性](https://wizardforcel.gitbooks.io/functional-light-js/content/ch6.html)
- [ES6中的装饰器Decorator](../../issues/96)
- [ES6的解构赋值](../../issues/128)
- [可迭代对象](../../issues/5)
- [String() 与 new String() 的差异](../../issues/14)
- [内存空间](../../issues/15)
- [4类常见内存泄漏及如何避免](../../issues/16)
- 事件循环
  - [事件循环试题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/7)
  - [事件循环EvenLoop](../../issues/31)
  - [requestAnimationFrame 和 setTimeout/setInterval 区别](../../issues/22)
- Object
  - [assign、keys、getOwnPropertyDescriptor、create、defineProperty](../../issues/167)
  - [entries、FromEntries](../../issues/168)
  - [freeze(冻结)、seal(封闭)](https://zhuanlan.zhihu.com/p/145153864)
  - [preventExtensions与freeze、seal区别](../../issues/169)
- 数组
  - [类数组和数组的区别](../../issues/10)
  - [数组方法分类](../../issues/82)
  - [数组扁平化处理](../../issues/3)
  - [实现数组去重](../../issues/4)
  - [for...in、Object.keys、Object.getOwnPropertyNames 之间区别](../../issues/40)
  - [for of , for in 和 forEach,map 的区别](../../issues/9)
  - [手写forEach、map、reduce、filter](../../issues/170)
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
  - [作用域题目汇总](../../issues/184)
- this指向
  - [this的绑定规则、场景](../../issues/12)
  - [call,aplly和bind的区别及实现原理](../../issues/79)
- 原型、原型链、继承
  - [原型](../../issues/52)
  - [原型链解决的是什么问题？prototype 和__proto__区别是什么？](../../issues/19)
  - [new的原理是什么？通过new的方式创建对象和通过字面量创建有什么区别？](../../issues/55)
  - [继承的七种方式](../../issues/53)
- [面向对象编程特点、js实现面向对象(封装、继承、多态)、重载（不属于面向对象）](../../issues/200)
- Promise和async / await
  - [async / await 的错误处理方法](https://github.com/davidlin88/blogs/issues/2)
  - [async / await以及和promise、生成器Generator的区别](../../issues/21)
  - [Promise实现并发控制](../../issues/137)
  - [使用Promise实现红绿灯交替重复亮](../../issues/46)
  - [封装带有超时（重试）机制的异步请求工具函数](../../issues/177)
  - [async 和 await 是怎么工作的？——生成器与协程](../../issues/182)
  - [async / await 底层的 generator 实现](../../issues/183)
  - [Promise源码学习](../../issues/1)
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
  - [Cookie、Session、Token(JWT)区别](https://juejin.cn/post/6844904115080790023)、[分布式Session一致性的4种解决方案](https://segmentfault.com/a/1190000022404396)
  - [如何防止JWT被盗](https://cloud.tencent.com/developer/article/1424531)
  - [为什么在京东搜索的商品，会展示在抖音广告上](http://www.woshipm.com/marketing/3259963.html)
  - [跨tab页sessionStorage共享](../../issues/175)
  - [LHS和RHS查询](../../issues/13)
  - [基于 Localstorage 设计一个 1M 的缓存系统，需要实现缓存淘汰机制](../../issues/42)
- [防抖和节流](../../issues/2)
- [同源策略以及实现跨域的方式](../../issues/6)
- 模块化
  - [CommonJS循环加载](../../issues/199)
  - [模块化：ES6、Commond、AMD、CMD](../../issues/24)
  - [Commonjs 和 Es Module](https://juejin.cn/post/6994224541312483336)
  - [js异步加载方式](../../issues/27)
- 事件代理机制
  - [浏览器事件代理机制：捕获、冒泡](../../issues/25)
  - [onclick与addEventListener区别](../../issues/190)
- [跨页面通信](https://juejin.cn/post/6844903811232825357#heading-3)
- [自定义事件](../../issues/26)
- [立即执行函数（IIFE）](../../issues/76)
- 应用 
  - [颜色的十进制与十六进制互转（正则）](../../issues/129)
  - [0.1 + 0.2不等于0.3？精度丢失问题](../../issues/17)
  - [10 个 Ajax 同时发起请求，全部返回展示结果，并且至多允许三次失败](../../issues/41)
  - [编写一个具有模糊查询功能的搜索框](../../issues/189)
  - [手写轮播图](https://github.com/TieMuZhen/cycle-swiper)
  - [如何实现上拉加载，下拉刷新？](../../issues/97)
  - [如何处理十万级别的大量数据 ？](../../issues/18)
  - [文件上传、下载、分片上传、断点续传](https://juejin.cn/post/6844904142251507720)
  - [大文件上传如何做断点续传？](https://github.com/febobo/web-interview/issues/89)
  - [单点登录及常见解决方案原理（CAS、oauth2、JWT）](https://blog.csdn.net/baolingye/article/details/104197535)
  - [遍历DOM树，拿到每个路径的便签和当前经过的便签的最大data-v的值](../../issues/192)

> ## HTML
- [HTML5新增了哪些特性？](https://juejin.cn/post/6988039257587712008)
- [对HTML5语义化的理解](../../issues/44)
- [meta、link之预加载图片、文件](../../issues/49)
- [SPA单页面优缺点及SPA首屏加载速度慢解决办法](../../issues/68)
- [HTML meta标签](https://segmentfault.com/a/1190000004279791)
- [disabled和readonly的区别](../../issues/72)

> ## CSS
- [css3的新特性](https://segmentfault.com/a/1190000010780991)
- [CSS变量 var()](../../issues/196)
- [超过行数的文本用省略号替代](../../issues/178)
- [px、em、rem、vh、vw区别](../../issues/98) 
- [设备像素、css像素、设备独立像素、dpr、ppi 之间的区别](../../issues/99)
- [:first-child / :last-child、:first-of-type / :last-of-type、:nth-child(n) / :nth-last-child(n)的区别](../../issues/134)
- 盒模型
  - [盒模型与box-sizing](../../issues/131)
  - [BFC、IFC、margin塌陷、margin合并](../../issues/47)
  - [清除浮动](../../issues/50)
- [样式的继承性和权重计算](../../issues/33) 
- [修改element-ui组件默认样式](../../issues/194) 
- [line-height详解](https://segmentfault.com/a/1190000003038583)
- [display、visibility、opacity、position隐藏元素的区别](../../issues/75)
- [position的四个属性值](https://www.ruanyifeng.com/blog/2019/11/css-position.html)
- 行内元素、块级元素
  - [为什么图片下面总是多几个像素空白？](../../issues/193)
  - [块级元素和行内元素及其区别](../../issues/73)
  - [inline、block、inline-block和float区别](../../issues/37)
- 响应式
  - [响应式布局及经典多栏布局案例](../../issues/32)
  - [Flex](https://www.ruanyifeng.com/blog/2015/07/flex-grammar.html)vs[Grid](https://www.ruanyifeng.com/blog/2019/03/grid-layout-tutorial.html)、[Flex查询手册](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)、[Grid查询手册](https://css-tricks.com/snippets/css/complete-guide-grid/)
  - [使用flex布局，实现子盒子之间的间隔固定，子盒子可以随着父盒子的大小进行调整](../../issues/135)
- 元素居中
  - [margin-left: auto元素右对齐以及margin: 0 auto水平居中的原理](../../issues/74)
  - [元素居中显示](../../issues/36)
- 性能优化
  - [如何优化CSS来提高性能](../../issues/102)
  - [link和@import的区别](../../issues/48) 
  - [link为什么要放在body前](https://zhuanlan.zhihu.com/p/46387951)
- 动画
  - [CSS绘制三角形—border法](https://www.jianshu.com/p/9a463d50e441)
  - [transition、transform、animation三种方式实现css动画](../../issues/100)
  - [setInterval、setTimeOut、requestAnimationFrame三种方式实现js动画](https://juejin.cn/post/6971402961217912839)
- 预处理器
  - [less基本知识](../../issues/34) 

> ## 计算机网络
- [OSI七层模型及其每层有哪些协议](../../issues/86)
- [如何理解TCP/IP协议?](../../issues/114)
- [DNS协议是什么？说说DNS完整的查询过程?](../../issues/115)
- [如何理解CDN？说说实现原理？](../../issues/116)
- [从输入 URL 到页面加载完成的过程中都发生了什么事情？](../../issues/117)
- [HTTP/0.9、HTTP/1.0、HTTP/1.1、HTTP/2、HTTP/3、websocket之间的区别，HTTP 和 HTTPS 的区别](../../issues/57)
- [一个TCP连接可以发送多少个HTTP请求？](https://juejin.cn/post/7000173309509926925)
- [HTTP的KeepAlive是开启还是关闭？](../../issues/197)
- [content-type的类型、form-data如何传对象](../../issues/201)
- Request、Response
  - [request和response结构](../../issues/174)
  - [HTTP headers和HTTP request methods](../../issues/7)
  - [HTTP headers 之 host, referer, origin](https://juejin.cn/post/6844903954455724045)
  - [HTTP 常见的状态码和适用场景](../../issues/87)
- [TCP、UDP的区别，TCP如何实现可靠传输，UDP如何改进实现可靠传输](../../issues/88)
- [三次握手、四次挥手及其涉及的相关问题](https://juejin.cn/post/6844903958624878606)
- 跨域
  - [简单请求、复杂请求、预检请求、跨域资源共享CORS](https://developer.mozilla.org/zh-CN/docs/Web/HTTP/CORS)
- 异步请求方式
  - [ajax、axios、fetch对比](https://www.cnblogs.com/weiqinl/p/11279950.html)
  - [xhr封装axios](../../issues/202)
  - [二次封装Axios](https://github.com/febobo/web-interview/issues/25)
- 缓存
  - [浏览器的缓存机制。强缓存(200(from disk cache))：Expires、Cache-Control，协商缓存(304)：Last-Modified/If-Nodified-since、Etag/If-None-Match](https://juejin.cn/post/6844903593275817998)
  - [图解 Http 缓存控制之 max-age=0、no-cache、no-store 区别](https://zhuanlan.zhihu.com/p/55623075)
  - [用户的刷新行为对缓存的影响](../../issues/198)
- HTTPS
  - [HTTPS详解](https://segmentfault.com/a/1190000021494676)  
  - [SSL/TLS握手过程](https://segmentfault.com/a/1190000021559557)
  - [证书吊销机制(Online Certificate Status Protocol, OCSP)](https://network.51cto.com/article/610944.html)
  - [Nginx部署CA证书](https://blog.csdn.net/why_2012_gogo/article/details/77894502)

> ## 浏览器
- 架构
  - [浏览器架构，共四部分](https://cloud.tencent.com/developer/article/1806716)
-  渲染
  - [浏览器的渲染原理](https://coolshell.cn/articles/9666.html)
  - [回流与重绘 (Reflow & Repaint)](../../issues/101)
- JS执行机制
  - [从浏览器多进程到JS单线程](https://segmentfault.com/a/1190000012925872)
- 浏览器安全
  - [Web 安全](https://segmentfault.com/a/1190000023396707)、[如何防止CSRF攻击？](https://tech.meituan.com/2018/10/11/fe-security-csrf.html)
- 垃圾回收
  - [V8垃圾回收机制、内存泄露](../../issues/56)

> ## 设计模式
- [权限设计方案](https://juejin.cn/post/6949453195987025927)
- [工厂模式、构造函数模式、寄生构造函数模式、稳妥构造函数模式](../../issues/54)
- [观察者模式与发布订阅模式](../../issues/61)
- [OOP与AOP区别、装饰者模式](../../issues/139)

> ## Vue
- [MVC、MVP、MVVM的区别](https://www.ruanyifeng.com/blog/2015/02/mvcmvp_mvvm.html)
- [v-if和v-show的区别](../../issues/85)
- [watch、computed区别及属性的监听](../../issues/84)
- [Vue过滤器](../../issues/93)
- [Vue中的diff算法](../../issues/71)
- [Vue生命周期](../../issues/65)；[父子组件、兄弟组件、宏mixins组件生命周期](https://juejin.cn/post/6844903602356502542)
- [为什么data属性是一个函数而不是一个对象？](../../issues/91)
- [动态给vue的data添加一个新的属性时界面不刷新？怎样解决？](https://github.com/febobo/web-interview/issues/10)
- [Vue的SEO优化方案](../../issues/94)
- [Vue 组件为何采用异步渲染-nextTick的实现原理](https://juejin.cn/post/6844903590293684231)
- 双向绑定原理
    - [数据响应(数据劫持)](../../issues/58)
    - [Vue数据双向绑定原理，实现v-model](../../issues/191)
- router
  - [vue-router](../../issues/38)
  - [hash 和 history 模式](https://zhuanlan.zhihu.com/p/130995492)
  - [router-link和a标签的区别](../../issues/206)
- [按需加载：vue异步组件require()、es6的import()（可进行chunk分包）](../../issues/62)
- [Vue 自定义指令Vue.directive](https://github.com/febobo/web-interview/issues/21)
- [为什么使用key](../../issues/66)
- [为什么避免 v-if 和 v-for 一起用](../../issues/70)
- [Vue 动态绑定样式的方式](../../issues/67)
- [keep-alive缓存后怎么更新](../../issues/92)
- 公共组件
  - [Mixins（混入）及源码分析](https://github.com/febobo/web-interview/issues/15)
  - [v-once、Vue.component](../../issues/133)
  - [插件 Vue.use(plugin) 的原理和使用](../../issues/64)
  - [Vue.extend](../../issues/132)
  - [Vue 插槽(slot)](https://github.com/febobo/web-interview/issues/16)
  - [Vue自定义模态框](../../issues/95)
  - [Vue动态组件:is实现tab页切换](https://segmentfault.com/a/1190000018018502)
  - [高阶组件(HOC)](http://caibaojian.com/vue-design/more/vue-hoc.html#vue-%E4%B8%AD%E7%9A%84%E9%AB%98%E9%98%B6%E7%BB%84%E4%BB%B6)[、使用举例](https://www.cnblogs.com/zhensg123/p/14699982.html)
  - [vue中8种组件通信方式：props/$emit、$parent/$children、ref、provide/inject、Eventbus、Vuex、localStorage/sessionStorage、$attrs/$listeners](https://juejin.cn/post/6844903887162310669)
- Vue3.0 
  - [Vue2.0和Vue3.0的区别](../../issues/69) 
  - [Vue3.0 所采用的 Composition Api 与 Vue2.x 使用的 Options Api 有什么不同？](https://juejin.cn/post/6844904066103902215)
- Vuex
  - [Vuex 简单介绍](../../issues/63)
  - [Vuex 和 localStorage 的区别](../../issues/205)

> ## Node
- [Node.js 架构](https://juejin.cn/post/7081891057918558221)
- [Webpack配置Node环境变量](../../issues/138)
- [压缩和混淆node.js服务端代码](https://segmentfault.com/a/1190000021269770)
- [说说对 Buffer 的理解、应用场景](../../issues/118)
- [说说对 Stream 的理解、应用场景](../../issues/119)
- [说说EventEmitter? 如何实现一个EventEmitter?](../../issues/120)
- [Node 定时器、Event Loop详解](http://www.ruanyifeng.com/blog/2018/02/node-event-loop.html)
- [说说 Node 文件查找的优先级以及 require 方法的文件查找策略?](../../issues/121)
- [中间件的理解和封装，express、koa区别](../../issues/122)
- [Nodejs 大文件分片上传](../../issues/123)
- [设计一个分页功能，前后端如何交互?](../../issues/124)
- [PM2自动重启、负载均衡、日志输出](https://www.cnblogs.com/chyingp/p/pm2-documentation.html)
- [Node.js 与 log4js日志分级（TRACE、DEBUG、INFO、WARN、ERROR）](https://zhuanlan.zhihu.com/p/22110802)
- [自动化API测试](https://cloud.tencent.com/developer/news/618920)

> ## Babel
- [什么是Babel](https://juejin.cn/post/6901649054225465352)
- [组件库按需加载原理分析](https://juejin.cn/post/6968505746757533710) 
- [babel-polyfill](../../issues/188)
- [Babel原理及插件开发](https://juejin.cn/post/6844903603983892487)
- [自己手写一个简单的babel插件](https://github.com/TieMuZhen/babel-plugin-debug)

> ## Webpack & npm
- [Webpack整体大纲](../../issues/59)
- [模块打包原理](../../issues/109)
- [webpack的构建流程](../../issues/103)
- [webpack proxy工作原理？为什么能解决跨域?](../../issues/104)
- [Loader](../../issues/35)
- [如何保证各个loader按照预想方式工作？](../../issues/113)
- [source map是什么？生产环境怎么用？](../../issues/108)
- [文件指纹策略](../../issues/112)
- [文件监听原理](../../issues/110)
- [Webpack 的热更新原理](../../issues/107)
- [如何对bundle体积进行监控和分析？](../../issues/111)
- [代码分割和公共代码提取](https://segmentfault.com/a/1190000021074403)
- [如何使用webpack优化前端性能](../../issues/105)
- [如何提高webpack的构建速度](../../issues/106)
- [Tree Shaking原理](../../issues/187)
- npm
  - [npm和yarn的区别](../../issues/125)
  - [npm 安装时 --save --dev 和 --save 区别](../../issues/126)
  - [npm init 和 npm install执行了哪些操作](../../issues/127)

> ## Redis
- [Redis概述](../../issues/147)
- [Redis、Memcache、MongoDB区别](../../issues/148)
- [缓存穿透、缓存击穿、缓存雪崩](../../issues/149)
- [八种数据类型：String、Bitmap、Hyperloglog、List、Set、Zset有序集合、Hash、Geospatial地理位置](../../issues/140)
- [模拟验证码发送](../../issues/145)
- [Redis事务及乐观锁](../../issues/141)
- [Redis配置文件详解](../../issues/143)
- [Redis订阅发布](../../issues/144)
- [哨兵模式](../../issues/150)
- [持久化之RDB操作、AOF操作](../../issues/146)
- [多线程、阻塞、非阻塞](../../issues/152)
- [秒杀系统](../../issues/153)
- 集群
  - [集群](../../issues/154)
  - [集群的环境搭建](../../issues/155)
- [分布式锁](../../issues/156)
- [秒杀案例](../../issues/157)
- [Redis经典面试题](../../issues/158)

> ## TypeScript
- [TypeScript 入门教程](https://ts.xcatliu.com/)
- [TypeScript 的另一面：类型编程](https://juejin.cn/post/6989796543880495135)

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
- [如何监控网页的卡顿？](https://zhuanlan.zhihu.com/p/39292837)
- [如何对直播卡顿优化](https://juejin.cn/post/7062552765117136903#heading-13)
- [QPS、TPS、并发用户数、吞吐量关系](https://zhuanlan.zhihu.com/p/111914041)
- [最新性能指标](https://juejin.cn/post/6850037270729359367)
- [前端性能优化 24 条建议（2020）](https://juejin.cn/post/6892994632968306702)
- [前端性能优化之旅](https://alienzhou.github.io/fe-performance-journey/)
- [搜索引擎优化（SEO）的技巧](https://zhuanlan.zhihu.com/p/43364394)

> ## 操作系统
- [32位和64位的区别](../../issues/203)
- [内存作用是什么？大了有什么好处](../../issues/204)
- [分段、分页](https://segmentfault.com/a/1190000038810428)
- [线程与进程的区别，各自之间如何通信](../../issues/89)
- [死锁的产生原因和解决办法](../../issues/90)

> ## 工具
- [Swagger API规范](https://swagger.io/)
- [Jenkins 持续集成](https://www.jenkins.io/zh/doc/pipeline/tour/getting-started/)
- [Git Flow](https://segmentfault.com/a/1190000006194051)
- [前端代码上传到阿里云服务器上（OSS）并访问](../../issues/185)
- [OSS 和 CDN 配合使用加速](https://maintao.com/2018/aliyun-oss-cdn-tips/)
- [如何保证发布后 CDN 代码是最新的？如何预热？](../../issues/186)
- [前端单元测试](https://juejin.cn/post/7039108357554176037)
- [Google Analytics跨域跟踪用户数据](https://www.webanalytics.com.cn/blog/google-analytics-cross-domain-tracking/)

> ## 算法
- [时间复杂度分析方法](https://mp.weixin.qq.com/s/Rzdz_dwS_4eOoX7XkFIALQ)[、时间和空间复杂度分析案例](https://zhuanlan.zhihu.com/p/50479555)
- [快速排序、堆排序、二路归并排序、插入排序](../../issues/163)
- [快速幂](../../issues/130)
- [大数加法](../../issues/161)
- [最长回文子串](../../issues/181)
- Map + 指针
  - [LRU 缓存](../../issues/180)
- 二分法
  - [寻找两个正序数组的中位数](../../issues/176)
- 栈
  - [去除字符](../../issues/179)
- 二叉树
  - [二叉树的下一个结点、二叉树测试用例编写](../../issues/165)
  - [二叉树的构造](../../issues/166)
  - [实现字典树](../../issues/142)
- 回溯
  - [递增子序列](../../issues/171)
- DFS
  - [单词拆分](../../issues/172)
  - [岛屿系列问题](../../issues/160)
- 图论
  - 并查集
    - [有环图转无环图](../../issues/151)
    - [最小生成树](../../issues/159)
  - [拓扑排序、最短路径、关键路径](../../issues/164) 


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
- [《词文摘录》](../../issues/80)
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
