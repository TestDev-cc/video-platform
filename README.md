# 基于Java-VUE-SpringBoot-MySQL的毕业设计-视频管理系统

![登陆界面](https://www.skywalking.pro/download/images/video-platform/WX20230106-174033@2x.png "登陆界面.png")

![用户端界面](https://www.skywalking.pro/download/images/video-platform/WX20230106-170546@2x.png "用户端界面.png")

####  **联系作者** 

![联系作者](https://skywalking-web.oss-cn-chengdu.aliyuncs.com/main-platform-fengfeiyezi.png)

 **这是作者的微信二维码，如需本项目源代码，可扫码或者VX:cyddhao联系作者。**  

![微信二维码-1](https://skywalking-web.oss-cn-chengdu.aliyuncs.com/fengfeiyezi-QR-code.png)

![主页](https://www.skywalking.pro/download/images/video-platform/WX20230106-170632@2x.png "主页.png")

![主页图表](https://www.skywalking.pro/download/images/video-platform/WX20230106-170710@2x.png "主页图表.png")

**系统功能持续更新中。。。**
#### 介绍
 **本系统是基于SpringBoot的视频管理系统，主要的系统构成是系统用户端和系统后端，这是现代JavaEE技术的主要技术架构。它的主要技术组建构成是通过SpringBoot内置的Spring框架，应用服务器，Http解析器，底层数据交互组件（MyBatis框架），分别实现后台代码组件的管理，服务器运行，Http请求交互参数解析的功能，除此之外则为通过现代浏览器技术，基于V8引擎的Node作为运行环境，来开发和运行前端界面。通过以上的技术背景和技术支持，可以实现普通用户在系统的注册，登录，浏览视频，评论视频，转发视频等功能，管理员管理系统的菜单，查询日志，管理视频内容，最终实现视频的传播和管理功能。
 SpringBoot2.X VUE2.6 Antd1.7.2  MyBatisPlus Shiro1.5.0 Java1.8 管理系统 JVM 权限设计 可作为毕业设计和快速开发 视频管理管理系统** 
 
 #### 后台管理系统功能点
|功能点   | 描述  | 备注   |
| :------------: | :------------: | :------------: |
|  权限管理 | 管理系统具备的菜单和按钮权限  | 属于RBAC权限一部分  |
|  系统用户管理 | 管理系统的各种用户  | 属于RBAC权限一部分  |
|  系统角色管理 | 管理系统的各种角色（进行权限控制）  | 属于RBAC权限一部分  |
|  视频管理 | 管理用户发布的视频信息  |   |
|  平台用户管理 | 管理系统的普通用户  |   |

 #### 用户端系统功能点
|功能点   | 描述  | 备注   |
| :------------: | :------------: | :------------: |
|  用户注册 | 平台用户注册  |   |
|  用户登录 | 平台用户登录  |   |
|  视频上传 | 上传视频信息  |   |
|  视频转发 | 平台普通用户之间进行视频转发和消息发送  |   |
|  视频打星评论 | 平台普通用户之间进行视频评论和打星  |   |
|  视频删除| 平台普通用户之删除自己发布的视频  |   |
 
#### 项目所用技术
|技术点   | 描述  | 备注   |
| :------------: | :------------: | :------------: |
|  SpringBoot2.X | 先进的Spring集成框架  | 集成了最新版  |
| VUE2.6  |  前端交互框架 |   |
| ElementUI 2.x |  饿了么出品的前端UI框架 |   |
| ANTD |  阿里出品的图表框架  | 好用且好看  |
| MyBatisPlus | 基于MyBatis封装的ORM框架  |方便查询   |
| Shiro1.5.0 | 经典而好用的权限框架  |  |
| uniapp | 移动端开发框架  |  |
| uview | 高颜值的移动端UI框架  |  |
| Java1.8 | 最常用的Java版本  |使用了Java8新特性  |
| RBAC权限模型|纯动态的菜单权限设计，可控制权限到按钮级别  |纯动态的菜单权限设计  |
#### 清晰的注释
**项目的每个类和方法，都具备清晰的注释，适合阅读，注释如下图：**

**1. 类注释**

![类注释](https://www.skywalking.pro/download/images/meta/WX20230206-092916@2x.png "类注释")

**2. 数据库字段注释注释**

![类注释](https://www.skywalking.pro/download/images/meta/WX20230206-093511@2x.png "类注释")
#### 项目特有优势
1. 清晰的注释，每个方法，类，字段，都具备中文注释。
2. 部署方便，作者编写了一键启动的脚本，可以让Java后端完美运行在主流服务器上。
3. 代码符合行业规范，变量，类，命名简洁优雅。
4. 应用多种市面上的先进技术，方便学习和开发。
5. 具备完整的项目文档和技术文档，方便二次开发。
6. 具备前后端代码生成器，一键生成VUE以及Java后端代码。 
#### 它适合做什么？
1. 适合作为高校毕业设计。
2. 适合作为初学者学习使用。
3. 如果场景适合，可以作为商业使用。
### 联系作者
#### 微信号: cyddhao
#### 管理系统后端演示地址:
```
登录地址: https://www.skywalking.pro/video-platform
登录账号: admin
登录密码: 123456
```
#### 用户端访问地址:
```
访问地址: https://www.skywalking.pro/video-platform/#/PlatformMainPage
```

**若演示程序不可用，可翻到文末扫码联系作者微信或者留言**

### 软件架构说明
该项目采用市面上比较流程的前后端分离架构，以SpringBoot技术栈为后端，以VUE为前端，采用优雅简洁漂亮的UI框架。系统采用前端发起请求，后端处理业务的方式进行交互，相对于传统的JSP，freemarker等技术有较大区别以及先进性。同时在权限控制方面有独到的创新，实现了VUE自定义指令，以控制系统权限到每一个系统按钮。是非常适合作为毕业设计以及学习的系统。
#### 前端技术
1. ElementUI
2. 页面,按钮级别权限控制。
3. 多个组件封装，调用方便。
4. Antv图表组件。
5. WebPack
6. ES6
7. 多环境打包。
8. VUE路由，过滤器，自定义指令。
9. 代码简洁，符合编码规范。
#### 后端技术
1. SpringBoot2.x
2. Shiro权限框架
3. Redis6.X最新版
4. MyBatis注解版
5. MySQL6.7
6. 分模块开发，自定义启动脚本，JVM调优
7. 多环境,前后端完全分离。
8. 代码生成器。
9. orika传输对象映射器。

### 系统技术文档
**为了让读者更好地理解系统技术原理，功能实现方法，故特地准备了系统技术文档，里面包含系统所使用的主要技术框架，运行说明，系统表设计，模块设计等。**
#### 系统技术文档截图

![系统技术文档截图-01](https://www.skywalking.pro/download/images/video-platform/WX20230106-171426@2x.png "系统技术文档截图-01.png")

![系统技术文档截图-02](https://www.skywalking.pro/download/images/video-platform/WX20230106-171509@2x.png "系统技术文档截图-02.png")


### 项目代码展示

#### 系统VUE代码截图展示

![管理系统VUE代码截图展示](https://www.skywalking.pro/download/images/video-platform/WX20230106-171551@2x.png "系统VUE代码截图展示.png")

#### 系统后端Java代码截图展示

![管理系统后端Java代码截图展示](https://www.skywalking.pro/download/images/video-platform/WX20230106-173902@2x.png "管理系统后端Java代码截图展示.png")

#### 数据库表结构展示

![数据库表结构展示](https://www.skywalking.pro/download/images/video-platform/WX20230106-173947@2x.png "数据库表结构展示.png")

### 系统截图展示
#### 系统登陆
- 登陆界面

![登陆界面](https://www.skywalking.pro/download/images/video-platform/WX20230106-174033@2x.png "登陆界面.png")

![主页图表](https://www.skywalking.pro/download/images/video-platform/WX20230106-170710@2x.png "主页图表.png")

#### 系统管理模块
- 系统主页

![主页](https://www.skywalking.pro/download/images/video-platform/WX20230106-170632@2x.png "主页.png")

- 菜单管理

![菜单管理](https://www.skywalking.pro/download/images/video-platform/WX20230106-174124@2x.png "菜单管理.png")

![菜单编辑](https://www.skywalking.pro/download/images/video-platform/WX20230106-174523@2x.png "菜单编辑.png")

- 角色管理

![角色管理](https://www.skywalking.pro/download/images/video-platform/WX20230106-174729@2x.png "角色管理.png")

![角色编辑](https://www.skywalking.pro/download/images/video-platform/WX20230106-174759@2x.png "角色编辑.png")

- 系统用户管理

![系统用户列表](https://www.skywalking.pro/download/images/video-platform/WX20230106-175031@2x.png "系统用户列表.png")

![系统用户编辑](https://www.skywalking.pro/download/images/video-platform/WX20230106-175118@2x.png "系统用户编辑.png")

#### 系统监控模块

- 系统日志

![系统日志](https://www.skywalking.pro/download/images/video-platform/WX20230106-175201@2x.png "系统日志.png")

#### 用户端模块

- 视频评论模块

![视频评论模块](https://www.skywalking.pro/download/images/video-platform/WX20230106-175736@2x.png "视频评论模块.png")

- 查看视频评论模块

![视频评论模块](https://www.skywalking.pro/download/images/video-platform/WX20230106-180427@2x.png "查看视频评论模块.png")

- 用户注册模块

![用户注册模块](https://www.skywalking.pro/download/images/video-platform/WX20230106-175953@2x.png "用户注册模块.png")

- 视频上传模块

![用户注册模块](https://www.skywalking.pro/download/images/video-platform/WX20230106-180302@2x.png "视频上传模块.png")

- 视频转发模块

![视频转发模块](https://www.skywalking.pro/download/images/video-platform/WX20230106-180516@2x.png "视频转发模块.png")

- 消息查看模块

![消息查看模块-01](https://www.skywalking.pro/download/images/video-platform/WX20230106-180605@2x.png "消息查看模块-01.png")

![消息查看模块-02](https://www.skywalking.pro/download/images/video-platform/WX20230106-180649@2x.png "消息查看模块-02.png")

#### 管理系统业务模块

- 平台用户管理模块

![平台用户管理模块](https://www.skywalking.pro/download/images/video-platform/WX20230106-175227@2x.png "平台用户管理模块.png")

- 视频管理模块

![视频管理模块](https://www.skywalking.pro/download/images/video-platform/WX20230106-175318@2x.png "视频管理模块.png")

![视频预览模块](https://www.skywalking.pro/download/images/video-platform/WX20230106-175351@2x.png "视频预览模块.png")

![视频审核模块](https://www.skywalking.pro/download/images/video-platform/WX20230106-175513@2x.png "视频审核模块.png")

#### 后台系统功能模块概要
+ 系统登陆
+ 系统主页
  - 系统主页折线图统计
    * 系统主页折线图统计
    + 系统模块导航
    - 系统在线数，访问数统计
+ 系统管理
  - 系统用户管理
    * 系统用户条件查询
    + 系统用户修改
    - 系统用户删除
  - 系统用户新增
  - 系统菜单管理
    * 系统菜单条件查询
    + 系统菜单修改(可级联修改)
    - 系统菜单删除
  - 系统菜单新增
  - 系统角色管理
    * 系统角色条件查询
    + 系统角色修改
    - 系统角色删除
  - 系统角色新增
  - 系统字典管理
    * 系统字典条件查询
    + 系统字典修改
    - 系统字典删除
  - 系统字典新增
+ 系统监控
  - 在线用户管理
    * 在线用户条件查询
    + 在线用户踢出
  - 系统日志管理
    * 系统日志条件查询
    + 系统日志分析
  + 系统访问IP分析
+ 平台用户管理
  - 平台用户管理
    * 平台用户条件查询
    + 平台用户新增
  * 平台用户修改
    + 平台用户批量删除
+ 视频信息管理
  - 视频信息列表
    * 视频信息条件查询
    + 视频信息新增
  * 视频预览
  * 视频审核
  * 视频信息修改
    + 视频信息批量删除



#### 演示地址
```
登录地址: https://www.skywalking.pro/video-platform
登录账号: admin
登录密码: 123456
```
若演示地址不可用，可扫码联系作者微信或者留言

####  **联系作者** 
![联系作者](https://skywalking-web.oss-cn-chengdu.aliyuncs.com/main-platform-fengfeiyezi.png)

 **这是作者的微信二维码，如需本项目源代码，可扫码或者VX:cyddhao联系作者。**  

![微信二维码-1](https://skywalking-web.oss-cn-chengdu.aliyuncs.com/fengfeiyezi-QR-code.png)

#### 安装教程

#### 后端安装方法

```
1.  mvn clean package
2.  tar -zxvf health-record-api.tar.gz (解压tar包)
3.  cd health-record-api
5.  sh /sbin/startup.sh dev
```
#### 前端安装方法

```
1.  yarn install (安装node_moudle)
2.  yarn start (启动)
3.  yarn build:pro (构建生产包)
```
