# 《Spring Cloud与Docker微服务架构实战 第二版》Docker章节（12-14章）配套代码

- 本Repo是《Spring Cloud与Docker微服务架构实战 **第二版**》Docker章节（12-14章）的配套代码，**第一版**的配套源码详见Camden分支。
- 所有Docker Compose采用Version 3 file format编写。
- 1-11章配套代码详见：<http://git.oschina.net/itmuch/spring-cloud-docker-microservice-book-code>




## 交流

- QQ群：731548893，欢迎加入
- 个人博客：[http://www.itmuch.com](http://www.itmuch.com)
- 微信：![微信公众号](wx.jpg)


**持续更新Spring Cloud、Docker相关知识**，敬请关注！！




## 目录说明

#### 一、docker-1-simple

* 使用Maven的Docker插件构建Docker镜像。详见其中的microservice-discovery-eureka目录。
* 使用Docker Compose编排Spring Cloud微服务。



#### 二、docker-2-eureka-ha

* 使用Docker Compose编排高可用的Eureka Server



####  三、docker-3-complex

* 综合示例，使用Docker Compose编排Spring Cloud微服务体系，并实现动态伸缩。


#### 四、docker-host

使用Docker Compose编排Spring Cloud微服务，使用host网络模式。该方式不适合生产，实体书里也没写。仅供参考、把玩。

#### 五、ELK

在第十一章用到ELK，考虑到对ELK不熟悉的朋友们，提供ELK的Compose文件。



