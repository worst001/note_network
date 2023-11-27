# 计算机网络

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


------------------------

## 计算机理论知识

### 参考文档

[目录       ](https://www.yuque.com/hanwenhao-bs03y/ygt7az/rgziz584rvlgkfkn?singleDoc# 《计算机网络》)

[概述       ](https://www.yuque.com/hanwenhao-bs03y/ygt7az/hngff4ecr4hg96gs?singleDoc# 《01-概述》)

[物理层     ](https://www.yuque.com/hanwenhao-bs03y/ygt7az/yihte6g7zf4rr11a?singleDoc# 《02-物理层》)

[数据链路层 ](https://www.yuque.com/hanwenhao-bs03y/ygt7az/ggmphycqdeehgv0h?singleDoc# 《03-数据链路层》)

[网络层     ](https://www.yuque.com/hanwenhao-bs03y/ygt7az/ursmgfnafp0nhwqv?singleDoc# 《04-网络层》)

[传输层     ](https://www.yuque.com/hanwenhao-bs03y/ygt7az/hrtzu51vbezyocg8?singleDoc# 《05-传输层》)

[应用层     ](https://www.yuque.com/hanwenhao-bs03y/ygt7az/ug3dxqest0wq44mx?singleDoc# 《06-应用层》)

[面试常客   ](https://www.yuque.com/hanwenhao-bs03y/ygt7az/rpzy09hi8w6th5c9?singleDoc# 《07-面试常客》)

### 基本介绍
计算机网络是指将多台计算机连接起来，使它们能够进行通信和共享资源的系统。通过计算机网络，人们可以远程访问其他计算机上的文件、传输数据、发送电子邮件、浏览网页等。

+ 节点（Nodes）
    + 节点是指网络中的计算机设备，如个人电脑、服务器、路由器等。每个节点都有一个唯一的标识符，称为 IP 地址，用于在网络上进行寻址和定位。
+ 链接（Links）
    + 链接是指节点之间的物理或逻辑连接。这些链接可以通过有线（如以太网、光纤）或无线（如 Wi-Fi、蓝牙）技术来实现。
+ 协议（Protocols）
    + 协议是计算机网络中的规则和约定，用于确定数据如何在网络中传输、交换和处理。常见的网络协议包括 TCP/IP、HTTP、FTP、DNS 等。
+ 拓扑结构（Topology）
    + 拓扑结构描述了计算机网络中节点和链接之间的布局方式。常见的拓扑结构包括总线型、星型、环形、网状等。
+ 网络设备（Network Devices）
    + 网络设备用于连接和管理计算机网络。例如，路由器用于在不同网络之间转发数据包，交换机用于连接多台计算机设备，并帮助它们进行通信。
+ 网络服务（Network Services）
    + 网络服务是通过计算机网络提供的各种功能和应用程序。例如，电子邮件、文件传输、远程登录、网页浏览等都是基于网络服务实现的。

计算机网络的好处包括资源共享、远程访问、高效通信、数据传输等。同时，计算机网络也面临一些挑战，如安全性问题、网络拥塞、可靠性等。


## 网络协议

### 参考文档

[协议汇总](https://www.yuque.com/hanwenhao-bs03y/ygt7az/ppg9yiddr02875eo?singleDoc# 《网络协议汇总》)

[HTTP协议](https://www.yuque.com/hanwenhao-bs03y/ygt7az/vyg2vx1dhrlggn8y?singleDoc# 《HTTP 协议》)

### 基本介绍
计算机网络涉及到许多不同的协议，这些协议定义了在网络中进行通信和数据传输的规则和标准。

+ 互联网协议（IP）
    + IP 协议用于在网络上对数据包进行寻址和路由选择，它定义了数据包的格式、地址分配和寻址方式。
+ 传输控制协议（TCP）
    + TCP 是一种面向连接的协议，提供可靠的数据传输服务。它负责将数据分割成小块，并通过 IP 网络将它们从源主机传输到目标主机，并在接收端重新组装。
+ 用户数据报协议（UDP）
    + UDP 是一种无连接的协议，提供不可靠但更高效的数据传输服务。它将数据打包成数据报，并通过 IP 网络发送，但不保证数据的可靠性和顺序。
+ 域名系统（DNS）
    + DNS 协议用于将主机名解析为 IP 地址。它提供了一个分布式的命名系统，使得用户可以使用易记的域名来访问互联网资源。
+ 超文本传输协议（HTTP）
    + HTTP 协议用于在客户端和服务器之间传输超文本文档。它是 Web 浏览器和 Web 服务器之间的通信协议，支持客户端发送请求和服务器返回响应。
+ 文件传输协议（FTP）
    + FTP 协议用于在客户端和服务器之间进行文件传输。它允许用户通过 FTP 客户端从服务器上下载文件或将文件上传到服务器。
+ 简单邮件传输协议（SMTP）
    + SMTP 协议用于在邮件服务器之间传输电子邮件。它定义了电子邮件的格式、编码方式以及如何在不同的邮件服务器之间进行交换。
+ 动态主机配置协议（DHCP）
    + DHCP 协议用于自动分配 IP 地址和其他网络配置信息给计算机设备。它允许计算机在加入网络时自动获取所需的网络设置。

## 异步IO模型

### 参考文档

#### Netty

[第 1 章 Netty 介绍和应用场景             ](NIO/netty/netty_chapter/_content/chapter01.md)

[第 2 章 Java BIO 编程                    ](NIO/netty/netty_chapter/_content/chapter02.md)

[第 3 章 Java NIO 编程                    ](NIO/netty/netty_chapter/_content/chapter03.md)

[第 4 章 Netty 概述                       ](NIO/netty/netty_chapter/_content/chapter04.md)

[第 5 章 Netty 高性能架构设计             ](NIO/netty/netty_chapter/_content/chapter05.md)

[第 6 章 Netty 核心模块组件               ](NIO/netty/netty_chapter/_content/chapter06.md)

[第 7 章 Google Protobuf                  ](NIO/netty/netty_chapter/_content/chapter07.md)

[第 8 章 Netty 编解码器和 Handler 调用机制](NIO/netty/netty_chapter/_content/chapter08.md)

[第 9 章 TCP 粘包和拆包及解决方案         ](NIO/netty/netty_chapter/_content/chapter09.md)

[第 10 章 Netty 核心源码剖析              ](NIO/netty/netty_chapter/_content/chapter10.md)

[第 11 章 用 Netty 自己实现 Dubbo RPC     ](NIO/netty/netty_chapter/_content/chapter11.md)

[Netty 源码案例                           ](https://github.com/dongzl/netty-handbook)

#### 其他方式
[WebSocket](https://developer.mozilla.org/zh-CN/docs/Web/API/WebSocket)

[Swoole](https://wiki.swoole.com/#/)

### 基本介绍
NIO（New I/O）是 Java 平台提供的一种基于通道和缓冲区的 I/O 模型。 它引入了一组新的 API，用于实现更高效、非阻塞的 I/O 操作。
在传统的 I/O 模型中，每个 I/O 操作都会导致线程被阻塞，直到操作完成。这意味着在同时处理多个连接或请求时，需要使用多线程来管理并发性，而每个线程都需要占用系统资源。这种模型在面对大量的并发连接时，容易造成资源浪费和性能问题。
NIO 则采用了基于事件驱动的模型，通过少量的线程来处理大量的连接。

+ 通道（Channel）
    + 通道是 NIO 中与数据源（如文件、套接字等）进行交互的对象。可以将通道看作是传统 I/O 中的流的替代品。通道可以读取和写入数据，并支持非阻塞模式。
+ 缓冲区（Buffer）
    + 缓冲区是 NIO 中用于存储数据的对象。它是一个连续的内存块，可以读取和写入数据。通过缓冲区，可以有效地进行数据的读取和写入操作。
+ 选择器（Selector）
    + 选择器是 NIO 中的关键组件，用于监控多个通道的状态。选择器能够检测到通道是否准备好进行读取或写入操作，并将操作分发给相应的处理程序。
+ 非阻塞 I/O 操作
    + NIO 提供了非阻塞的 I/O 操作，这意味着在没有数据可用时，线程不会被阻塞，而是继续执行其他任务。这使得单个线程可以同时处理多个连接和请求。

NIO 的优势在于它能够提供更高的并发性和吞吐量，适用于处理大量的并发连接和高负载的网络应用程序。然而，相对于传统的阻塞 I/O，NIO 编程模型更为复杂，需要更深入的理解和使用。
