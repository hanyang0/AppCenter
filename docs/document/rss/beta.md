---
title: RSS追踪内测说明
lang: zh
date: 2020/8/2 8:28:23
type: post
---

# RSS追踪内测说明

:::tip
该文章是临时性的，内测结束即会删除
:::

RSS追踪V2版本目前已经基本完成了（你可以在侧边查看应用功能介绍），现对外开放内测申请。

## 内测申请适用对象：

1. 已购买RSS追踪本体应用
2. Windows系统版本在 Windows10 ver 1809及以上
3. 使用的在线RSS服务在目前RSS追踪的支持范围内，具体支持的服务请查看[服务支持列表](./service.html)
4. 接受内测阶段可能会出现的BUG及不稳定的情况，遇到问题时能够提供完整的复现步骤。

## 内测申请方式：

请将您的申请信息（格式在下方）发送至开发者邮箱：[Thansy@foxmail.com](mailto:Thansy@foxmail.com)

邮件格式如下：

*标题：*

**[内测申请]RSS Stalker内测申请**

*内容：*

**我的微软账户：xxxx@example.com**

**我目前正在使用的RSS服务：xxxx （指的是Inoreader, Feedly等云服务，不是你的订阅源）**

## 内测生效方式

我会在Microsoft Store开一个外部测试版通道，将你的微软账户添加进该内测群组的列表中。

在收到申请邮件后，我会尽快回复你。在收到我的邮件回复后，请在应用商店中手动检查更新。

## 内测目标及截止日期

:::tip
目前快捷键模块并没有实装，我还在进行市面上主流RSS阅读器的研究
:::

:::warning
由于架构完全推倒重来（从以本地阅读为主改为以在线服务为主），V1版本的数据结构已经无法迁移至新版本，所以本次更新是一次破坏式更新，您需要提前备份您的订阅源数据，并在新版本中通过OPML的方式导入。
:::

由于应用目前大体上没什么问题，所以本次内测时间并不长，初步敲定为两周，即**8月中旬**结束

本次内测的主要目标如下：

1. 测试是否有影响使用体验的BUG
2. 由于Inoreader有API请求限制，需要有10个以上的用户才会提高限额，所以需要进行小范围内测以完成提额申请，故而在内测期间，Inoreader的服务可能不稳定
3. 对NewsBlur的令牌申请已经发出，正在等待回应，可能会在内测期间加上对NewsBlur的支持
4. Feedly已经不做指望，但如果Feedly回应了我的请求，同样可以适配Feedly
5. 完成对快捷键的研究，给应用添加上和主流RSS阅读器相类的快捷键

:::tip
本次内测暂时不会考虑新功能，主要目的是夯实基础。
:::

:::tip
并没有什么内测交流群之类的（我现在越来越少看聊天软件了），如果有什么问题要报告或者提出一些功能建议，请直接发邮件
:::