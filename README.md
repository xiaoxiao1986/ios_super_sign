## ios_super_sign

###### 超级签名 免签封装 安卓打包 企业签名 自助分发多合一系统

最新部署教程 https://github.com/xujimu/ios_super_sign_docker

### 主要功能

1. 基本操作

   - 修改密码
   - 用户信息
   - 共有池
   - 退出

2. 超级签名

   - 应用列表

     - 应用信息

     - 安卓合并
     - 简介编辑
     - 轮播图编辑
     - 分发地址复制
     - 下载码启动
     - 下载码购买地址
     - 删除

   - 上传应用

     - 拖动ipa上传

   - 下载密码

     - 下载码生成
     - 下载码信息显示
     - 删除

3. 证书管理

   - 证书列表
     - 证书信息
     - 剩余设备数
     - 删除
   - 上传证书
     - p8模式证书上传

4. 用户管理

   - 用户列表
     - 用户信息
     - 添加共有池

5. 下载管理

   - 下载记录
   - 对应设备签名的证书下载

6. 免签封装

   - 打包支持自定义信息
     - 应用名称
     - 打包网址
     - 描述文件名称
     - 描述文件机构
     - 描述文件描述信息
     - 描述文件统一信息
     - 应用图标
     - 启动图(仅支持安卓)
     - 苹果图标是否可删除
     - 安卓动态网址
     - 安卓包名
     - 版本
     - 自定义描述文件绿标证书
   - 打包记录
     - 分发地址
     - 分发源码下载地址

7. 企业签名

   - 开始签名
     - 开始签名
     - 编辑签名证书所需共有池
     - 删除
     - 证书备注修改
   - 签名记录
     - 签名记录信息
     - 签名后的ipa包下载
   - 上传证书

8. 自助分发

   - 开始分发
   - 分发记录
     - 分发记录显示
     - 安卓合并更新
     - 苹果更新
     - 简介编辑
     - 分发地址复制
     - 删除

### 架构

---

- 后端 spring boot
- 前端 vue
- 数据库 mysql
- redis
- 其他 redis python openssl androidsdk python unzip java8 java11 zsign

### 部署

---



**准备**

​		*由于该项目环境制作十分复杂,所以使用docker来部署,使用到的都是编译后的jar包和静态文件*

 		1.centos7 服务器必须是干净的 配置的话没什么要求太低会卡 推荐阿里云 阿里云可以使用内网oss分发很   快 如果使用其他服务器只能使用七牛云分发或者自己服务器的带宽
 		2.域名一个 并申请ssl证书 拿到tomcat证书也就是jks后缀 必须是ca认证的 解析到服务器上
		 3.下载发布包

**安装**

最新安装视频教程：https://b23.tv/4ZdXS8c
视频对应的sign文件夹在视频评论区域
 
### 鸣谢
https://github.com/zhlynn/zsign

### 展示

---

![](https://ae04.alicdn.com/kf/H8175f4efd00442899b70cdc100a4cc4d4.jpg)
![](https://ae02.alicdn.com/kf/H54e91a41996f4ace9016d976b03679feU.jpg)
![](https://ae02.alicdn.com/kf/Hf4fcdd3089884144aabb99fd0b9e0da3o.jpg)
![](https://ae02.alicdn.com/kf/H42bbf17c9a7445ecbd0545870a316f33b.jpg)
![](https://ae02.alicdn.com/kf/Hf224715e8e4448e2a7c7419b5ea0eb33u.jpg)
![](https://ae04.alicdn.com/kf/H1887b5e3be104a2395633e768d8c3fabA.jpg)
