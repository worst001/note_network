# IO

## BIO
> 阻塞模型

老师布置任务给学生 学生排队报告情况
老师无法进行其它事情 需要等待

+ 任务的发布和执行没有分离
+ 保证了一致性

## NIO
> 非阻塞模型

### 多路复用

老师布置任务时委托班长
班长记录任务状态(观察者模式)
对于老师来说不需要要等待 每次有任务给到班长
班长发现相似的任务 让相关的学生继续解决
班长本身处于忙的状态
最慢的学生完成时认为完成(短板效应)

+ 本质上解耦了任务发布与任务执行 加上观察者模式去解决
+ 保证了高可用性


## 网关

### Nginx 和 Gateway

[性能比较](https://www.bilibili.com/read/cv5795313/)
其中对Gateway的性能测试是错误的

[Gateway性能](https://www.itmuch.com/spring-cloud-sum/performance-zuul-and-gateway-linkerd/)

## Bus 消息总线
观察者模式

