---
layout: default
title: V2Ray Client for Linux
---

## 怎样在ubuntu(分64位/32位)系统安装v2ray客户端？

> 前面的话：

> ubuntu系统中的v2ray客户端分为64位和32位，针对不同的系统架构。下载客户端的时候，需要对应下载。可以命令行界面运行下面的命令，获得系统架构的参数。

```
getconf LONG_BIT
```

> 同Windows系统一样，其它程序借助v2ray客户端，才能实现番茄。本教程中的程序是chromium。

> chromium安装之后，switchyomega插件和配置文件安装方法与windows下chrome浏览器安装方法相同。参考[这里][1]。

### 安装V2Ray客户端

64位系统，点击[这里][3]下载；32位系统，点击[这里][2]下载。

先解压，进入解压文件夹后，运行客户端。需要的命令分别如下：

```
unzip v2ray-v3.21-linux*   //解压软件包
./v2ray 			//运行客户端
```

不要关闭命令行窗口，最小化即可。只要程序在运行，chrome浏览器处于可番茄状态。

#### Ubuntu下v2ray客户端安装结束！


[1]:<{{ site.baseurl }}{% post_url 2018-2-1-V2ray-Client-For-Windows %}>
[2]:<http://w8.undervineyard.com/v2ray-v3.21-linux-32-configured.zip>
[3]:<http://w8.undervineyard.com/v2ray-v3.21-linux-64-configured.zip>