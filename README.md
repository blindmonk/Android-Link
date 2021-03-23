
## Android 成为资深研发之路

## 目录
* ### Android自定义
   * [基础篇](#android-基础自定义view)
   * [View组件库](#android-view组件库)
   * [项目组件库](#android-项目组件库)
    
* ### Android动画
   * [基础篇](#android-动画基础)
   * [开源库](#android-动画开源库)
   * [源码分析](#android-动画源码分析)
   
* ### Android优化
   * [性能优化](#android-性能优化)
   * [内存优化](#android-内存优化)
   * [OOM、ANR相关](#android-oom-anr)
   
* ### Android基础开发常用工具和资料
   * [Studio 插件、优化等](#android-studio)
   * [Gradle 知识库](#gradle)
   * [APK加固与反编译](#android-加固与反编译)
   * [Android-orm框架，推荐使用GreenDao，Ormlite](#安卓orm框架用得比较多的就greendaoormlite)
   * [Android-Json数据解析工具](#安卓json解析)
   * [Android 常用辅助工具](#android-开发辅助工具)
   * [Android 推送（含IM）相关](#android-推送含im)
   * [Android APK内测平台](#android-应用内测平台)
   * [Android 社会化分享，短信验证等](#android社会化分享短信验证意见反馈支付等相关)
   * [Android Drawable资源相关](#安卓资源相关)
   * [Git 教程](#git)
   * [Ibeacon与蓝牙4.0](#ibeacon与蓝牙40相关)
   * [Android NoSql相关](#android-nosql)
   * [Android 后端等服务云](#android-后端等服务)
   * [Android 网络层库-包含图片相关](#安卓网络层包含图片)
   
* ### Android值得关注的
   * [插件化与动态加载](#android-插件与动态加载)
   * [组件化](#android-热更新)
   * [热更新](#android-热更新)
   * [RxJava、agera](#rxjava-agera相关资料)
   * [值得关注的库](#安卓开发值得关注的库)
   * [值得关注的优秀内容和工具](#android-开发中值得看的优秀内容和工具)
   * [国外个人博客](#国外个人博客)
   * [Android 开源项目](#android-开源软件)
   * [设计网站，可以找到一些酷炫的设计稿](#设计网站可以寻找一些酷炫的设计稿)
   
* ### [Android 面试](#面试)




=============================================================

### Android 基础自定义view
 - [GcsSloop](http://www.gcssloop.com/customview/CustomViewIndex/) (很详细自定义View包括相关Api介绍)
 - [Gallery 3D效果](http://blog.csdn.net/leehong2005/article/details/8070538)
 - [SlidingDrawer抽屉效果](http://blog.csdn.net/xyz_lmn/article/details/6906689)
 - [绚丽的枫叶loading效果分析实践](http://blog.csdn.net/tianjian4592/article/details/44538605)
 - [Math用法](http://blog.csdn.net/heng615975867/article/details/13769341)
 - [oMeasure初看，深入理解](http://www.cppblog.com/guojingjia2006/archive/2012/03/27/169214.html)
 - [360全景视频螺旋仪](http://download.csdn.net/download/ujjldx/9315333)
 - [android中moveTo,lineTo,quadTo···详解](https://segmentfault.com/a/1190000000721127)
 - [andoird复杂的列表视图新鞋发MutiType](http://gank.io/post/5823bcf6421aa90e799ec2ad)
 - [贝塞尔曲线](http://www.jianshu.com/p/9eef2a713d33)
 - [快速放些京东、天猫下拉刷新](http://www.jianshu.com/p/9daaa87045d0)
 - [Paint之 setXfermode PorterDuffXfermode 讲解](http://blog.csdn.net/tianjian4592/article/details/44783283)
 - [自定义View  原理](https://www.jianshu.com/p/988326f9c8a3)

### Android View组件库
 - [列表相关List](https://github.com/XXApple/AndroidLibs/tree/master/%E5%88%97%E8%A1%A8List) 
 - [动画相关Animation](https://github.com/XXApple/AndroidLibs/tree/master/%E5%8A%A8%E7%94%BBAnimation)
 - [图标Icon](https://github.com/XXApple/AndroidLibs/tree/master/%E5%9B%BE%E6%A0%87Icon)
 - [图片框架Image](https://github.com/XXApple/AndroidLibs/tree/master/%E5%9B%BE%E7%89%87%E6%A1%86%E6%9E%B6Image)
 - [图表Chart](https://github.com/XXApple/AndroidLibs/tree/master/%E5%9B%BE%E8%A1%A8Chart)
 - [完整开源项目Project](https://github.com/XXApple/AndroidLibs/tree/master/%E5%AE%8C%E6%95%B4%E5%BC%80%E6%BA%90%E9%A1%B9%E7%9B%AEProject)
 - [布局Layout](https://github.com/XXApple/AndroidLibs/tree/master/%E5%B8%83%E5%B1%80Layout)
 - [开发框架Framework](https://github.com/XXApple/AndroidLibs/tree/master/%E5%BC%80%E5%8F%91%E6%A1%86%E6%9E%B6Framework)
 - [弹框Dialog](https://github.com/XXApple/AndroidLibs/tree/master/%E5%BC%B9%E6%A1%86Dialog)
 - [按钮Button](https://github.com/XXApple/AndroidLibs/tree/master/%E6%8C%89%E9%92%AEButton)
 - [文本Label](https://github.com/XXApple/AndroidLibs/tree/master/%E6%96%87%E6%9C%ACLabel)
 - [特效Effect](https://github.com/XXApple/AndroidLibs/tree/master/%E7%89%B9%E6%95%88Effect)
 - [网络框架Network](https://github.com/XXApple/AndroidLibs/tree/master/%E7%BD%91%E7%BB%9C%E6%A1%86%E6%9E%B6Network)
 - [自定义控件Custom](https://github.com/XXApple/AndroidLibs/tree/master/%E8%87%AA%E5%AE%9A%E4%B9%89%E6%8E%A7%E4%BB%B6Custom) (其他分类找不到的，大部分都在这个分类里面)
 - [菜单Menu](https://github.com/XXApple/AndroidLibs/tree/master/%E8%8F%9C%E5%8D%95Menu)
 - [辅助工具类Utils](https://github.com/XXApple/AndroidLibs/tree/master/%E8%BE%85%E5%8A%A9%E5%B7%A5%E5%85%B7%E7%B1%BBUtils)
 - [进度条Progressbar](https://github.com/XXApple/AndroidLibs/tree/master/%E8%BF%9B%E5%BA%A6%E6%9D%A1Progressbar)
 
### Android 项目组件库
- [Android Libraries and Resources ](http://alamkanak.github.io/android-libraries-and-resources/)
- [Android Arsenal ](http://android-arsenal.com/)(一个专门收集 android 开源库的网站, 网站经常更新)
- [Android 开源项目汇总 ](https://github.com/Trinea/android-open-project)
- [Android 开源项目源码分析 ](http://codekk.com/open-source-project-analysis)
- [泡在网上的日子库汇总](http://www.jcodecraeer.com/plus/list.php?tid=31)
- [android-gems国外定期上传开源库](http://www.android-gems.com/)


### Android 动画基础
- [Android补间动画、属性动画 常用功能总结](http://www.jianshu.com/p/ec62b81df7ed)
- [动画基础组件、类详讲](http://www.360doc.com/content/13/0102/22/6541311_257754535.shtml)
- [Interpolator 图形化生成的贝塞尔插值器](http://www.cnblogs.com/benhero/p/4377374.html)

### Android 动画开源库
- [View、Acitvity过度基础动画库](https://github.com/hitherejoe/animate)
- [awesome 定期更新动画相关包含IOS](https://github.com/Animatious/awesome-animation)
- [Material-Animations 比较知名的Android过场转换动画](https://github.com/lgvalle/Material-Animations)
- [AndroidViewAnimations 输入框、文字相关动画](https://github.com/daimajia/AndroidViewAnimations)

### Android 动画源码分析
- [Android动画的实现流程](http://blog.csdn.net/startfromweb/article/details/7644405)
- [Android Animation运行原理详解](http://www.jianshu.com/p/fcd9c7e9937e)



### Android 性能优化
 - [优化基础和控件](http://blog.csdn.net/xyz_lmn/article/details/13870027)
 - [Android界面性能调优手册](https://segmentfault.com/a/1190000004547751)
 - [Android性能优化视频，文档以及工具](https://github.com/Juude/awesome-android-performance)
 - [APK瘦身记，如何实现高达53%的压缩效果](https://zhuanlan.zhihu.com/p/23882195?from=groupmessage)
 - [胡凯-性能优化](http://hukai.me/blog/archives/)
 - [Android最佳性能实践(1)：合理管理内存](http://blog.csdn.net/guolin_blog/article/details/42238627)
 - [Android最佳性能实践(2)：分析内存的使用情况](http://blog.csdn.net/guolin_blog/article/details/42238633)
 - [Android最佳性能实践(3)：高性能编码优化](http://blog.csdn.net/guolin_blog/article/details/42318689)
 - [Android最佳性能实践(4)：布局优化技巧](http://blog.csdn.net/guolin_blog/article/details/43376527)
 - [blockcanary-轻松找出Android App界面卡顿元凶](https://github.com/moduth/blockcanary)
 - [Android性能优化典范（一）从各个方面分析](http://www.csdn.net/article/2015-01-20/2823621-android-performance-patterns)
 - [Android Splash页秒开 Activity白屏 Activity黑屏](http://blog.csdn.net/yanzhenjie1003/article/details/52201896)
 
### Android 内存优化
- [Android 内存暴减的秘密？！](https://mp.weixin.qq.com/s/kYFxXvL2SrxhKATWgYpOPg)
- [我这样减少了26.5M Java内存！](https://mp.weixin.qq.com/s/ZGpGXM8wGiSr-jtrxU3ALA)
- [Android内存优化(大汇总——中)](http://blog.csdn.net/a396901990/article/details/38707007)
- [使用新版Android Studio检测内存泄露和性能](https://www.2cto.com/kf/201512/455421.html)
- [Android 内存管理机制](http://www.jianshu.com/p/5bd50b15177f)
- [Android 内存管理分析总结](http://www.jianshu.com/p/8b1d9c86fa84)
- [Android 内存管理与优化](http://www.jianshu.com/p/8b1d9c86fa84)

### Android OOM ANR
- [什么情况导致oom](http://blog.csdn.net/a396901990/article/details/38707007)
- [Android内存优化之OOM](http://www.jianshu.com/p/b6a65519a1a0)
- [Android避免OOM](http://www.jianshu.com/p/f5d8d3066b36)
- [ANR定位和修正](http://www.jackywang.tech/AndroidInterview-Q-A/chinese/subject/%E6%80%A7%E8%83%BD%E4%BC%98%E5%8C%96.html)
- [Android ANR：原理分析及解决办法](http://www.jianshu.com/p/388166988cef)
- [ANR 原理与实战技巧  通过log的方式分析](http://www.jcodecraeer.com/a/anzhuokaifa/androidkaifa/2017/0902/8459.html)


### Android 插件与动态加载
 - [手机淘宝（插件化Atlas）](https://alibaba.github.io/atlas/)
 - [Android插件化技术——原理篇](https://mp.weixin.qq.com/s/Uwr6Rimc7Gpnq4wMFZSAag)
 - [OpenAtlas，已改名为ACDD，可以在手机淘宝中见到踪影](https://github.com/bunnyblue/ACDD)
 - [360的DroidPlugin](https://github.com/Qihoo360/DroidPlugin)
 - [dynamic-load-apk](https://github.com/singwhatiwanna/dynamic-load-apk)
 - [携程DynamicAPK](https://github.com/CtripMobile/DynamicAPK)
 - [美团分包](http://tech.meituan.com/mt-android-auto-split-dex.html)
 - [微信/手Q加载方案](http://mp.weixin.qq.com/s?__biz=MzAwNDY1ODY2OQ==&mid=207151651&idx=1&sn=9eab282711f4eb2b4daf2fbae5a5ca9a&3rd=MzA3MDU4NTYzMw==&scene=6#rd)
 - [Small](https://github.com/wequick/Small)
 - [Android博客周刊专题之《插件化开发》](http://www.androidblog.cn/index.php/Index/detail/id/16)
 - [Android Plugin Framework 插件开发框架及示例程序，原理介绍等](https://github.com/limpoxe/Android-Plugin-Framework)
 - [获取主dex](https://github.com/lizhangqu/MainDex)
 - [应用双开VirtualApp](https://github.com/asLody/VirtualApp)
 - [Android Dex分包之旅](http://yydcdut.com/2016/03/20/split-dex/)
 - [掌阅-最简单易懂的Android插件补丁框架](https://github.com/iReaderAndroid/ZeusPlugin)
 - [ANROID动态加载技术 系列索引](https://zhuanlan.zhihu.com/p/20515113)

### Android 热更新
 - [微信tinker](http://www.tinkerpatch.com/Docs/intro)
 - [dexposed](https://github.com/alibaba/dexposed)
 - [AndFix](https://github.com/alibaba/AndFix)
 - [QQ空间热修复](http://mp.weixin.qq.com/s?__biz=MzI1MTA1MzM2Nw==&mid=400118620&idx=1&sn=b4fdd5055731290eef12ad0d17f39d4a&scene=0#wechat_redirect)
 - [QQ空间热修复实现方案](https://github.com/dodola/HotFix)
 - [Nuwa 女娲](https://github.com/jasonross/Nuwa)
 - [Android HotPatch从入门到“放弃”](https://mp.weixin.qq.com/s?__biz=MzIzMDEyNzM4NQ==&mid=2650956297&idx=1&sn=f4bfdd7b16f95b6d34c6f34d8ce392e0&scene=0&uin=MTY4NDEwODc2Mg%3D%3D&key=cf237d7ae24775e8a8b56c7ea2bb2868382d9036f67165867c202e363b23bb4e596335de9da22825b530281867b47449&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.6+build(15G31)&version=12000006&lang=zh_CN&nettype=WIFI&fontScale=100&pass_ticket=95LpBT0hMvr3CsOzDCiFvaRxltvzQUdRKYWgyVX2qwUNRC1PW%2Bmf8ebbmyh6bwrH)
 - [Android Patch 方案与持续交付](http://wereadteam.github.io/2016/07/26/AndroidPatch/?from=timeline&isappinstalled=0)
 - [Android N混合编译与对热补丁影响解析](https://mp.weixin.qq.com/s?__biz=MzAwNDY1ODY2OQ==&mid=2649286341&idx=1&sn=054d595af6e824cbe4edd79427fc2706&scene=2&srcid=0804Rg6BqGmPSPyeUOOLXds3&from=timeline&isappinstalled=0&uin=MTY4NDEwODc2Mg%3D%3D&key=cf237d7ae24775e86d7c5f57902ee2b81f05b64d1b6baf39ba9ad8115ea453e72d5d9f36a58c506d01f2a84e9b6c2eca&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.6+build(15G31)&version=12000006&lang=zh_CN&nettype=WIFI&fontScale=100&pass_ticket=95LpBT0hMvr3CsOzDCiFvaRxltvzQUdRKYWgyVX2qwUNRC1PW%2Bmf8ebbmyh6bwrH)
 - [微信Android热补丁实践演进之路](https://mp.weixin.qq.com/s?__biz=MzAwNDY1ODY2OQ==&mid=2649286306&idx=1&sn=d6b2865e033a99de60b2d4314c6e0a25&scene=0&uin=MTY4NDEwODc2Mg%3D%3D&key=cf237d7ae24775e8857eb5c8144bf27076228deefafb6a0afd4416d54ed479daa6a67f0363c96df893d5cf4e4d3db423&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.6+build(15G31)&version=12000006&lang=zh_CN&nettype=WIFI&fontScale=100&pass_ticket=95LpBT0hMvr3CsOzDCiFvaRxltvzQUdRKYWgyVX2qwUNRC1PW%2Bmf8ebbmyh6bwrH)
 - [Android热更新之so库的热更新](http://blog.csdn.net/sbsujjbcy/article/details/51475499)
 - [Android aapt实现资源分区（补充携程aapt源码）](http://blog.csdn.net/sbsujjbcy/article/details/51405207)
 - [Android 热修复使用Gradle Plugin1.5改造Nuwa插件](http://blog.csdn.net/sbsujjbcy/article/details/50839263)
 - [Android 热修复Nuwa的原理及Gradle插件源码解析](http://blog.csdn.net/sbsujjbcy/article/details/50812674)
 - [Tinker_imitator](https://github.com/zzz40500/Tinker_imitator)
 - [ZeusPlugin插件框架热修复gradle插件源码](https://github.com/iReaderAndroid/PatchPluginForZeus)
 - [RocooFix](https://github.com/dodola/RocooFix)
 - [ Android Classloader热修复技术之百家齐放](http://blog.csdn.net/sbsujjbcy/article/details/51760578)
 - [从Instant-Run出发，谈谈Android上的热修复](http://zjutkz.net/2016/05/10/%E4%BB%8EInstant-Run%E5%87%BA%E5%8F%91%EF%BC%8C%E8%B0%88%E8%B0%88Android%E4%B8%8A%E7%9A%84%E7%83%AD%E4%BF%AE%E5%A4%8D/)
 - [Android热修复与增量升级，基于微信Tinker原理](https://github.com/byteam/delta)
 - [美团Android热更新方案Robust](http://tech.meituan.com/android_robust.html)
 
 
 ### RxJava RxJava2相关资料
 - [RxJava2 这可能是最好的RxJava 2.x 教程（完结版）](https://www.jianshu.com/p/0cd258eecf60)
 - [RxJava 扔物线](https://gank.io/post/560e15be2dca930e00da1083)
 - [RxJava Github地址](https://github.com/ReactiveX/RxJava/)
 - [RxAndroid Github地址](https://github.com/ReactiveX/RxAndroid)
 - [RxJava中文文档翻译](https://github.com/mcxiaoke/RxDocs)
 - [Awesome-RxJava](https://github.com/lzyzsd/Awesome-RxJava)
 - [在正确的线程上观察](http://www.jianshu.com/p/72911b9ba2d7)
 - [给 Android 开发者的 RxJava 详解](http://gank.io/post/560e15be2dca930e00da1083)
 - [谜之RxJava （一） —— 最基本的观察者模式](https://segmentfault.com/a/1190000004049490)
 - [谜之RxJava （二） —— Magic Lift](https://segmentfault.com/a/1190000004049841)
 - [迷之RxJava （三）—— 线程切换](https://segmentfault.com/a/1190000004051191)
 - [迷之RxJava （三）update —— 线程切换（二）](https://segmentfault.com/a/1190000004855661)
 - [迷之RxJava （三）update 2 —— subscribeOn 和 observeOn 的区别](https://segmentfault.com/a/1190000004856071)
 - [迷之RxJava（四）—— Retrofit和RxJava的基情](https://segmentfault.com/a/1190000004077117)
 - [RxJava 与 Retrofit 结合的最佳实践](http://gank.io/post/56e80c2c677659311bed9841)



### 面试

- [面试总结-java和android](https://github.com/JackyAndroid/AndroidInterview-Q-A)
- [LearningNotes](https://github.com/GeniusVJR/LearningNotes) (非常详细的面试资料, 涉及 Android, Java, 设计模式, 算法等)
- [80% 以上简历都是不合格的-面试要种简历查抓起](http://j.codekk.com/blogs/detail/5705bcdf4a38205862ef4770)
- [推荐两个技术简历模板](http://j.codekk.com/blogs/detail/5705bcdf4a38205862ef476f)
- [Android 面试那些事儿-聊聊心得](https://zhuanlan.zhihu.com/p/21565914)
- [改善技术简历的47条原则-比较意思](http://lucida.me/blog/lean-technical-resume/)
- [比较全Android 面试资料集合](http://www.jianshu.com/p/d1efe2f31b6d)


### Android Studio
 - [studio基本使用](https://github.com/ruijun/Android-Dev-Favorites/tree/master/Android%20Studio)
 - [查看依赖关系的插件](https://github.com/rholder/gradle-view)
 - [Android Studio 比较热门的调试技巧](http://tianweishu.com/2015/12/21/android-studio-debug-tips-you-may-not-know/)
 - [Android打包的那些事](http://www.jayfeng.com/2015/11/07/Android%E6%89%93%E5%8C%85%E7%9A%84%E9%82%A3%E4%BA%9B%E4%BA%8B/)
 - [idea-live-templates 模板](https://github.com/keyboardsurfer/idea-live-templates)
 - [方法数统计插件，可用于统计是否达到65536个方法](https://github.com/KeepSafe/dexcount-gradle-plugin)
 - [Android-Drawable-Importer插件](https://github.com/winterDroid/android-drawable-importer-intellij-plugin)
 - [GsonFormat Json对应的Bean快速生成插件](https://github.com/zzz40500/GsonFormat)
 - [android-selector-chapek Selector生成插件](https://github.com/inmite/android-selector-chapek)
 - [快速生成butterknife注解插件](https://github.com/avast/android-butterknife-zelezny)
 - [android-material-design-icon-generator图标插件](https://github.com/konifar/android-material-design-icon-generator-plugin)
 - [Retrolambda 在java 6 7中使用 lambda表达式插件](https://github.com/evant/gradle-retrolambda)
 - [Gradle依赖自动补齐插件](https://github.com/ligi/GradleDependenciesHelperPlugin)
 - [idea-markdown编辑器插件](https://github.com/nicoulaj/idea-markdown)
 - [从布局中生成View的声明插件](https://github.com/Haehnchen/idea-android-studio-plugin)
 - [codota代码片段搜索，支持Chrome和Android Studio](https://www.codota.com/)
 - [布局文件分组插件](https://github.com/dmytrodanylyk/folding-plugin)
 - [DPI计算插件](https://github.com/JerzyPuchalski/Android-DPI-Calculator)
 - [gradle-publish 发布库插件](https://github.com/msdx/gradle-publish)
 - [发布lib到jcenter](https://github.com/andforce/release-android-lib-to-jcenter)
 - [vysor 这个是Chrome的插件，电脑操作手机](https://chrome.google.com/webstore/detail/vysor-beta/gidgenkbbabolejbgbpnhbimgjbffefm)
 - [Android Studio插件开发](http://jiajixin.cn/2015/10/11/android-studio-plugin-dev/)
 - [Android SDK镜像服务器搭建](http://jiajixin.cn/2015/10/11/android-sdk-mirror/)
 - [Android Studio 插件整理 48 个](https://ydmmocoo.github.io/2016/06/28/Android-Studio%E6%8F%92%E4%BB%B6%E6%95%B4%E7%90%86/)

### Android webview&JSBridge技术
 - [WebView 性能和用户体验优化](https://www.jianshu.com/p/fc7909e24178)
 - [WebView 全面干货指南](https://www.jianshu.com/p/fd61e8f4049e)
 - [你要的WebView与 JS 交互方式 都在这里了](https://blog.csdn.net/carson_ho/article/details/64904691/)
 - [手把手教你构建 Android WebView 的缓存机制 & 资源预加载方案](https://blog.csdn.net/carson_ho/article/details/71402764)
 - [浅谈Hybrid技术的设计与实现](http://www.cnblogs.com/yexiaochai/p/4921635.html)
 - [谈谈App混合开发](http://www.tuicool.com/articles/m6RVFfA)
 - [在WebView中如何让JS与Java安全地互相调用](http://blog.csdn.net/xyz_lmn/article/details/39399225)
 - [WebView中接口隐患与手机挂马利用](http://blog.csdn.net/marshalchen/article/details/11124541)
 - [ Android JSBridge的原理与实现](http://blog.csdn.net/sbsujjbcy/article/details/50752595)

### React Native 与 Weex 专题
 - [weex](http://alibaba.github.io/weex/)
 - [深入源码探索 ReactNative 通信机制](https://segmentfault.com/a/1190000004586390)
 - [React Native首屏白屏优化](https://segmentfault.com/a/1190000004743424)
 - [React Native专题系列文章更新ing(涉及基础,组件,进阶以及开源项目)](http://www.lcode.org/react-native/)
 - [React-native-Android-热更新](http://richard-cao.github.io/2015/12/03/React-native-Android-热更新/)
 - [React-Native学习指南](https://github.com/ele828/react-native-guide)
 - [Facebook的react-native](http://facebook.github.io/react-native/)
 - [React Native: 配置和起步](http://www.liaohuqiu.net/cn/posts/react-native-1/)
 - [React Native: Android 的打包](http://www.liaohuqiu.net/cn/posts/react-native-android-package/)
 - [React Native For Android初体验](http://www.jianshu.com/p/847a54e0c385)
 - [JianDan-React-Native](https://github.com/w4lle/JianDan-React-Native)
 - [React Native For Android 架构初探](http://mp.weixin.qq.com/s?__biz=MzI1MTA1MzM2Nw==&mid=207782506&idx=1&sn=3ff6b03c0d59fbda406f64739d9272cf&scene=1&srcid=1009Q3qo6mLeT2ydjdzUwLQ7&from=groupmessage&isappinstalled=0#rd)
 - [react-native-viewpager](https://github.com/race604/react-native-viewpager)
 - [React Native for Android 实践 -- 实现知乎日报客户端](http://www.race604.com/react-native-android-practice/)
 - [【React Native for Android】jsBridge实现原理](http://blog.desmondyao.com/2016/07/02/rn-bridge/)
 - [其实没那么复杂！探究react-native通信机制](http://zjutkz.net/2016/05/03/%E5%85%B6%E5%AE%9E%E6%B2%A1%E9%82%A3%E4%B9%88%E5%A4%8D%E6%9D%82%EF%BC%81%E6%8E%A2%E7%A9%B6react-native%E9%80%9A%E4%BF%A1%E6%9C%BA%E5%88%B6/)

 
### Android 加固与反编译
 - [android反编译工具的合集](https://github.com/Juude/droidReverse)
 - [Apktool](http://ibotpeaches.github.io/Apktool/)
 - [dex2jar](http://sourceforge.net/projects/dex2jar/)
 - [DecompileApk](https://github.com/MasonLiuChn/DecompileApk)
 - [Android APK加固技术方案调研](http://www.jianshu.com/p/856bf5b437aa)
 - [Android apk包res 资源混淆工具](https://github.com/joker535/Baffle)
 - [微信资源混淆](https://github.com/shwenzhang/AndResGuard)
 - [美团Android资源混淆保护实践](http://tech.meituan.com/mt-android-resource-obfuscation.html)
 - [美团Android资源混淆实现方案](https://github.com/JohnnyYin/ResProguard)
 - [Apk脱壳圣战之---如何脱掉“360加固”的壳](https://mp.weixin.qq.com/s?__biz=MzIzNDA3MDgwNA==&mid=2649229991&idx=1&sn=0fc62c65609143936d10849de6eb8069&scene=2&srcid=0629LJbsgjl7ctiSLYjRYXf5&from=timeline&isappinstalled=0&uin=MTY4NDEwODc2Mg%3D%3D&key=cf237d7ae24775e8a22350257773584f0e2dc2ae515c3e0b8779155f7a039c04e16a736510fe4d44b761a3f2b651a43b&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.6+build(15G31)&version=12000006&lang=zh_CN&nettype=WIFI&fontScale=100&pass_ticket=95LpBT0hMvr3CsOzDCiFvaRxltvzQUdRKYWgyVX2qwUNRC1PW%2Bmf8ebbmyh6bwrH)
 - [Android脱壳圣战之---如何脱掉"爱加密"家的保护壳](http://mp.weixin.qq.com/s?__biz=MzIzNDA3MDgwNA==&mid=2649229983&idx=1&sn=de2bd1a408d74e102ecd13a05512d1fa&scene=21#wechat_redirect)
 - [一键生成项目混淆代码插件](https://github.com/zhonghanwen/AndroidProguardPlugin)


### Gradle
 - [Gradle for Android](https://segmentfault.com/a/1190000004229002)
 - [谷歌Gradle官方文档](http://google.github.io/android-gradle-dsl/current/)
 - [Android Gradle 构建系统·初探](https://mp.weixin.qq.com/s?__biz=MzIzNTA3MjQwNw==&mid=2650672318&idx=1&sn=74fb2afc4e409be3014ea83aa623a792&scene=2&srcid=0814iBs3jyLcRldTGb3oqFIT&from=timeline&isappinstalled=0&uin=MTY4NDEwODc2Mg%3D%3D&key=cf237d7ae24775e8ab813a673c218977220f758d689261e1700639f2be2698a142186e9c68a3727f6e55683cee9ee94e&devicetype=iMac+MacBookPro12%2C1+OSX+OSX+10.11.6+build(15G31)&version=12000006&lang=zh_CN&nettype=WIFI&fontScale=100&pass_ticket=95LpBT0hMvr3CsOzDCiFvaRxltvzQUdRKYWgyVX2qwUNRC1PW%2Bmf8ebbmyh6bwrH)
 - [Gradle系列之从init.gradle说起](http://blog.csdn.net/sbsujjbcy/article/details/52079413)
 - [深入理解Android之Gradle](http://blog.csdn.net/innost/article/details/48228651)

### Android 开发中值得看的优秀内容和工具
 - [androidcat](http://androidcat.com/?step=1&view=CatFragment)
 - [ADB 用法大全](https://github.com/mzlogin/awesome-adb)
 - [使用 CheckStyle 检查代码](http://gudong.name/2016/04/07/checkstyle.html)
 - [图解 Retrofit - ServiceMethod](http://www.jianshu.com/p/3518cf8c6e4c)
 - [OkHttp3源码分析-综述](http://www.jianshu.com/p/aad5aacd79bf)
 - [Android进程保活招式大全](http://dev.qq.com/topic/57ac4a0ea374c75371c08ce8)
 - [08/07 北京 GDG Android Meetup 活动回顾，讲义，照片](https://mp.weixin.qq.com/s?__biz=MzA5MDg3MjczMg==&mid=2652003543&idx=1&sn=849c06ac198cbfe9cdcfae90b2a17021&scene=1&srcid=0815jxyNu3OlM7PEE8PGhNYa&key=305bc10ec50ec19b21a47f33276f15cf9aee4503429d7392ce9c57f25fe26abae9fb7cffaa188ed67fd7057f3bbdd764&ascene=0&uin=MTM5ODYyMTY4Mg%3D%3D)
 - [Java源码生成（Square JavaWriter）](https://github.com/square/javapoet)
 - [安卓架构文章合集（a collection of android Architecture）](https://github.com/CameloeAnthony/AndroidArchitectureCollection/blob/master/README.md)
 - [OS X 下使用 Hexo 和 Coding Pages 搭建静态博客](http://www.eyrefree.org/2016/03/23/2016-03-23-Hexo-Coding-Pages/)
 - [Android系统源码查看，支持在线跟踪引用](http://androidxref.com)
 - [贾吉鑫](http://jiajixin.cn)
 - [TraceView性能优化工具使用](http://wangxinghe.me/blog/2016-02-25/android-tools-traceview/)
 - [network-connection-class](https://github.com/facebook/network-connection-class)
 - [阿里巴巴技术文章](https://github.com/amfe/article)
 - [Android打包的那些事](http://www.jayfeng.com/2015/11/07/Android%E6%89%93%E5%8C%85%E7%9A%84%E9%82%A3%E4%BA%9B%E4%BA%8B/)
 - [InfoQAndroid周报](http://www.infoq.com/cn/android-weekly/)
 - [开发技术前线](http://www.devtf.cn/)
 - [美团Android DEX自动拆包及动态加载简介](http://tech.meituan.com/mt-android-auto-split-dex.html)
 - [Android官方培训课程中文版](https://github.com/kesenhoo/android-training-course-in-chinese)
 - [一个定期翻译国外Android优质的技术、开源库、软件架构设计、测试等文章的开源项目](https://github.com/bboyfeiyu/android-tech-frontier)
 - [Android Guides](https://github.com/codepath/android_guides)
 - [Android 开源项目源码解析](https://github.com/android-cn/android-open-project-analysis)
 - [Android 图像处理教学](http://chiuki.github.io/android-shaders-filters)
 - [Android 开源项目分类汇总](https://github.com/Trinea/android-open-project) 
 - [开发过程中遇到的坑](https://github.com/simple-android-framework-exchange/the-fucking-traps-in-android-dev)
 - [Android 开源交流](https://github.com/aosp-exchange-group/share)
 - [Android 著名开源库的简版实现](https://github.com/simple-android-framework-exchange/simple-android-opensource-framework)
 - [Android 问题交流讨论，大部分是面试题](https://github.com/android-cn/android-discuss) 
 - [android 设计模式](https://github.com/simple-android-framework-exchange/android_design_patterns_analysis)
 - [Android 全国职位列表](https://github.com/android-cn/android-jobs)
 - [fuck-2014-flirt-2015](https://github.com/aosp-exchange-group/fuck-2014-flirt-2015)
 - [AndroidDevTools开发相关资料下载](http://www.androiddevtools.cn/)
 - [android-best-practices最佳实践](https://github.com/futurice/android-best-practices)
 - [java设计模式](https://github.com/iluwatar/java-design-patterns)
 - [Android最佳实践示例](https://github.com/tianzhijiexian/Android-Best-Practices)
 - [Android 中 Java 与JavaScript 交互最详尽的总结](http://droidyue.com/blog/2014/09/20/interaction-between-java-and-javascript-in-android/?comefrom=http://blogread.cn/news/)
 - [如何为drawable着色](http://www.jcodecraeer.com/a/anzhuokaifa/androidkaifa/2015/0824/3356.html)
 - [Drawable 着色的后向兼容方案](http://www.race604.com/tint-drawable/)
 - [Awesome-MaterialDesign](https://github.com/lightSky/Awesome-MaterialDesign)
 - [Android 面试题InterviewQuestion](https://github.com/lizhangqu/InterviewQuestion)
 - [awesome-android](https://github.com/JStumpp/awesome-android)
 - [Retrofit相关文章](https://futurestud.io/blog/retrofit-getting-started-and-android-client/)
 - [Lite Android](http://litesuits.com/)
 - [Bugly Blog](http://bugly.qq.com/blog/)
 - [掘金](http://gold.xitu.io/#/tag/Android)

### 安卓网络层(包含图片)
 - [okhttp](https://github.com/square/okhttp)
 - [retrofit](https://github.com/square/retrofit)
 - [picasso](http://square.github.io/picasso/)
 - [Volley](https://android.googlesource.com/platform/frameworks/volley)
 - [fresco](https://github.com/facebook/fresco)
 - [Android-Universal-Image-Loader](https://github.com/nostra13/Android-Universal-Image-Loader)
 - [robospice](https://github.com/stephanenicolas/robospice)
 - [android-async-http](http://loopj.com/android-async-http/)
 - [Fast-Android-Networking](https://github.com/amitshekhariitbhu/Fast-Android-Networking)


### 安卓orm框架，用得比较多的就GreenDao，Ormlite
 - [greenDAO](http://greendao-orm.com/)
 - [ORMLite](http://ormlite.com/sqlite_java_android_orm.shtml)
 - [ActiveAndroid](https://github.com/pardom/ActiveAndroid/wiki/Getting-started )
 - [SugarORM](http://satyan.github.io/sugar/index.html)
 - [Siminov](http://siminov.github.io/android-orm/)
 - [androrm](http://www.androrm.net/)
 - [cupboard](https://bitbucket.org/qbusict/cupboard/wiki/GettingStarted)
 
### 安卓Json解析
 - [Gson,用法简单，速度慢](https://github.com/google/gson)
 - [fastjson，号称最快](https://github.com/alibaba/fastjson)
 - [jackson](https://github.com/FasterXML/jackson)

### Android 单元测试
 - [使用Mockito和Roboletric进行Android单元测试](http://mp.weixin.qq.com/s?__biz=MzIwOTQ1MjAwMg==&mid=2247483744&idx=1&sn=e322c5dc19952c563e00a24815399300&scene=0#wechat_redirect)
 - [Robolectric](http://robolectric.org/)

### Android 开源软件
 - [一个第三方开源微博](https://github.com/wangdan/AisenWeiBo)
 - [android相关的干货(文摘，名博，github等等)](https://github.com/openproject/AndroidDigest)
 - [第三方github客户端](https://github.com/Leaking/WeGit)
 - [开源中国的系列软件](http://git.oschina.net/oschina/)
 - [体重档案](https://github.com/Jhuster/EWeightScale)
 - [Simplifyreader](http://skillcollege.github.io/SimplifyReader/)
 - [西源坊](https://github.com/lzjun567/XiYuanFangApp)


### Android 开发辅助工具
 - [Charles 从入门到精通](http://gold.xitu.io/entry/56488b7660b20fc9b9c2f0be)
 - [Google Play APK下载器](http://apps.evozi.com/apk-downloader/)
 - [slideshare](http://www.slideshare.net/)
 - [codota代码片段搜索，支持Chrome和Android Studio](https://www.codota.com/)
 - [vysor 这个是Chrome的插件，电脑操作手机](https://chrome.google.com/webstore/detail/vysor-beta/gidgenkbbabolejbgbpnhbimgjbffefm)
 - [Browser extension to display GitHub code in tree format](https://github.com/buunguyen/octotree)
 - [google hosts翻墙，有vpn的忽略](http://laod.cn/hosts/2015-google-hosts.html)
 - [开源中国在线工具](http://tool.oschina.net/)
 - [百度ApiStore](http://apistore.baidu.com/)
 - [Vim插件](https://github.com/vim-scripts/Auto-Pairs)
 - [强迫症的 Mac 设置指南](https://github.com/macdao/ocds-guide-to-setting-up-mac)
 - [Linux-Tutorial](https://github.com/judasn/Linux-Tutorial)
 - [Markdown-Syntax-CN](https://github.com/judasn/Markdown-Syntax-CN)

 
### Android 推送（含IM）
 - [环信，支持即时音视频](http://www.easemob.com/)
 - [腾讯云通讯，支持即时音视频](http://www.qcloud.com/product/avc.html)
 - [极光推送和IM](https://www.jpush.cn/)
 - [个推](http://www.getui.com/)
 - [小米推送，在MIUI上属于系统服务框架，共享系统级长连接](http://dev.xiaomi.com/doc/?page_id=1670)
 - [百度云推送,部分机型收不到推送，如小米，Bug是否修复未知](http://push.baidu.com/)
 - [腾讯信鸽推送](http://xg.qq.com/xg/)
 - [友盟推送](https://www.umeng.com/push)
 - [leancloud](https://leancloud.cn/)
 - [bmob云推送，含IM](http://www.bmob.cn/products)
 - [蘑菇街TeamTalk](https://github.com/mogujie/TeamTalk)
 - [Openfire+Smack开源Xmpp解决方案](http://www.igniterealtime.org/downloads/index.jsp)
 
 
### Android后端等服务
 - [parse，缺点是服务器在国外，速度慢](https://parse.com/)
 - [leancloud，国内的，仿parse](https://leancloud.cn/)
 - [Bmob后端云](http://www.bmob.cn/)
 - [七牛云存储](http://www.qiniu.com/)
 - [apicloud](http://www.apicloud.com/)
 
### Android 应用内测平台
 - [蒲公英，内测应用](http://www.pgyer.com/)
 - [Fir.im，内测应用](http://fir.im/)

### Android社会化分享，短信验证，意见反馈，支付等相关

 - [友盟,社会化分析，意见反馈](http://www.umeng.com/)
 - [Sharesdk，社会化分析](http://mob.com/)
 - [Ping++，支付](https://pingxx.com)
 - [bmob支付，Bmob为广大开发人员提供的统一、正规的收费手段，让没有企业认证的个人开发者，也能通过支付宝和微信向用户收费](http://docs.bmob.cn/androidpay/index.html?menukey=fast_start&key=start_android_pay)
 - [容联云通讯](http://www.yuntongxun.com/ability/toPriceTariff)


### 安卓开发值得关注的库
 - [方法自动生成](https://projectlombok.org/)
 - [Android上的一个蛛网评分控件](https://github.com/xiaopansky/SpiderWebScoreView)
 - [ReLinker 安全加载so库的方式](https://github.com/KeepSafe/ReLinker)
 - [SugarTask](https://github.com/mthli/SugarTask)
 - [sync adapter](https://github.com/taoliuh/v2ex)
 - [Android Weak Handler防止内存泄露](https://github.com/badoo/android-weak-handler)
 - [Android Priority Job Queue 异步任务调度](https://github.com/path/android-priority-jobqueue)
 - [android-priority-jobqueue](https://github.com/yigit/android-priority-jobqueue)
 - [Android对话框](https://github.com/H07000223/FlycoDialog_Master)
 - [扩展的RecyclerView，拥有添加头、底等多种操作](https://github.com/tianzhijiexian/ExRecyclerView/)
 - [MaterialDesign相关库](https://github.com/lightSky/Awesome-MaterialDesign)
 - [右滑返回SwipeBackLayout](https://github.com/ikew0ng/SwipeBackLayout)
 - [百分比布局](https://github.com/JulienGenoud/android-percent-support-lib-sample)
 - [EventBus](https://github.com/greenrobot/EventBus)
 - [ObservableScrollView](https://github.com/ksoichiro/Android-ObservableScrollView/)
 - [工具库less code, more efficient for android](https://github.com/openproject/LessCode)
 - [通用适配器](https://github.com/JoanZapata/base-adapter-helper)
 - [android-log](https://github.com/SnowdreamFramework/android-log)
 - [NineOldAndroids](http://nineoldandroids.com/)
 - [BadgeView ](https://github.com/jgilfelt/android-viewbadger)
 - [CircleImageView](https://github.com/hdodenhof/CircleImageView)
 - [CustomShapeImageView](https://github.com/MostafaGazar/CustomShapeImageView)
 - [SweetAlert for Android, a beautiful and clever alert dialog](https://github.com/pedant/sweet-alert-dialog)
 - [android-pulltorefresh](https://github.com/johannilsson/android-pulltorefresh)
 - [SlidingMenu](https://github.com/jfeinstein10/SlidingMenu)
 - [ViewPagerIndicator](https://github.com/JakeWharton/ViewPagerIndicator)
 - [一个动画集合库](https://github.com/daimajia/AndroidViewAnimations)
 - [FontAwesome for Android](https://github.com/JoanZapata/android-iconify)
 - [RecyclerView made simple](https://github.com/lucasr/twoway-view)
 - [jsoup库(java)](http://jsoup.org/)
 - [android-wheel](https://github.com/maarek/android-wheel)
 - [xUtils](https://github.com/wyouflf/xUtils)
 - [android-common](https://github.com/Trinea/android-common)
 - [zxing](https://github.com/zxing/zxing)
 - [Android开发常用整理](https://github.com/wangjiegulu/AndroidBucket)
 - [左滑粒子删除效果](https://github.com/ZhaoKaiQiang/ParticleLayout)
 - [JSON Server：零编码快速“伪造” REST API](https://github.com/typicode/json-server)
 - [owncloud](https://github.com/owncloud/)
 - [Android_Data (Android 学习资料收集)](https://github.com/Freelander/Android_Data)

 
### 安卓资源相关
 - [安卓每个版本的Drawable图标](http://androiddrawables.com/)
 - [FontAwesome字体图标安卓字符串](https://github.com/liltof/font-awsome-for-android)
 - [色系](http://www.google.com/design/spec/style/color.html)
 - [颜色库](https://github.com/MatthewYork/Colours)
 - [IconFinder图标资源](https://www.iconfinder.com/)
 - [阿里巴巴矢量图](http://www.iconfont.cn/)
 - [icomoon](https://icomoon.io/app/#/select)
 - [AndroidAssetStudio](http://romannurik.github.io/AndroidAssetStudio/)
 - [Android Holo颜色生成器](http://android-holo-colors.com/)
 - [Android Action Bar Style Generator](http://jgilfelt.github.io/android-actionbarstylegenerator/)
 - [在线.9.png图片生成器](http://romannurik.github.io/AndroidAssetStudio/nine-patches.html)
 - [安卓button在线制作工具](http://angrytools.com/android/button/)
 - [Theme.xml属性](http://omapzoom.org/?p=platform/frameworks/base.git;a=blob;f=core/res/res/values/themes.xml;hb=master)
 - [移动APP云计算平台Parse](https://www.parse.com/)

### git
 - [Git教程](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)
 - [用 Git Hooks 进行自动部署](http://segmentfault.com/a/1190000003836345?utm_source=Weibo&utm_medium=shareLink&utm_campaign=socialShare)
 - [Git工作流指南：Forking工作流](http://blog.jobbole.com/76861/)


### Android NoSql

 - [realm-java](https://github.com/realm/realm-java)
 - [couchbase-lite-android](https://github.com/couchbase/couchbase-lite-android)
 - [SimpleNoSQL](https://github.com/Jearil/SimpleNoSQL)
 - [SnappyDB](https://github.com/nhachicha/SnappyDB/)

### 设计网站，可以寻找一些酷炫的设计稿

 - [https://dribbble.com/](https://dribbble.com/)
 - [http://pttrns.com/](http://pttrns.com/)
 - [http://capptivate.co/](http://capptivate.co/)

### 国外个人博客
 - [Jakewharton](http://jakewharton.com/blog)
 - [Romain Guy](http://www.curious-creature.com/)
 - [Cyril Mottier](http://cyrilmottier.com/)
 - [Mark Allison](http://blog.stylingandroid.com/)
 - [Daniel Lew](http://blog.danlew.net/)
 - [Ravi Tamada](http://www.androidhive.info/)
 - [Chris Nash](http://loseyourmarbles.co/about-me/)
 - [juhani@fatrobot.io](http://www.androiduipatterns.com/)
 - [Wolfram Rittmeyer](http://www.grokkingandroid.com/)
 - [Rich Hyndman](http://geekyouup.blogspot.com/)


### 国外的一些优秀网站
 - [androidweekly.net](http://androidweekly.net/)
 - [Android Developers Blog](http://android-developers.blogspot.ca/)
 - [vogella](http://www.vogella.com/tutorials/android.html)
 - [tutorialspoint](http://www.tutorialspoint.com/android/)
 - [tutsplus](http://code.tutsplus.com/categories/android-sdk)
 - [oderzheaven](http://www.coderzheaven.com/android-tutorials/)
 - [thenewcircle](https://thenewcircle.com/training/android/)
 - [coreservlets](http://www.coreservlets.com/android-tutorial/)
 - [Droid-Blog](http://droid-blog.net/)
 - [coursera.org](https://www.coursera.org/)
 - [commonsware.com](http://commonsware.com/blog/archive.html)
 - [http://android.amberfog.com/](http://android.amberfog.com/)
 - [anddev](http://www.anddev.org/)


### Ibeacon与蓝牙4.0相关
 - [一个ibeacon交互库](https://github.com/AltBeacon/android-beacon-library)
 - [AprilBeacon-Android-sdk](https://github.com/AprilBrother/AprilBeacon-Android-SDK)
 - [Estimote SDK](https://github.com/Estimote/Android-SDK)
 - [蓝牙4.0相关](https://github.com/devunwired/accessory-samples)

 

