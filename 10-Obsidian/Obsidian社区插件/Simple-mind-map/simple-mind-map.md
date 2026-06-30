---
uid: 20250804120818
title: Obsidian 插件：Simple mind map 值得常备的脑图插件
tags: ['脑图', '思维导图', '效率工具', 'obsidian插件']
description: Obsidian 插件：Simple mind map 在 Obsidian 中创建、编辑、预览和交付思维导图，让 Markdown、双链与脑图工作流衔接起来。
author: OS
type: other
draft: false
editable: false
modified: 20260630114000
---

# Obsidian 插件：Simple mind map 值得常备的脑图插件

> [!Note] 插件名片
> - 插件名称：Simple mind map
> - 插件作者：wanglin2
> - 插件说明：在 Obsidian 中创建、编辑、预览和管理思维导图，支持 Markdown 与脑图互转、节点双链、嵌入编辑、多结构切换和多格式导入导出。
> - 插件分类：['脑图', '思维导图', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/wanglin2/obsidian-simplemindmap)
> - 官方下载：[Obsidian 社区插件页](https://community.obsidian.md/plugins/simple-mind-map)
> - 国内下载：[PKMer 插件市场](https://pkmer.cn/products/plugin/pluginMarket/?simple-mind-map)
> - 专业版介绍：[PKMer SimpleMindMap 落地页](https://pkmer.cn/products/simplemindmap/)
> - 使用文档：[帮助文档](https://github.com/wanglin2/obsidian-simplemindmap/blob/main/docs/help_zh.md)
> - 功能清单：[[10-Obsidian/Obsidian社区插件/Simple-mind-map/README|README]]

![Simple mind map](https://cdn.pkmer.cn/images/202606051235430.gif!pkmer)

## 概述

### Simple mind map 插件总结

1. **主要功能**：在 Obsidian 内直接创建和编辑 `.smm.md` 思维导图文件，并支持将 Markdown 文档预览或转换为思维导图。
2. **适用场景**：适合用 Obsidian 做课程大纲、项目拆解、读书笔记、会议复盘、知识结构梳理和汇报材料准备的用户。
3. **核心特色**：延续 Obsidian 本地优先的使用习惯，支持双链、标签、备注、嵌入编辑、多语言和多结构脑图视图。
4. **使用建议**：如果只需要基础脑图编辑，可从 Obsidian 官方社区插件页或 PKMer 插件市场安装；如果需要更多导入导出、专属结构和交付能力，可查看 [专业版介绍页](https://pkmer.cn/products/simplemindmap/)。
5. 功能清单：[[10-Obsidian/Obsidian社区插件/Simple-mind-map/README|README]]

Simple mind map 是 PKMer 与 wanglin 老师合作推进的 Obsidian 思维导图插件，底层能力来自 [mind-map](https://github.com/wanglin2/mind-map) 项目。它的目标不是替代 Markdown，而是让线性笔记可以在需要时生长为可视化图谱，并在整理、演示、导出之间保持同一套知识资产。

## 快速上手

1. **安装插件**：可通过 [Obsidian 官方社区插件页](https://community.obsidian.md/plugins/simple-mind-map) 安装，也可使用 [PKMer 插件市场](https://pkmer.cn/products/plugin/pluginMarket/?simple-mind-map) 加速下载。
2. **新建脑图**：点击左侧 Ribbon 图标、文件夹右键菜单中的【新建思维导图】，或在命令面板执行【新建思维导图】。
3. **打开视图**：`.smm.md` 文件默认以思维导图视图打开，也可以通过右键菜单或更多菜单切换为 Markdown 文档。
4. **插入文档**：在命令面板输入 `smm`，可快速找到“新建思维导图”和“新建思维导图并插入当前文档”等命令。
5. **调整设置**：可配置主题模式、默认主题、默认结构、文件路径、图片路径和无操作自动保存时间。

## 核心能力

### 文件与视图

- **专用文件格式**：思维导图文件使用 `.smm.md`，文件中包含元数据、压缩后的脑图数据、图像数据和内链数据；修改文件名时不要去掉 `.smm`，否则可能无法正确识别。
- **Markdown 兼容**：支持把 Markdown 文档预览为思维导图，也支持在思维导图与 Markdown 文档之间转换。
- **搜索定位**：开启“是否允许在 OB 中搜索”后，会额外保存节点文本用于 Obsidian 搜索；点击搜索结果可打开思维导图并定位到对应节点。
- **多语言支持**：支持中文、英文、越南语和繁体中文，会跟随 Obsidian 语言自动切换。

### Markdown 与 Obsidian 语法

- 支持 `#`、`##`、`###` 等标题层级自动转为主题节点。
- 支持无序列表嵌套，并保留多层级树状结构。
- 支持 `[[双链]]`、标签、备注等 Obsidian 常用标记。
- 节点超链接可插入 Obsidian 文件链接，便于从脑图节点跳转到具体笔记。

### 脑图编辑体验

- **多结构表达**：支持思维导图、逻辑结构、组织结构、目录结构等常用图谱结构。
- **节点操作**：可编辑文本、添加链接、标签、备注、节点图片，并支持从仓库或本地拖拽文件到节点。
- **画布体验**：支持滚轮、拖拽、快捷键等常见画布操作；按住 `Shift` 时鼠标滚轮可左右移动画布。
- **移动端适配**：针对手机端增加右键菜单图标、大纲编辑辅助按钮，并隐藏部分非必要按钮。

## 推荐工作流

1. **沉淀**：继续在 Obsidian 中使用 Markdown 写作，不打断原有知识库结构。
2. **组织**：把主题拆解为节点、分支、结构和标签，快速建立可视化框架。
3. **关联**：为关键节点添加 Obsidian 双链、标签、备注或附件，让脑图成为知识库入口。
4. **交付**：按需要导出为图片、HTML、Mermaid、表格或其他格式，用于汇报、复盘和协作。

## 专业版能力

> [!tip] 专业版入口
> 更多专业版介绍、购买说明和功能演示见 [PKMer SimpleMindMap 落地页](https://pkmer.cn/products/simplemindmap/)。

专业版面向更复杂的导入导出、结构展示和交付场景，当前落地页重点介绍了以下能力：

- **导出增强**：支持导出 XLSX、FreeMind、JPG、Mermaid、HTML，PDF 导出中的节点超链接可点击。
- **导入增强**：支持导入 XLSX、FreeMind，并支持粘贴 Markdown、TXT 内容导入。
- **专属结构**：提供表格、时间轴、鱼骨图等更适合汇报和分析的结构。
- **节点表达**：支持节点标记、节点编号、节点待办、隐藏节点文本、更多节点形状和连线效果。
- **嵌入编辑**：支持 `smm` 代码块嵌入编辑，可在 Markdown 中直接维护思维导图片段。
- **展示预览**：支持填空模式、字体扩展、新标签页预览为思维导图等演示和阅读能力。

## 版本进展

### 当前公开版本

- GitHub 公开版本曾以 `0.1.2` 为阶段节点，内测版本可能领先于 GitHub 版本。
- 新版本检查、Markdown 导入优化、Markdown 与思维导图互转、搜索定位、移动端适配等能力已逐步完善。
- 具体版本差异建议以 [GitHub 仓库](https://github.com/wanglin2/obsidian-simplemindmap)、[Obsidian 社区插件页](https://community.obsidian.md/plugins/simple-mind-map) 和插件内更新提示为准。

### 内测说明

1. 可通过 PKMer QQ 群或微信群联系管理员，了解内测群资格。
2. 内测群版本可能领先于 GitHub 公开版本一段时间。
3. 入群不需要缴费，注意甄别信息差；入群后请先阅读群公告，并在指定位置友善反馈问题。

## 相关链接

- [GitHub 项目](https://github.com/wanglin2/obsidian-simplemindmap)
- [Obsidian 官方下载页](https://community.obsidian.md/plugins/simple-mind-map)
- [PKMer 插件市场下载](https://pkmer.cn/products/plugin/pluginMarket/?simple-mind-map)
- [PKMer SimpleMindMap 专业版落地页](https://pkmer.cn/products/simplemindmap/)
- [帮助文档](https://github.com/wanglin2/obsidian-simplemindmap/blob/main/docs/help_zh.md)
- [底层 mind-map 项目](https://github.com/wanglin2/mind-map)
- [问题反馈与功能建议](https://github.com/wanglin2/obsidian-simplemindmap/issues)

---