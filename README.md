# RG_Platform

## 项目介绍
```
本项目为餐饮企业定制软甲产品，包括系统管理后台和移动端应用两部分。其中系统管理后套主要是提供给餐饮企业内部员工使用，可以对餐厅的菜品、套餐、订单等进行管理维护。移动端应用主要提供给消费者使用，可以在线浏览菜品、添加购物车、下单等。

本项目共分为3期进行开发：
第一期主要实现基本需求，其中移动端应用使用H5实现，用户可以通过手机浏览器访问。
第二期主要针对移动端应用进行改进，使用微信小程序实现，用户使用起来更加方便。
第三期只要针对系统进行优化升级，提高系统的访问性能。
```

## 技术选型
```
用户层  H5  VUE.js  ElementUI   微信小程序
```
```
网关层  Nginx
```
```
应用层  SpringBoot  SpringMVC  SpringSession    Spring  Swagger     lombok  
```
```
数据层  Mysql   Mybatis Mybatis Plus    Redis
```
```
工具    git     maven   junit
```

## 功能架构

### 移动端前台（H5 小程序）
```
手机号登陆  文星登录 地址管理 历史订单 菜品规格 购物车 下单
```
### 系统管理后台
```
分类管理 菜品管理 套餐管理 菜品口味管理 员工登录 员工推出 员工管理 订单管理
```

## 角色

### 后台系统管理员
```
登录后台管理系统，拥有后台系统中的所有操作权限
```
### 后台系统普通员工
```
登录后台管理系统，对菜品、套餐、订单等进行管理 
```
### C端用户
```
登录移动端应用，可以浏览菜品、台南佳啊购物车、设置地址、在线下单等
```

## 具体架构

### 数据表
```
序号        表名            说明
1           employee       员工表
2           category       菜品和套餐分类表
3           dish           菜品表
4           setmeal        套餐表
5           setmeal_dish   套餐菜品关系表
6           dish_flavor    菜品口味关系表
7           user           用户表（C端）
8           address_book   地址簿表
9           shopping_cart  购物车表   
10          orders         订单表
11          order_detail   订单明细表
```