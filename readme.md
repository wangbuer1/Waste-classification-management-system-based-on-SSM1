# 基于SSM的垃圾分类管理系统

## 1、项目介绍

基于SSM的垃圾分类管理系统拥有两种角色：用户和管理员。具体功能如下：

![系统功能结构图](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202205291131402.jpg)


## 2、项目技术

后端框架：SSM（Spring、SpringMVC、Mybatis）

前端框架：Bootstrap、html、css、JavaScript、JQuery

## 3、开发环境

- JAVA版本：JDK1.8，其它版本理论上可以
- IDE类型：IDEA、Eclipse、Myeclipse都可以。推荐IDEA与Eclipse
- tomcat版本：Tomcat 7.x、8.x、9.x、10.x版本均可
- 数据库版本：MySql 5.5-5.7
- maven版本：无限制
- 硬件环境：Windows 或者 Mac OS


## 4、功能介绍

### 4.1 登录

![登陆](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202205291131086.jpg)

### 4.2用户 模块

![用户-垃圾分类信息](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202205291131019.jpg)

![用户-垃圾与运输信息](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202205291131456.jpg)

![用户-垃圾站信息](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202205291131820.jpg)

![用户-报修信息](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202205291132298.jpg)

![用户-投诉信息](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202205291132776.jpg)

- 垃圾分类信息：用户可以根据垃圾分类名字，查询分类信息
- 垃圾运输信息：用户可以查看自己小区对应的垃圾运输信息
- 报修信息：用户可以根据关键词搜索自己报修过的信息，并能够增、删、改
- 留言信息：用户可以根据关键词搜索自己留言过的信息，并能够增、删、改
- 垃圾站信息：用户可以根据垃圾站名搜索垃圾站信息

### 4.3 管理员模块

![管理员-垃圾信息管理](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202205291134476.jpg)

![管理员-垃圾站管理](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202205291134836.jpg)

![管理员-垃圾分类信息管理](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202205291134120.jpg)

![管理员-报修管理](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202205291134478.jpg)

![管理员-报修状态修改](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202205291134666.jpg)

![管理员-小区管理](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202205291134832.jpg)

- 小区管理：管理员可以根据小区名搜索小区信息，并能增删改查，还能禁止或开启小区账户
- 垃圾运输信息管理：管理员可以增删改垃圾运输信息
- 垃圾分类管理：管理员可以根据垃圾分类名搜索，，并能增删改查
- 垃圾站管理：管理员可以根据垃圾站名搜索，并能增删改查
- 报修管理：管理员可以根据关键字和小区名（即业主）搜索报修信息，并能修改信息的状态（状态分为“待处理”和“已完成”）
- 投诉管理：管理员可以根据关键字和小区名（即业主）搜索投诉信息，并能修改信息的状态

### 4.4 设计文档目录

![文档目录](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202205291138962.jpg)

## 5、视频演示

[点击播放视频，视频位于文章最后](https://mp.weixin.qq.com/s/S3Xzko_soGHECoU-N8f_eQ)

## 6、获取方式

关注公众号： **程序员王不二**，回复关键词  ： “ **垃圾1**”   



![公众号](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202205281253739.png)

