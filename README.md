<!-- PROJECT SHIELDS -->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
<!-- [![LinkedIn][linkedin-shield]][linkedin-url] -->

<!-- PROJECT LOGO -->

# 计算机网络

整理了计算机网络基础理论知识、和每一层对应的协议，着重画出Http脑图。然后通过Netty实现异步IO加深对网络IO的理解。

公网资料、笔记地址请访问这里

- 文档地址: [http://mkdocs.grft.top/计算机网络/](http://mkdocs.grft.top/计算机网络/)

其他相关技术可以访问我的博客，主页地址请访问这里

- 访问入口：[http://mkdocs.grft.top](http://mkdocs.grft.top)

--------------------

## 基本知识点
计算机网络是由多台计算机组成的系统，这些计算机通过通信媒体（如电缆、电话线、无线信号等）和网络设备（如路由器、交换机、调制解调器等）互相连接和通信，实现数据和资源的共享。

计算机网络可以根据其覆盖范围、设计结构、传输技术等方面进行分类。

## 常见的分类

### 覆盖范围
+ 局域网（LAN，Local Area Network）：通常覆盖一个较小区域，如家庭、学校或办公室大楼。
+ 城域网（MAN，Metropolitan Area Network）：覆盖城市大小的区域。
+ 广域网（WAN，Wide Area Network）：跨越广泛地理区域，可以是国家或全球性的网络。

### 设计结构（网络拓扑）
+ 星型拓扑：所有计算机通过独立的通信线路连接到一个中央节点（通常是一个交换机或路由器）。
+ 总线拓扑：所有计算机共享一条通信线路。
+ 环形拓扑：计算机形成一圈，数据顺着圈传输。
+ 网状拓扑：计算机之间有多条通信线路相互连接，提供多条数据传输路径。

### 传输技术
+ 以太网（Ethernet）：最流行的局域网技术之一，使用特定的数据包和帧结构。
+ Wi-Fi：无线局域网标准，允许设备通过无线信号连接网络。
+ 光纤通信：使用光脉冲来传输数据，可以提供非常高的数据传输速率。

### 计算机网络的核心功能包括以下几点
+ 数据传输：在计算机之间传送文本、图片、音频、视频等数据。
+ 资源共享：共享网络上的硬件（如打印机、扫描仪等）和软件资源（如应用程序、文件等）。
+ 公用服务：如电子邮件、网页浏览、文件传输、远程登录等。

### 网络通信遵循一系列协议，最著名的是TCP/IP模型，它分为四层
+ 链路层（Link Layer）：处理网络的物理连接部分，如电缆、网络接口卡等。
+ 网络层（Internet Layer）：处理数据包在网络中的路由选择，IP协议位于此层。
+ 传输层（Transport Layer）：确保数据有效地、可靠地从源头传输到目的地，主要的协议有TCP（传输控制协议）和UDP（用户数据报协议）。
+ 应用层（Application Layer）：为应用软件提供网络服务，如HTTP（超文本传输协议）、FTP（文件传输协议）等。

### 网络安全
网络安全是计算机网络设计和运营中的重要考虑因素，涉及到保护网络和网络访问设备免受未授权访问、数据泄露和各种攻击（如病毒、木马、钓鱼攻击等）。


--------------------

## 目录

[目录](index.md)

## 计算机理论知识

+ [目录](https://www.yuque.com/hanwenhao-bs03y/ygt7az/rgziz584rvlgkfkn?singleDoc#%20《计算机网络》)
+ [概述](https://www.yuque.com/hanwenhao-bs03y/ygt7az/hngff4ecr4hg96gs?singleDoc#%20《01-概述》)
+ [物理层](https://www.yuque.com/hanwenhao-bs03y/ygt7az/yihte6g7zf4rr11a?singleDoc#%20《02-物理层》)
+ [数据链路层](https://www.yuque.com/hanwenhao-bs03y/ygt7az/ggmphycqdeehgv0h?singleDoc#%20《03-数据链路层》)
+ [网络层](https://www.yuque.com/hanwenhao-bs03y/ygt7az/ursmgfnafp0nhwqv?singleDoc#%20《04-网络层》)
+ [传输层](https://www.yuque.com/hanwenhao-bs03y/ygt7az/hrtzu51vbezyocg8?singleDoc#%20《05-传输层》)
+ [应用层](https://www.yuque.com/hanwenhao-bs03y/ygt7az/ug3dxqest0wq44mx?singleDoc#%20《06-应用层》)
+ [面试常客](https://www.yuque.com/hanwenhao-bs03y/ygt7az/rpzy09hi8w6th5c9?singleDoc#%20《07-面试常客》)


## 网络协议

+ [协议汇总](https://www.yuque.com/hanwenhao-bs03y/ygt7az/ppg9yiddr02875eo?singleDoc#%20《网络协议汇总》)
+ [HTTP协议](https://www.yuque.com/hanwenhao-bs03y/ygt7az/vyg2vx1dhrlggn8y?singleDoc#%20《HTTP%20协议》)


## 异步IO模型

#### Netty

+ [第 1 章 Netty 介绍和应用场景](NIO/netty/netty_chapter/_content/chapter01.md)
+ [第 2 章 Java BIO 编程](NIO/netty/netty_chapter/_content/chapter02.md)
+ [第 3 章 Java NIO 编程](NIO/netty/netty_chapter/_content/chapter03.md)
+ [第 4 章 Netty 概述](NIO/netty/netty_chapter/_content/chapter04.md)
+ [第 5 章 Netty 高性能架构设计](NIO/netty/netty_chapter/_content/chapter05.md)
+ [第 6 章 Netty 核心模块组件](NIO/netty/netty_chapter/_content/chapter06.md)
+ [第 7 章 Google Protobuf](NIO/netty/netty_chapter/_content/chapter07.md)
+ [第 8 章 Netty 编解码器和 Handler 调用机制](NIO/netty/netty_chapter/_content/chapter08.md)
+ [第 9 章 TCP 粘包和拆包及解决方案](NIO/netty/netty_chapter/_content/chapter09.md)
+ [第 10 章 Netty 核心源码剖析](NIO/netty/netty_chapter/_content/chapter10.md)
+ [第 11 章 用 Netty 自己实现 Dubbo RPC](NIO/netty/netty_chapter/_content/chapter11.md)
+ [Netty 源码案例](https://github.com/dongzl/netty-handbook)

#### 其他方式

+ [WebSocket](https://developer.mozilla.org/zh-CN/docs/Web/API/WebSocket)
+ [Swoole](https://wiki.swoole.com/#/)


-------------------

## 贡献者

请阅读**CONTRIBUTING.md** 查阅为该项目做出贡献的开发者。

#### 如何参与开源项目

贡献使开源社区成为一个学习、激励和创造的绝佳场所。你所作的任何贡献都是**非常感谢**的。

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## 版本控制

该项目使用Git进行版本管理。您可以在repository参看当前可用版本。

<!-- ## 作者 -->
<!--  -->
<!-- [小昊子](https://github.com/worst001) -->
<!--  -->
<!-- 制做不易，如果有帮到你就请作者喝杯咖啡吧! -->
<!--  -->
<!-- ![支付宝加微信](https://xiyou-oss.oss-cn-shanghai.aliyuncs.com/%E5%85%AC%E4%BC%97%E5%8F%B7%E4%B8%8E%E6%94%AF%E4%BB%98/%E6%94%AF%E4%BB%98%E5%AE%9D%E5%8A%A0%E5%BE%AE%E4%BF%A1.jpg) -->
<!--  -->
<!-- 作者无聊时做的测试游戏，完全免费哦！ -->
<!--  -->
<!-- ![公众号](https://xiyou-oss.oss-cn-shanghai.aliyuncs.com/%E5%85%AC%E4%BC%97%E5%8F%B7%E4%B8%8E%E6%94%AF%E4%BB%98/%E5%85%AC%E4%BC%97%E5%8F%B7%E5%B0%8F.jpg) -->


## 参考资料

[https://www.bilibili.com/video/BV19E411D78Q](https://www.bilibili.com/video/BV19E411D78Q)

[https://github.com/dongzl/netty-handbook](https://github.com/dongzl/netty-handbook)


### 写在最后的话

因为仓库与文档的数量比较大，有些借鉴资料忘了在`参考文档`部分提及原作者与原仓库，若有疏漏请告诉，我及时补上。

所有引用的原资料都确认是开源认证，若有侵权请告知。

<!-- links -->
[your-project-path]:shaojintian/Best_README_template
[contributors-shield]: https://img.shields.io/github/contributors/worst001/mkdocs_network.svg?style=flat-square
[contributors-url]: https://github.com/worst001/mkdocs_network/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/worst001/mkdocs_network.svg?style=flat-square
[forks-url]: https://github.com/worst001/mkdocs_network/network/members
[stars-shield]: https://img.shields.io/github/stars/worst001/mkdocs_network.svg?style=flat-square
[stars-url]: https://github.com/worst001/mkdocs_network/stargazers
[issues-shield]: https://img.shields.io/github/issues/worst001/mkdocs_network.svg?style=flat-square
[issues-url]: https://img.shields.io/github/issues/worst001/mkdocs_network.svg
[license-shield]: https://img.shields.io/github/license/worst001/mkdocs_network.svg?style=flat-square
[license-url]: https://github.com/worst001/mkdocs_network/blob/main/LICENSE.txt
<!-- [linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555 -->
<!-- [linkedin-url]: https://linkedin.com/in/shaojintian -->
