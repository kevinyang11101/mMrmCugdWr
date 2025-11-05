# 前言

欢迎来到本仓库！这里为您分享一款小型企业客户关系管理系统，该系统是基于Java语言和MySQL数据库开发而成的实战项目。该项目适用于毕业设计或学习交流之用，包含源码、文档报告以及详细的代码讲解。希望这份分享能够帮助到您，下面请跟随我一起来了解这个项目吧！

# 内容介绍

小型企业客户关系管理系统旨在帮助企业更好地管理和维护客户信息，提高客户满意度。本系统主要实现了以下功能：

1. 客户信息管理：包括客户基本信息录入、修改、查询和删除等操作。
2. 客户关系维护：记录客户跟进情况，提高客户满意度。
3. 数据报表：生成各类报表，便于企业分析客户数据，为决策提供依据。
4. 用户权限管理：确保系统安全，实现不同角色的权限控制。

# 技术介绍

本项目采用以下技术栈：

## 语言：Java

## 使用框架：Spring Boot

## 前端技术：JS、Vue、CSS3

## 开发工具：IDEA/Eclipse

## 数据库：MySQL 5.7/8.0

## 数据库管理工具：phpstudy/Navicat

## JDK版本：jdk1.8

## Maven：apache-maven 3.8.1-bin

## 前端环境：Node.Js 12/14/16

# 核心代码

以下是项目中的一段核心代码，展示了如何使用Spring Boot和Vue实现客户信息查询功能：

```java
// Controller层
@RequestMapping("/getCustomerList")
public String getCustomerList(@RequestParam("page") int page, @RequestParam("limit") int limit) {
    PageHelper.startPage(page, limit);
    List<Customer> customers = customerService.getCustomerList();
    PageInfo<Customer> pageInfo = new PageInfo<>(customers);
    return JSONObject.toJSONString(pageInfo);
}

// Vue前端代码
<template>
  <div>
    <el-table :data="customerList" style="width: 100%">
      <el-table-column prop="name" label="客户名称"></el-table-column>
      <el-table-column prop="phone" label="联系电话"></el-table-column>
      <el-table-column prop="address" label="地址"></el-table-column>
      <!-- ... -->
    </el-table>
  </div>
</template>
```

# 免费源码获取

```
8000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img14.360buyimg.com/ddimg/jfs/t1/309410/31/26207/204959/689e9fccFb7e532ce/416e8c2a06a39321.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/319947/23/25081/82469/689e9faaF7eeeae49/42b95ad1ffc98424.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/320894/31/24732/155140/689e9fadFebb07aed/f3c40e9f53c92997.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/327983/3/4716/31418/689e9faeFe6e55785/31cb6368fba46ab1.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/317761/33/25319/30028/689e9fb0F3b3cfdd4/874b2efe6867033c.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/324743/19/4822/61252/689e9fb0F6266b8f6/c2f874e429226b9f.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/328023/20/4579/29880/689e9fb1Fa7242146/6406a47dbc21fff2.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/311025/14/26768/152957/689e9fb1F5d2c4e64/fe6159d3614d4429.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/315639/26/26351/56363/689e9fb2F975049b9/4c3486af76f3cba0.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/311680/11/26427/35045/689e9fb2Fbbd816e7/7af1b13294da3442.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
