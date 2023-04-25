---
uid: 20230329145808
title: Obsidian 插件：Floating TOC
description: 
tags: 
author: cuman
type: other
draft: false
editable: false
modified: 20230414160859
public: yes
---

# Obsidian 插件：Floating TOC

# 概述

Floating Toc 插件能实现悬浮目录。悬浮目录的效果近似你在其他网页文字处理协同上见到的效果，一般会悬浮在网页左侧，。简单来说就是在侧边存在能根据正文中标题文字自动生成的大纲。之前，我也介绍过另一款 TOC 插件：[[Dynamic Toc（TOC插件）]]。

## 效果&特性

- 生成一个浮动的标题目录，在笔记文档的左侧
    ![Pasted image 20230122190116.png](https://s1.vika.cn/space/2023/04/14/c265c37e4c5f4118b43e07eda49a8083?attname=floatingtoc.gif)

- 可以在编辑模式，阅读模式下运行
- 录跟踪当前滚动的位置，并同步高亮显示
- Ctrl + 鼠标左键点击目录，可以折叠/展开当前目录。
- 支持 [[多窗口模式]]

## 安装

1. 打开社区插件市场
2. 搜索 "floating toc"
3. 安装
4. 开启插件

# 实际操作

安装并启动插件，自动在左边形成悬浮目录。

插件的设置页面如下

![image.png](https://s1.vika.cn/space/2023/04/14/3bfcf87972494efc9f13fe61f22e072a)

- 浮动目录显示位置 可以选择悬浮目录的位置，是居左还是具右，还是两边对齐。
- 目录文字左对齐 是目录标题的对齐方式 一般默认即可
- 是否忽略顶级目录 如果开启，一级标题就不会显示在目录中
- 是否默认钉在笔记上 默认浮动标题是鼠标移动到面板边缘才触发，开启后浮动目录默认一直显示。
- 是否开启标题提示 默认鼠标放在标题上会有完整的标题提示。
- 插件样式设置
	通过安装 [[obsidian-style-settings]] 插件可以获得更多的插件样式设置

	 ![195370659-d77a7c31-1711-42b3-80fc-3b9a06eb9b0c.gif](https://s1.vika.cn/space/2023/04/14/b643f21a6dd8431486e796a91085b435)

> [!info] 技巧
> 比如有些想要少数派的风格的 可以如下设置
> - 外观设置 显示层级线 设置为 default
> - 图标代替指示条 关闭
> - 在指示条旁边显示标题上下级
> - 笔记背景模糊效果设置 开启模糊效果的选项关闭
> - ![](https://s1.vika.cn/space/2023/04/14/9185d53cfccc4b0dbd0d66870170cb70)

## 相关视频

[Obsidian 这款浮动目录插件，文章越长使用起来越方便_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1Ze4y1C7Yw/)