# 科大二手工坊


**写在前面：**

感谢各位小伙伴们的支持，最近比较忙，后续有更新一定告知大家（2020.12.09）

## 项目介绍

基于SSM的校园二手物品交易平台
（项目包括前台和后台）


### 首页截图

![image.png](https://s2.loli.net/2021/12/18/pT2a8w1PgmKlQUk.png)

### 后台截图

![image.png](https://s2.loli.net/2021/12/18/aehXmsMySWorbZI.png)

## 运行环境

开发工具 IDEA

安装运行环境：

1. `jdk1.8` 
2. `Tomact8`或`Tomcat8.5`
3. `maven3.5`

数据库：MySQL 

## 启动项目

1. 使用IDEA打开项目

2. 编辑Tomcat配置

![QQ截图20211218171208.png](https://s2.loli.net/2021/12/18/UJR5dW6LDYjvIbt.png)

3. 配置Tomcat路径、jre环境、端口号

![QQ图片20211218171636.png](https://s2.loli.net/2021/12/18/H28jI7PM5yvNUAL.png)

4. 将项目war包添加至tomcat中

![QQ图片20211218172006.png](https://s2.loli.net/2021/12/18/RveWbpOrSstMgUi.png)

5. 在你的`tomcat`中建立`images`文件夹

![image.png](https://s2.loli.net/2021/12/20/qjlAst3E58JP9u6.png)

6. 在idea中配置images图片资源目录

![image.png](https://s2.loli.net/2021/12/20/qjlAst3E58JP9u6.png)

7. 选择刚刚在tomcat中建立的文件夹，点击ok

 ![images](https://s2.loli.net/2021/12/20/ZNocujMeFawLfqd.png)
 
8. 

![image.png](https://s2.loli.net/2021/12/20/qjlAst3E58JP9u6.png)

9. 启动项目访问网址：localhost:8088/goods/index

## 项目说明

**端口号暂时固定为8088，不要更改其它的tomact端口号**

**不建议用Tomcat9哦！版本过高会出现不兼容的问题**

访问网址：localhost:8088/goods/index

学生用户登录 15232103749/123456

管理页面登录：localhost:8088/admin/toLogin

系统管理员用户登录  17611006666/aaa

### 项目中可能遇到的问题

**可以在这里提交issues：**[项目遇到的问题和建议看这里 · Issue #19 · lvr1997/kd-second-hand-workshop (github.com)](https://github.com/lvr1997/kd-second-hand-workshop/issues/19)

**PS: 如果感兴趣的话可以添加qq群 696224249 一起讨论哦^v^**

## 更新情况

2020.04.14 
1. 项目部分调整，保证能启动
2. 添加数据库`sql`文件，在`src/main/java/resources`目录下

2020.12.09

1. 更新pom依赖
2. 添加git忽略文件

2020.12.10

1. 更新至Spring5.x版本 

2020.12.11

1. 修复项目启动访问页面报404问题
2. 修改项目名 **kd-second-hand-workshop**

2021.01.05

1. 统一项目根路径

2021.12.17

1. 修复在Tomcat8.0及8.5运行环境下项目启动报404的问题

2. 修复在个人中心查看自己购买的商品时，还可以购买自己的商品的bug

2021.12.20

1. 修复上传图片会存到target目录的bug

2. 修复用户累计收入收出功能漏洞

3. 清空除用户表、地址表以外其他表添加的测试数据

## 功能模块

前台部分：
- [x] 首页
    - [x] 分类展示
    - [x] 闲置检索
    - [x] 发布闲置
- [x] 学生用户登录
    - [x] 找回密码
    - [x] 注册
- [x] 发布/想要
    - [x] 管理我发布的闲置
    - [x] 管理我想要的闲置    
- [x] 用户留言（收到的留言，发布的留言）
- [x] 个人信息管理
- [x] 订单管理
- [x] 意见反馈
- [x] 累计收入，累计支出
- [x] 模拟支付
- [x] 收货地址管理
- [x] 闲置收藏

后台管理系统部分：

- [x] 首页轮播图管理
- [x] 闲置管理
- [x] 分类管理
- [x] 举报管理
- [x] 留言管理
- [x] 订单管理

****