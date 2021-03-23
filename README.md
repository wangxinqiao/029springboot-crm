# 029springboot crm客户关系管理系统
029springboot crm客户关系管理系统


#### 介绍
- 本应用是一个客户关系管理系统，主要包括五大模块，分别是营销管理，客户管理，服务管理，统计报表和系统管理，为客户关系管理提供简单的数据管理与分析
- 技术选型方面，该项目是一个`SpringBoot`的单体应用，项目使用`SpringBoot2`框架快速开发，数据访问层使用`Mybatis`框架，页面渲染引擎使用`Freemarker`，页面样式使用`Layui`，日志方面选用的是`logback`，统计报表部分使用的是`ECharts`,数据库使用的Mysql 8.0版本；

- 在线演示地址：[CRM-智能办公](http://wuhunyu.top:1212/crm)，账号：**admin**，密码：1234

- 源码获取： [**点此下载** ](http://www.shuyue.fun/?type=productinfo&id=179)

#### 安装教程
1.  在mysql(默认为mysql8)中创建名为`crm`的数据库，并执行源码根目录的`crm.sql`脚本生成数据库表以及数据
2.  将项目源码导入idea中，指定项目的jdk版本为jdk8或以上，并标记为maven项目，下载所需依赖
3.  修改`application.yml`中针对于数据库的配置(主要是数据库名和数据库密码)
4.  修改logback.xml中，第4行，日志文件的存储地址，改为自己的路径；
5.  启动项目测试是否正常，默认启动地址首页为`http://localhost:1212/crm`，默认数据库中的管理员为`admin`，密码为`123456`，可在登录系统之后自行修改用户密码

## 运行截图
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/174355_63d6bc22_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/174409_3c860b84_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/174418_8a9f3011_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/174427_e4274507_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/174436_48c5d585_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/174444_7e116f53_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/174452_8d56ee92_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0317/174500_c0d51b26_863230.png "屏幕截图.png")
