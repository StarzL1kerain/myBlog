---
title: "Hugo+nginx建站记录"
date: 2023-03-07T21:32:22+08:00
# draft: true
toc: false
images:
tags:
  - 建站
---

建站这个问题我已经想了好久，今天终于完整的实现

从WordPress到hexo以及现在的hugo终于用上了服务器和域名
[参考教程](https://www.cnblogs.com/Kingram/p/15009385.html)
* 简单的说一下这次碰到的问题
* 使用的服务器是腾讯云的服务器Ubuntu20
* 在安装Nginx修改conf.d时找不到这个文件，百度搜了一下竟然看到了我22年底写的一个解决方法[ubuntu20安装nginx后无conf.d目录或conf.d目录下无default.conf文件](https://www.bilibili.com/read/cv20422207 "ubuntu20安装nginx后无conf.d目录或conf.d目录下无default.conf文件")
* 然后就是安装配置好hugo,运行hugo报错，搜了一下是要用拓展版我下的是最新版不支持，拓展版是带extended的