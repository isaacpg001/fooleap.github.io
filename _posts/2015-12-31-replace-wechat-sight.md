---
layout: post
title: 替换 iOS 版微信小视频
description: "昨日，看表弟在群里发一小视频，有几分钟时间长，而且还是原腾讯视频的。我认为那肯定不是用微信录制的，而是通过某些手段实现的。随便搜索了一下，点开了一个教程，却被误导，于是决定写一篇不大必要的教程。"
date: 2015-12-31 08:50:00 +0800
thumb: IMG_PATH/wechat.png
category: tech
tags: [微信, 小视频, iPhone, iOS]
---

昨日，看表弟在群里发一小视频，有几分钟时间长，而且还是原腾讯视频的。我认为那肯定不是用微信录制的，而是通过某些手段实现的。随便搜索了一下，点开了一个教程，却被误导，于是决定写一篇不大必要的教程。

为什么说不必要？似乎 iOS 版微信 6.2 以后，微信小视频模块有些变化，替换后可能会出现发送失败的情况。我用的微信版本是 6.1.5 版，以下的环境为已越狱 iOS 6、6.1.5 版微信。

{% include media.html type="video" src="IMG_PATH/replace-wechat-sight-01.mp4" poster="IMG_PATH/replace-wechat-sight-01.mp4?vframe/jpg/offset/1" %}

## 录制小视频并临时保存

在微信主界面下拉拍摄小视频并保存即可。

## 替换掉保存的视频及首帧截图

此前，在 [备份 iOS 版微信小视频](/backup-wechat-sight.html) 说过自己临时保存的小视频在以下目录：

    Library/WechatPrivate/2e69ade238c7b7e8f308fe5d25a41a24/Sight/draft/

每个微信号中间那串加密的字符串各不相同，准备好大小合适的 MP4 格式视频文件（个人认为 3M 以下较好，可使用 QQ 影音压缩）及 JPG 格式的首帧截图（一般宽度为 240 像素）。文件名改为微信保存后的文件名，并替换掉原文件。

## 选择已替换的小视频发送

按正常发送姿势发送即可。

**本文历史**

* 2015 年 12 月 31 日 完成初稿
