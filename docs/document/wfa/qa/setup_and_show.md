---
title: 软件安装及显示问题
lang: zh-CN
---

# 软件安装及显示问题

## 我买了软件怎么安装不了

目前，WFA支持Windows10版本号为1703以上的版本。如果你的商店里下载按钮是灰色或者根本没有下载按钮，很可能是你的系统版本过低。

检查系统版本的方法：

按下`Win`+`R`，输入`winver`，回车即可查看当前的系统版本。

如果你的系统版本低于1703，请及时更新系统至最新版本，以保证软件的流畅运行。

## 软件有手机版吗？

**有**，如果你是*WindowsPhone*手机的话。但事实上，由于WP手机名存实亡，所以可视作WFA仅有WIN10桌面版。

如果你想在移动端访问WFA的相关功能服务，有几种解决方案：

1. 访问[WFA网页版](https://wfa.richasy.cn)，网页版采用PWA技术，可以通过将网页保存到桌面的方式，变成一个`本地应用`。
2. 使用合作软件。WFA与多位开发者都保持着良好的合作关系，提供一些基础的[API](../api/)
    - WF国际服：iOS端与安卓端皆有。
    - Warframe Ordis：安卓端应用。

## 能不能多出几个主题

很遗憾，**不能**。UWP应用有个特点，即初始时即限定死最多只能有两套主题，`Light`和`Dark`。所以我在设计软件时就没有考虑过多套主题的情况。

## 为什么我没有Fluent Design（亚克力）效果

如果你的系统版本低于**1709** *（内部OS-16299）*，那么你是无法使用Fluent效果的，建议升级系统。

## 界面过窄导致显示效果差强人意

的确，在有些小屏设备上，WFA的显示效果可能不尽如人意。故此建议小屏用户：

1. 尽量全屏使用软件
2. 如果侧边栏占据大量面积，可以缩小软件宽度，进入移动版界面