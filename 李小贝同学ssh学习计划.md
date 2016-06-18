# 李小贝同学ssh学习计划

> 张小乐老师出版


假设李小贝同学已经完全掌握Java语法相关知识。本学习计划本着由易到难的原则，一步步让李小贝同学学习，使用，调优ssh框架。

本学习内容在Ubuntu上完成。李小贝同学需要在一个全新的Ubuntu系统搭建Java环境，Tomcat，Intellij等。

## Servlet

Servlet 作为 JavaWeb 基础，几乎所有 JavaWeb 框架都基于它。

### 学习目标

- [ ] 了解 Tomcat 目录结构，部署流程和相关命令
- [ ] 学会配置 web.xml 文件
- [ ] 了解 Tomcat 对静态资源的处理
- [ ] 学会使用简单的 Servlet API
- [ ] 学会使用 JSP

### 训练任务

- [ ] 使用 Servlet 实现一个简易的用户登录。

	- 用户输入用户名：`test`，密码：`password`时，返回登录成功
	- 用户输入用户名：`test`，密码非`password`时，返回密码错误
	- 用户输入用户名非 `test` 时，返回无此用户
	- 提交时要求用户必须填写用户名和密码，否则不予提交

- [ ] 使用Servlet实现简易的图片裁剪
	- 用户上传图片，并输入裁剪坐标`(left,top)`，`(right,bottom)`
	- 使用Java对图片进行剪裁返回给用户剪裁后的图片

### 时间限制
总时长：3-5天
#### 学习时间

1-2 天

#### 实践时间 

2-3 天

## SpringMVC

SpringMVC 是基于 Servlet 的 web 框架，其比 Servlet 更加规范，方便，易于测试。

### 学习目标

- [ ] 了解 Spring MVC Web 请求转发结构
- [ ] 学会使用 Spring MVC 注解
- [ ] 学会使用 Srping MVC API
- [ ] 学会使用 EL 语言

### 训练任务

同 Servlet 训练任务，需要使用 Spring MVC 实现

- [ ] 使用 Servlet 实现一个简易的用户登录。

	- 用户输入用户名：`test`，密码：`password`时，返回登录成功
	- 用户输入用户名：`test`，密码非`password`时，返回密码错误
	- 用户输入用户名非 `test` 时，返回无此用户
	- 提交时要求用户必须填写用户名和密码，否则不予提交

- [ ] 使用Servlet实现简易的图片裁剪
	- 用户上传图片，并输入裁剪坐标`(left,top)`，`(right,bottom)`
	- 使用Java对图片进行剪裁返回给用户剪裁后的图片

### 时间限制
总时长：3-5天
#### 学习时间

1-2 天

#### 实践时间 

2-3 天

## Hibernate

## Spring

## ssh整合

## 项目实践