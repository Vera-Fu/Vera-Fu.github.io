---
title: Wild Star
date: 2022-06-02 22:43:22
author: VeraFu
img: ../images/Wild%20Star01.png
top: true
hide: false
cover: false
coverImg: 
toc: false
mathjax: false
summary: 《Wild Star》是一款使用Nintendo SDK开发的弹幕射击游戏。游戏中共有四个关卡，关卡中有各种不同的敌人。击败敌人，提高评价，获取金币，强化自身，征服这颗荒野星球吧！
categories: 已发布游戏（个人项目）
tags:
  - C语言
  - OpenGL
  - 弹幕射击
---
# Wild Star

***

### 制作时间

- 2021年6月

### 制作工具

- Nintendo SDK

### 游戏标签

- 弹幕射击

### 游戏简介

- 《Wild Star》是一款使用Nintendo SDK开发的弹幕射击游戏。游戏中共有四个关卡，关卡中有各种不同的敌人。击败敌人，提高评价，获取金币，强化自身，征服这颗荒野星球吧！

### 实机截图

![](../images/Wild%20Star01.png)

![](../images/Wild%20Star02.png)

![](../images/Wild%20Star03.png)

### [演示视频&游戏本体（Dropbox）](https://www.dropbox.com/sh/xi3mzvilghraa4e/AADiySN6eN3t-UAPBofzy_PYa?dl=0) 

### [演示视频&游戏本体（腾讯微云）](https://share.weiyun.com/wwKzFreR) 

（注: 由于本体仅可在Switch开发机上运行，故此处不包含游戏本体。）

### [源码](https://github.com/Vera-Fu/Wild-Star.git)

***

### 游戏制作详情

- 本游戏为HAL校方组织的游戏设计比赛项目的参赛作品。使用的制作工具为Nintendo SDK，游戏的类型为弹幕射击。最终获得了由学校颁发的意欲赏。
  
- 本游戏制作的主要目的是了解与熟悉游戏的Initialize、Update、Draw、UnInitialize四大基本循环，了解与熟悉游戏制作的流程。

- 游戏的主体为《飞机大战》式的弹幕射击，但在此基础上加入了商店，机体强化，关卡选择，场景切换，简单的敌人AI等设计。

- 游戏中共含四大关卡，关卡中有不同的敌人，敌人有各种不同的攻击方式。游戏的难度颇高，在班级同学（试玩者约7-8人）的试玩中无人顺利通过第一关，仅有一人见到了第一关的关底BOSS。但敌人的出现时机以及攻击方式均是固定的，玩家进行记忆以及熟悉以后每一关均可尝试无伤通关。为此我亦为游戏加入了关卡最高分以及关卡评价的设计，给予了玩家重复挑战的欲望。

### 碎碎念

- 虽然作为一个游戏该有的基本要素都有了，但其实就是一个平平无奇的弹幕射击游戏……

- 整个游戏开发过程中花费时间比较多的还是在AI和关卡的调整设计上吧，当时写AI的时候就是用了粗暴的if else，自己甚至也没有意识到这是游戏AI，所以其实就是一个简单的固定移动和根据剩余血量的进行的固定攻击方式。
  
- 关卡的调整设计就是敌人的出现时机，关卡的长度等等。我自己在设计的时候是按照着自己可以无伤过的标准来设计的。但在后续同学的试玩中发现难度还是太高了……我也在差不多这个时候听到了一个观点：“如果一个游戏的难度对于设计师来说正好，那么对于玩家来说那难度肯定是偏高的。”

- 因为没有游戏本体可供试玩，所以就，谢谢你看我的游戏。