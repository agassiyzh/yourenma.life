---
title: 缘起
categories:
  - daily
author_staff_member: james
show_comments: true
---

这个项目起源2021年10月24日小电内部Hacker Day。

这次挑战由我一个人完成。报名的时候初衷很简单。由于平时在公司，上个厕所非常不方便。尤其是早上GST（golden shit time），有时候要跑6、7、8楼6个厕所才能占到一个坑位。还有就是会议室，有些时候经常看到线上已经约不到了。但是跑到会议室（却还空着），这个时候就能捡个漏。我们是不是可以远程获取到厕所和会议室有没有人的状态。

## 动手做

整个方案实现有这些部分：

1. 树莓派装了一个Home Assistant
2. ESP8266刷入了 ESPEasy
3. 在ESP8266上接入了一个红外人体感应器
4. 通过ESP8266 联网通过MQTT把状态汇集到Home Assistant
5. 为了展示成果，买了个yourenma.life的域名，简单写了个官网

## 那天比赛

1. TODO List

![](/images/1024/reminder.png)

2. 工位

![](/images/1024/P1002981.JPG)
![](/images/1024/P1002989.JPG)
![](/images/1024/P1002988.JPG)
![](/images/1024/P1002990.JPG)

3. 板子们

![](/images/1024/P1003016.JPG)
## 展开讲讲

其实可以想见，关于人体检测可以在很多场景中得到应用。

比如帮助商家做客流分析。

## 关于团队

在核心商业逻辑跑通之前只有`我`。