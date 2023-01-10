#动态能力演示

##目录

*【导言】（#导言）
*【准备环境】（#准备环境）
*【入门】（#入门）
*【示例代码】（#示例代码）
*【结果】（#结果）
*【问题或问题】（#问题或问题）
*【许可证】（#许可证）

##简介
动态能力SDK是华为AppGallery参考App Bundle技术动态加载特性的一套解决方案。第三方应用集成动态能力SDK后，可以在必要时从华为应用市场下载特性，减少网络流量和终端存储空间的消耗。
【阅读更多关于动态能力SDK的信息】（https://developer.huawei.com/consumer/cn/doc/development/AppGallery-connect-Guides/agc-featuredelivery-introduction）。

##准备环境
硬件要求：
1、PC
2、华为手机

软件要求：
1、JDK 1.8及以上版本
2、Android API 21及以上版本
3. Android Studio 3.2或更高版本。与本指南相关的案例在Android Studio 3.5上运行。

##入门
使用Android Studio打开解压后的工程。在AppGallery Connect中创建项目和应用程序。

##示例代码
动态能力SDK支持下载和安装功能、获取安装状态、中止安装功能、延迟卸载功能和其他一些功能。

示例代码：src\main\java\com\huawei\android\dynamicfeaturesplit\SampleEntry.java

##结果
运行应用程序后，您应该看到这样的屏幕：
<img src="资产/2020-02-29-12-14-11.png"高度="534"宽度="300"风格="最大宽度：100%;">

##问题或问题
如果您对如何使用AppGallery Connect Demos有疑问，请尝试以下选项：
*【堆栈溢出】（https://stackoverflow.com/questions/tagged/appgallery）是任何编程问题的最佳地点。请务必使用appgallery标记您的问题。
*【华为开发者论坛】（https://forums.developer.huawei.com/forumPortal/en/home?fid=0101188387844930001）AppGallery模块非常适合一般问题或寻求建议和意见。

如果您在我们的示例中遇到错误，请向存储库提交【问题】（https://github.com/AppGalleryConnect/agc-demos/issues）。更好的是，您可以提交带有修复程序的【拉取请求】（https://github.com/AppGalleryConnect/agc-demos/pulls）。

##许可证
动态能力演示在【Apache许可证，版本2.0】（http://www.apache.org/licenses/LICENSE-2.0）下获得许可。