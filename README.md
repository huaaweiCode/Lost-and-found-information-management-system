# 失物招领信息管理系统

## 1、项目介绍

失物招领信息管理系统1拥有两种角色，分别为管理员和用户，具体功能如下：

管理员：招领信息管理、寻物信息管理、留言信息管理、申请信息管理、物品类型管理、学生管理、管理员管理、公告管理

用户：招领信息查看与发布、寻物信息查看与发布、留言查看与发布，个人信息查看及修改


## 2、项目技术

后端框架：JFinal、 Servlet、mvc模式

前端框架：FreeMarker、html、css、JavaScript、JQuery

## 3、开发环境

- JAVA版本：JDK1.8，其它版本理论上可以
- IDE类型：推荐IDEA
- tomcat版本：Tomcat 7.x、8.x、9.x、10.x版本均可
- 数据库版本：MySql 5.x、8.0都可
- maven版本：无限制
- 硬件环境：Windows 或者 Mac OS


## 4、功能介绍

### 4.1 登录

![登录](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202205202032770.jpg)

管理员和用户均可以通过此界面登录至系统，前端会自动校验信息

### 4.2用户 模块

![首页](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/202205202033437.jpg)

![用户-查看个人发布的招领信息](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/%E7%94%A8%E6%88%B7-%E6%9F%A5%E7%9C%8B%E4%B8%AA%E4%BA%BA%E5%8F%91%E5%B8%83%E7%9A%84%E6%8B%9B%E9%A2%86%E4%BF%A1%E6%81%AF.jpg)

![用户-查看寻物信息](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/%E7%94%A8%E6%88%B7-%E6%9F%A5%E7%9C%8B%E5%AF%BB%E7%89%A9%E4%BF%A1%E6%81%AF.jpg)

![用户-查看寻物信息详情](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/%E7%94%A8%E6%88%B7-%E6%9F%A5%E7%9C%8B%E5%AF%BB%E7%89%A9%E4%BF%A1%E6%81%AF%E8%AF%A6%E6%83%85.jpg)

![用户-查看招领信息](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/%E7%94%A8%E6%88%B7-%E6%9F%A5%E7%9C%8B%E6%8B%9B%E9%A2%86%E4%BF%A1%E6%81%AF.jpg)

![用户-查看招领信息详情并申请认领](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/%E7%94%A8%E6%88%B7-%E6%9F%A5%E7%9C%8B%E6%8B%9B%E9%A2%86%E4%BF%A1%E6%81%AF%E8%AF%A6%E6%83%85%E5%B9%B6%E7%94%B3%E8%AF%B7%E8%AE%A4%E9%A2%86.jpg)

![用户-发布感谢信息](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/%E7%94%A8%E6%88%B7-%E5%8F%91%E5%B8%83%E6%84%9F%E8%B0%A2%E4%BF%A1%E6%81%AF.jpg)

![用户-发布寻物信息](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/%E7%94%A8%E6%88%B7-%E5%8F%91%E5%B8%83%E5%AF%BB%E7%89%A9%E4%BF%A1%E6%81%AF.jpg)

![用户-发布找零信息](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/%E7%94%A8%E6%88%B7-%E5%8F%91%E5%B8%83%E6%89%BE%E9%9B%B6%E4%BF%A1%E6%81%AF.jpg)

- 招领信息查看预发布：用户可以发布招领信息，以及查看别人发布的招领信息和申请认领
- 寻物信息查看与发布：用户可以发布寻物信息，以及查看别人发布的寻物信息
- 留言查看与发布：用户可以查看留言墙，还可以发布留言
- 个人信息查看及修改：用户可以修改个人信息

### 4.3 管理员模块

![管理员-公告管理](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/%E7%AE%A1%E7%90%86%E5%91%98-%E5%85%AC%E5%91%8A%E7%AE%A1%E7%90%86.jpg)

![管理员-管理员信息管理](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/%E7%AE%A1%E7%90%86%E5%91%98-%E7%AE%A1%E7%90%86%E5%91%98%E4%BF%A1%E6%81%AF%E7%AE%A1%E7%90%86.jpg)

![管理员--留言信息管理](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/%E7%AE%A1%E7%90%86%E5%91%98--%E7%95%99%E8%A8%80%E4%BF%A1%E6%81%AF%E7%AE%A1%E7%90%86.jpg)

![管理员-申请信息管理](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/%E7%AE%A1%E7%90%86%E5%91%98-%E7%94%B3%E8%AF%B7%E4%BF%A1%E6%81%AF%E7%AE%A1%E7%90%86.jpg)

![管理员-物品类型管理](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/%E7%AE%A1%E7%90%86%E5%91%98-%E7%89%A9%E5%93%81%E7%B1%BB%E5%9E%8B%E7%AE%A1%E7%90%86.jpg)

![管理员-学生管理](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/%E7%AE%A1%E7%90%86%E5%91%98-%E5%AD%A6%E7%94%9F%E7%AE%A1%E7%90%86.jpg)

![管理员-寻物信息管理](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/%E7%AE%A1%E7%90%86%E5%91%98-%E5%AF%BB%E7%89%A9%E4%BF%A1%E6%81%AF%E7%AE%A1%E7%90%86.jpg)

![管理员-招领信息管理](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/%E7%AE%A1%E7%90%86%E5%91%98-%E6%8B%9B%E9%A2%86%E4%BF%A1%E6%81%AF%E7%AE%A1%E7%90%86.jpg)

- 招领信息管理：管理员可以通过物品类型筛选招领信息，还可以编辑和删除招领信息，已经找到丢失人的记录状态会被设置为“已找到失主”，且删除和编辑操作会被设置为无法执行。
- 寻物信息管理：管理员可以通过物品类型筛选寻物信息，还可以编辑和删除寻物信息。其它同招领信息管理
- 留言信息管理：管理员可以查看和删除留言
- 申请信息管理：管理员可以查看和删除申请招领记录
- 物品类型管理：管理员可以增删改查物品类型信息
- 学生管理：管理员可以通过学号、姓名、专业查询学生，还可以增加、删除和修改学生信息
- 管理员管理：管理员可以增删改查管理员信息
- 公告管理：管理员可以查看和发布公告

### 4.4 文档目录

![目录](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/%E7%9B%AE%E5%BD%95.jpg)

## 5、获取方式

扫描下方，回复 “ **失物招领1**” ，即可获取完整版的项目代码。

![https://gitee.com/](https://project-images-1256969109.cos.ap-chongqing.myqcloud.com/Typora-Images/%E5%85%AC%E4%BC%97%E5%8F%B7.png)

