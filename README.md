# company-oa-system

## 介绍
### 基于微信小程序的企业办公自动化(OA)系统

该系统旨在通过微信小程序为企业员工提供便捷的办公服务，包括但不限于考勤打卡、任务管理、薪资查询等功能。同时，它还提供了后台管理系统，方便企业管理者进行员工信息、请假记录等的管理。

#### 功能结构图
管理端
![](./images/m1.png)
客户端
![](./images/c1.png)


## 软件架构
系统分为三个端：客户端（微信小程序）、管理端（Web应用）和服务端。

- **客户端**：使用原生微信小程序实现，提供给企业员工使用。
- **管理端**：使用Layui框架实现，供企业管理者进行各种管理操作。
- **服务端**：采用Java SpringBoot框架搭建，负责处理业务逻辑和数据交互。

##### 使用的技术栈：
- **客户端**：微信小程序
- **管理端**：HTML、CSS、JavaScript、Layui、Ajax、jQuery
- **服务端**：Java JDK8、SpringBoot、Mybatis
- **数据库**：MySQL
- **开发工具**：Idea、HBuilderX、微信小程序开发者工具、xampp、Navicat

## 安装教程
1. 启动MySQL服务，创建数据库`company_oasystem`，并导入数据库文件`company_oasystem.sql`。
2. 在Idea中打开`CompanyOAServer`项目，修改`application.yml`中的数据库连接信息，然后启动项目。
3. 打开管理端项目`CompanyOAManager`于HBuilderX中，调整`AppConfig.js`内的服务器配置，并设置web服务器（如Nginx或Apache；推荐使用xampp集成环境）。
4. 使用微信小程序开发者工具打开`CompanyOA`项目，编辑`request.js`文件中的服务端地址与端口号，之后运行项目。
5. 测试客户端与管理端登录，确保系统正常运作。

## 效果图
- **客户端**
  ![](./images/c2.png)
  ![](./images/c3.png)
  ![](./images/c4.png)
  ![](./images/c5.png)
  ![](./images/c6.png)
  ![](./images/c7.png)
  ![](./images/c8.png)
  ![](./images/c9.png)
  ![](./images/c10.png)
  ![](./images/c11.png)
  ![](./images/c12.png)
  ![](./images/c13.png)
  ![](./images/c14.png)
  ![](./images/c15.png)
  ![](./images/c16.png)
- **管理端**
  ![](./images/m2.png)
  ![](./images/m3.png)
  ![](./images/m4.png)
  ![](./images/m5.png)
  ![](./images/m6.png)
  ![](./images/m7.png)

## 资料
#### 功能概述
![](./images/d2.png)
#### 客户端UI概念
![](./images/d3.png)
#### 数据库实体设计
![](./images/d1.png)

#### 写在最后
所有代码以及数据库全部开源，都是我们自己写的，如果觉得有用， **麻烦点个star、watch、fork三连，凭截图联系我获取源码** ，谢谢！ !!! 仅用于学习交流，请勿商用或者用于违法用途！ 如果部署搭建途中有任何问题随时可以联系我，我们也可以定制开发。
我们接所有项目定制开发、技术支持，有需要可以联系我，谢谢！
邮箱：1373577355@qq.com
wx：Awake778

#### ！！！技术支持收费，大家都时间珍贵，白嫖先生勿扰！！！！！！！！
![img.png](images/wx.jpg)

# 技术支持
 - 方案1：我这边按照需求开发完成，部署、简单讲解，后期有任何技术问题随时可以问。
 - 方案2：跟着我做，我带着做，边做边讲，后期有任何技术问题随时问，小修改免费修改。


### 我们的技术栈：
#### 前端技术
- **Web开发**: VUE, Element, Bootstrap, LayUI
- **微信小程序**: 原生开发, Taro
- **移动应用开发**:
  - Android（Java）
  - iOS（Swift）
- **跨平台开发**: uniapp

#### 后端技术
- **Java生态系统**:
  - 框架：Spring, SpringBoot, SpringSecurity
  - 数据持久层：MyBatis, JPA
- **其他后端语言**: PHP, Python, Node.js

#### 数据库管理
- **关系型数据库**: MySQL, SQLServer, SQLite, Oracle
- **非关系型数据库**: MongoDB
- **缓存与搜索**: Redis, ElasticSearch

#### 服务器与部署
- **操作系统部署运维调试**: Linux, Windows
- **容器化与编排**: Docker部署, Kubernetes (k8s)部署
- **Web服务器配置**: Nginx, Apache, Tomcat, IIS
- **CI/CD与版本控制**: Jenkins部署, Git部署, SVN部署

#### 其他技术能力
- **数据分析**: 基于Java的分析工具, 基于Python的分析工具
- **爬虫开发**: 基于Java
- **自动化测试**: 接口测试（基于Java）, 自动化测试（基于Java）
- **自动化运维与监控**:
  - 自动化部署（基于Java） 
  

标签：
- company-OA - 企业OA系统
- wechat-miniprogram - 微信小程序
- spring-boot - Spring Boot
- mysql-database - MySQL数据库
- layui-admin - Layui管理界面
- java-backend - Java后端
- opensource-project - 开源项目