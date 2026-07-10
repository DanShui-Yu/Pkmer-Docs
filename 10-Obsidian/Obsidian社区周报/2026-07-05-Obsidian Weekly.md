---
uid: 20260710135526
title: Obsidian Weekly 2026-07-05：编辑与同步新选择 & 手写压感支持
tags: [Weekly, Obsidian]
description: Obsidian Weekly 2026-07-05：编辑与同步新选择 & 手写压感支持
author: 淡水鱼,熊猫别熬夜,PKMer
type: other
draft: false
editable: false
modified: 20260710135546
---

# Obsidian Weekly 2026-07-05：编辑与同步新选择 & 手写压感支持

> [!Abstract]
> **统计时间**：2026-06-28 21:00 ~ 2026-07-05 21:00
> **声明**：本栏目灵感来源于 _Eleanor Konik_ 女士于 2021 年 4 月至 2023 年 6 月期间写作发表的一系列 [Obsidian Roundup](https://www.eleanorkonik.com/tag/roundup/) 文章，如有兴趣可关注原作者的个人网站 [Obsidian Iceberg](https://www.eleanorkonik.com/)；内容来源于 Obsidian 官方 Discord 频道和相应项目在 Github 或其独立网站上的信息。描述中可能存在基于个人理解进行的修改，如有错谬欢迎指正。感谢 Obsidian 团队为我们带来如此优秀的软件。

## 插件新闻

### 社区插件

#### 新增

> [!Tip]
> 由于 AI 审核的引入，近期上架插件数量出现爆炸式增长，编者目前精力有限，故仅能选择性收录并简单介绍，详情可前往新版插件页面 [Obsidian Community](https://community.obsidian.md/) 获取。

##### 人工智能与大语言模型集成

[EchoWiki](https://obsidian.md/plugins?id=echowiki) By _mohammadmaso_

> 使用本地大语言模型代理，将原始笔记和语音转录整理为结构化、互联的维基库。

[Codex Usage](https://obsidian.md/plugins?id=codex-usage) By _0libote_

> 通过托管本地助手，在 Obsidian 中显示 CodexBar 风格的 AI 编码使用数据。

[Vault Companion for Claude](https://obsidian.md/plugins?id=vault-companion-for-claude) By _estrenuo_

> 在桌面端和移动端与 Claude 对话。经您批准后，Claude 可通过您自己的 Anthropic API 密钥或自托管中继的 Claude 订阅，读取、搜索、创建和更新库中的笔记。

[Parallax](https://obsidian.md/plugins?id=consensus-research) By _maxonamission_

> 研究思维的成型之地：搜索前先探索问题，权衡来自 OpenAlex 和 Semantic Scholar 的证据，挑战你的框架，追踪你的信念，并保持方法论记录。

![图片](https://raw.githubusercontent.com/maxonamission/obsidian-parallax/master/docs/screenshots/problem-exploration.png)

[DeepSeek CLI Chat](https://obsidian.md/plugins?id=deepseek-cli) By _hxxxl_

> 在 Obsidian 中与 DeepSeek 模型对话

[Huanmuyu](https://obsidian.md/plugins?id=huanmuyu) By _jiangzizhao_

> 多语言每日打卡、朗读、划词保存生词库学习系统

[Promptbox](https://obsidian.md/plugins?id=promptbox) By _istefox_

> 本地优先的 AI 提示词库，支持分类、搜索和快速复用。

[AI Commit](https://obsidian.md/plugins?id=ai-commit) By _arumata_

> 通过 DeepSeek AI 为 Obsidian Git 生成有意义的提交信息

[CloudWeave](https://obsidian.md/plugins?id=cloudweave) By _abcamus_

> Obsidian 白板的云存储文件节点 +AI 分析。支持从阿里云、百度网盘、夸克网盘、OneDrive 浏览和插入文件。

![图片](https://raw.githubusercontent.com/abcamus/cloudweave/master/asset/demo.png)

[Scan to Markdown](https://obsidian.md/plugins?id=scan-to-markdown) By _swift_

> 使用手机扫码拍照，经大语言模型视觉模型将书本、公式、表格内容转换为 Markdown，直接写入当前笔记光标处或另存为新笔记。

[Chew It](https://obsidian.md/plugins?id=chew-it) By _leweii_

> 在侧边栏使用大语言模型分析当前笔记——生成大纲、核心概念解释和精炼摘要。支持 Claude（Anthropic）和任何 OpenAI 兼容 API。

[PantryFin](https://obsidian.md/plugins?id=pantryfin) By _crx2003_

> AI 驱动的膳食规划器，将食材从食品储藏室流转到餐桌。移动端优化，支持中文食材识别和卡路里追踪。

[Postcraft](https://obsidian.md/plugins?id=postcraft) By _turuhiro26-hub_

> 一键将选中的笔记转换为可直接发布的 X（推特）和 LinkedIn 草稿。匹配你的写作风格。需自带 Claude API 密钥。

[MiMo](https://obsidian.md/plugins?id=mimocode) By _kxwu222_

> 将小米 MiMo 作为 AI 助手引入侧边栏！

[Mistal Spell Checker](https://obsidian.md/plugins?id=mistral-spell-checker) By _saintbyte_

> 基于 Mistral AI 的拼写检查器。

[Aide](https://obsidian.md/plugins?id=aide) By _doko89_

> 由 OpenAI 兼容 API 驱动的 AI 写作助手。

[InsightMesh Viewer](https://obsidian.md/plugins?id=insightmesh-viewer) By _aucontraire_

> 只读浏览 InsightMesh 溯源信息：每个生成的维基页面背后的对话、检查点、决策和差异。

[Video Summarizer and Transcript Generator](https://obsidian.md/plugins?id=wayinvideo-video-summarizer-and-transcript-generator) By _wayinvideo_

> 使用 WayinVideo 创建视频摘要和带说话人标记的转录文本。

---

##### 任务与项目管理

[Sector Tasks](https://obsidian.md/plugins?id=sektor-tasks) By _leotomhal_

> 以直观、基于时间的方式处理任务的仪表板，按可配置标签分组。需要 Obsidian 的 Task 插件和单文件存储。

![图片](https://raw.githubusercontent.com/leotomhal/sector-tasks-obsidian/master/img/overview.png)

[Move Done Down](https://obsidian.md/plugins?id=move-done-down) By _mihanentalpo_

> 将已完成的顶级 Markdown 任务块下移到已完成任务尾部之前。

[Bamboo Immortals](https://obsidian.md/plugins?id=bamboo-immortals) By _miaoziguan_

> 基于 OGAS 理念的中国风目标自动化管理系统——竹林修仙传。

[Docket](https://obsidian.md/plugins?id=docket) By _myeongsoyi_

> 项目管理：支持状态、截止日期和甘特图/工作分解结构/看板视图的项目、任务和子任务管理。

[Task Deck](https://obsidian.md/plugins?id=task-deck) By _ismailivanov_

> 类 Trello 的任务看板，支持 Markdown 卡片、标签、日期和检查清单。

![图片](https://github.com/user-attachments/assets/6bfa709d-2cf8-4900-a274-9e95927541b4)

[Pie Tasks](https://obsidian.md/plugins?id=pie-tasks) By _pieofmind_

> 跨多个看板管理 Markdown 文件中的任务。即时切换任务文件，以看板、列表、日历或仪表板视图查看，复选框状态直接写回文件。

[DDL Radar](https://obsidian.md/plugins?id=ddl-radar) By _yzyhhhstudy_

> 库内计算机科学会议截止日期倒计时：侧边栏面板、笔记内截止日期看板、前言关联倒计时横幅和状态栏徽章。

[Bullet-time](https://obsidian.md/plugins?id=bullet-time) By _novitcz_

> 将无序列表转换为甘特图风格时间线 █ █ █ ▒ ▒
![图片](https://github.com/user-attachments/assets/caf2dccc-2e63-4b92-8092-8f29f49295c8)

[Random Task Selector](https://obsidian.md/plugins?id=random-task-selector) By _jaidetree_

> 从光标处的检查清单中随机抽取一个任务，并为任务标记选中时间/完成时间。

![图片](https://raw.githubusercontent.com/jaidetree/obsidian-random-task/master/docs/assets/preview.gif)

[Gym Workout Tracker](https://obsidian.md/plugins?id=gym-workout-tracker) By _piero24_

> 使用模板、日历视图和快速数据录入追踪健身锻炼。无库文件混乱，所有数据存储在单个文件中。

![图片](https://raw.githubusercontent.com/Piero24/obsidian-gym-tracker/main/assets/gym.png)

[Pomodoro Calendar](https://obsidian.md/plugins?id=pomodoro-calendar) By _allone5_

> 带有动画彩虹进度条和 CalDAV 日历集成的番茄钟插件

[Konbini Kanban](https://obsidian.md/plugins?id=konbini-kanban) By _nickvo_

> 在 Bases 视图中将笔记组织为 Linear 风格看板，支持状态列、拖拽更改状态、优先级、标签和子问题。

[PARA-Tree](https://obsidian.md/plugins?id=para-tree) By _sparky-code_

> PARA 库的 Git 图风格视图：领域是主干，项目是功能分支，资源是提交——查看工作如何向上关联到你的生活领域。

[Bracket to Checkbox](https://obsidian.md/plugins?id=bracket-to-checkbox) By _2jihan_

> 输入 [ ] 后按空格，将其转换为 Markdown 复选框 (- [ ])。

[Sobriety Tracker](https://obsidian.md/plugins?id=sobriety-tracker) By _tiancaijb_

> 戒断恢复的冲动计时器、每日签到提醒和连续天数追踪。

---

##### 编辑与格式

[Toastmaster](https://obsidian.md/plugins?id=toastmaster) By _tikitock_

> 可配置的 Toast 通知持续时间和关闭控制，让通知不会在你读完前消失。

[Caption Numbering](https://obsidian.md/plugins?id=caption-numbering) By _zhangyitong625-zjuchem_

> 使用六级标题（######）自动为图/表标题编号。

[Auto Headings](https://obsidian.md/plugins?id=auto-headings) By _aarlert_

> 自动标题编号，支持完全自定义模板、按文件夹规则、白名单和反向链接同步。双语界面（英文/中文）。

[Spreadsheet Table](https://obsidian.md/plugins?id=spreadsheet-table) By _q7jxb7yxdk-star_

> Markdown 表格的电子表格风格编辑、公式和渲染。

[Floating Text Overlay](https://obsidian.md/plugins?id=floating-text-overlay) By _liaoqiuyi681-blip_

> 可移动、可调整大小的浮动 Markdown 标签，链接到笔记文本并随文档滚动。

[Plain Links Tools](https://obsidian.md/plugins?id=plain-links-tools) By _soheidon_

> 让裸邮箱地址和选中的链接在 Obsidian 中表现为纯文本。

[Mass Editor](https://obsidian.md/plugins?id=mass-editor) By _ondreu_

> 强大的库内批量搜索和编辑：嵌套 AND/OR 查询构建器、安全的批量前言/标签/正文操作、备份和撤销。

[Image Auto Rename](https://obsidian.md/plugins?id=image-auto-rename) By _milin-jad_

> 使用文件名和每个文件的序列号，自动重命名新创建、粘贴或当前文件的图片。

[Hilo](https://obsidian.md/plugins?id=hilo) By _san, opellen_

> 使用 Obsidian 原生==文本==语法的多色高亮。

[Indented Table](https://obsidian.md/plugins?id=indented-table) By _nnyj_

> 渲染列表项内缩进的 Markdown 管道表格。

[Better Tables](https://obsidian.md/plugins?id=better-tables) By _yaye-work_

> 如果你对在笔记中制作表格感到沮丧，请安装这个。通过 ```Table``` 块召唤交互式表格。只需拖拽即可调整大小和重新排序，悬停插入，点击编辑。

[Rich Table](https://obsidian.md/plugins?id=rich-table) By _sdking_

> 支持合并、样式和选择列的富表格，围栏代码块内支持 wiki 链接。

[Comic Scripter](https://obsidian.md/plugins?id=comic-scripter) By _victoriadouglas_

> 漫画脚本的自动页码和面板编号。

[InkedMark](https://obsidian.md/plugins?id=inkedmark) By _pcrausaz_

> 在 Markdown 笔记中手写，支持压感墨迹、可搜索文本层、内联草图和 Apple Pencil 支持。

[Scalosaurus](https://obsidian.md/plugins?id=scalosaurus) By _polygonhunter_

> 使用拖拽手柄调整嵌入图片大小，并将尺寸写回 wiki 链接，支持吸附到列宽。

---

##### 同步与备份

[Sync Deck](https://obsidian.md/plugins?id=sync-deck) By _ismailivanov_

> 跨设备的实时库同步和团队在线状态。

[Hybrid Git Sync](https://obsidian.md/plugins?id=hybrid-git-sync) By _wk-obsidian_

> 跨平台 Git 同步插件。桌面端使用原生 git，移动端使用 GitHub/GitLab API。

[MDFriday Sync](https://obsidian.md/plugins?id=mdfriday-sync) By _mdfriday, mdfriday2_

> 使用 CouchDB 跨设备同步 Obsidian 库——支持端到端加密、选择性同步和实时同步。支持桌面端和移动端。

[Propsync](https://obsidian.md/plugins?id=propsync) By _ragnavig_

> Propsync 是一个按组同步笔记间标准属性的 Obsidian 插件。

[Contact Forge](https://obsidian.md/plugins?id=contact-forge) By _raulanatol_

> Obsidian 是你的联系人的唯一可信源；将选定子集单向同步到 macOS 通讯录，并提供不同步警报。

![图片](https://raw.githubusercontent.com/raulanatol/obsidian-contact-forge/master/docs/images/settings.png)

[Vault Link](https://obsidian.md/plugins?id=vault-link) By _armalv_

> 在库之间链接文件和文件夹，使它们在磁盘上共享相同内容，支持按文件排除规则保留库特定内容（如主题）。

[Local Sync](https://obsidian.md/plugins?id=local-sync) By _liuboacean_

> 局域网双向库同步——CRDT 自动合并、PSK 认证、UDP 发现

[Ztsd Vault Backup](https://obsidian.md/plugins?id=ztsd-vault-backup) By _aplikofi_

> 使用原生 Zstandard 压缩流、SHA256 完整性检查和 GFS 时间分层保留的高性能库备份。

[Secure Git Sync](https://obsidian.md/plugins?id=secure-git-sync) By _vinci0007_

> 密码确认的 Git 同步，支持可选的加密远程笔记快照。

[Wisdio Companion](https://obsidian.md/plugins?id=wisdio-companion) By _young-caveman_

> 将 Wisdio 浏览器笔记与本地 Obsidian 库同步。

[Google Drive Vault Sync](https://obsidian.md/plugins?id=google-drive-vault-sync) By _haniewicz_

> 使用 Google Drive 的 Obsidian 库双向自动/手动同步。

[Slogs Sync](https://obsidian.md/plugins?id=slogs-sync) By _dimohy_

> 将 Markdown 笔记与 Slogs 远程 Obsidian 库同步。

[Auto GitKeep](https://obsidian.md/plugins?id=auto-gitkeep) By _satosprod_

> 自动在库的每个文件夹中放置.gitkeep 文件，以便 Git 跟踪空目录。加载时扫描现有文件夹并监视新文件夹。

---

##### 可视化与视图

[Eve Apple Tree Thinking System](https://obsidian.md/plugins?id=eve-apple-tree) By _brandthebrand_

> 将你的笔记培育成一棵活的 3D 光之树——这是思考工具，而非文件柜。每个文件夹成为一棵树；笔记是按领域和时间放置的叶子；链接是根茎；花朵是顿悟时刻；苹果是产出成果。

![图片](https://raw.githubusercontent.com/brandthebrand/eve-apple-tree/master/img/hero.jpg)

[TimeLineX](https://obsidian.md/plugins?id=timelinex) By _siavashameli_

> 跨多个叠加时间线按时间顺序组织和可视化笔记，支持公历、波斯历（太阳回历）和伊斯兰历（回历）。

[Files Progress](https://obsidian.md/plugins?id=files-progress) By _sonna-io_

> 文件浏览器中的微型进度条，显示每个笔记相对于目标字符数的完成度。

[Chillight Graph](https://obsidian.md/plugins?id=chillight-graph) By _irolyuk_

> 将 Obsidian 图谱视图转换为带有发光节点和花彩连线的动画主题图谱。

![图片](https://raw.githubusercontent.com/irolyuk/chillight-graph/master/assets/theme-christmas-garland.png)

[Pinax](https://obsidian.md/plugins?id=pinax) By _nicknikolakakis, sphragis-oss_

> 在任何库之上构建配置驱动的仪表板：通过单个 profile.json 生成表格、看板、热力图和表单。

![图片](https://raw.githubusercontent.com/sphragis-oss/pinax/master/docs/demo.gif)

[Advanced Bases](https://obsidian.md/plugins?id=advanced-bases) By _brightwav3_

> Obsidian Bases 的 Notion 风格视图——紧凑卡片、信息流和时间线。仅包含核心视图的轻量构建。

[Metadata Visuals](https://obsidian.md/plugins?id=metadata-visuals) By _anthonyfitzpatrick_

> Obsidian 的元数据驱动可视化引擎。

[FlowKit Health Dashboard](https://obsidian.md/plugins?id=flowkit-health-dashboard) By _saiken_

> 从质量、维护、性能、流行度和兼容性方面对每个已安装插件进行评分。

[hledger Dashboard](https://obsidian.md/plugins?id=hledger-dashboard) By _cousine_

> hledger 日记账的完整财务仪表板

[Simple Plotlines](https://obsidian.md/plugins?id=simple-plotlines) By _null-machine_

> 通过为场景笔记标记其推进的情节点，跨幕组织故事情节。

![图片](https://raw.githubusercontent.com/null-machine/simple-plotlines/master/screenshots/plotlines.png)

[Songwriter Player](https://obsidian.md/plugins?id=songwriter-player) By _mrrepac_

> 用于歌曲创作的高级侧边栏音频播放器：波形、工作标记、A-B 循环区域、播放计数和热键。播放不受笔记滚动和关闭面板影响。

[Gene Code](https://obsidian.md/plugins?id=gene-code) By _neznayer_

> 在 Obsidian 笔记中渲染基因代码棒棒糖图和系谱图。

[Stonks](https://obsidian.md/plugins?id=stonks) By _dmgx0_

> 输入股票代码时内联显示实时股票、ETF 和加密货币价格。对报价进行简单计算，直接在笔记中追踪个人投资组合。从雅虎财经获取数据，支持移动端。

![图片](https://raw.githubusercontent.com/dmgx0/obsidian-stonks/master/docs/demo.gif)

[STEP Viewer](https://obsidian.md/plugins?id=step-viewer) By _ondreu_

> 在交互式 3D 查看器中打开和查看 STEP(.step/.stp) 以及 STL、OBJ、CAD、FCStd 模型。

![图片](https://raw.githubusercontent.com/ondreu/STEP-viewer/master/assets/1.png)

[Habits](https://obsidian.md/plugins?id=habits) By _jamescliffordspratt_

> 带连续天数、图表和统计的习惯追踪器。从轮播仪表板或侧边栏面板记录每日习惯，暂停习惯而不丢失连续天数，并导出可打印 PDF 报告。

![图片](https://raw.githubusercontent.com/jamescliffordspratt/obsidian-habits/master/images/habits-renderer.gif)

[Sketch Mechanisms](https://obsidian.md/plugins?id=sketch-mechanisms) By _masoudmim_

> 从简单代码块生成 2D 机构（四连杆、滑块曲柄、齿轮、凸轮、摆锤、弹簧）的实时手绘动画。

[Math Plotter](https://obsidian.md/plugins?id=math-plotter) By _sharbelmarshi_

> 从图形界面创建数学图表。通过表单插入图表，无需编写绘图代码。

[Maps Timeline](https://obsidian.md/plugins?id=maps-timeline) By _jagajaga_

> 在交互式地图上查看 Google 地图时间线位置历史——访问、路线和精确 GPS 轨迹，支持日期和日期范围选择器。

[Graph Type to Search](https://obsidian.md/plugins?id=graph-type-to-search) By _junghyunbak_

> 图谱视图中的预输入搜索：图谱聚焦时开始输入以过滤，并在标题匹配的节点周围绘制高亮环。可选地保持所有节点可见，仅对匹配项画环。

[Graph Save](https://obsidian.md/plugins?id=graph-save) By _manitofigh_

> 自动保存和恢复图谱节点位置。

[Pin Board](https://obsidian.md/plugins?id=pin-board) By _rayvven_

> 文件夹中图片和视频的 Pinterest 风格垂直滚动板。指向一个文件夹，滚动浏览，并可选地为任何图钉附加笔记。

[Markdown Mindmap](https://obsidian.md/plugins?id=markdown-mindmap) By _kikocastro_

> 从笔记前言链接渲染可配置的思维导图/层级树。在 ```mindmap 代码块中定义每个导图。

[File Media Gallery](https://obsidian.md/plugins?id=file-media-gallery) By _jagajaga_

> 右键单击笔记以图库形式查看其所有媒体（图片、视频、音频、PDF），支持按类型分类标签页和全屏灯箱。

[STP Viewer](https://obsidian.md/plugins?id=stp-viewer) By _ove_

> 3D STEP 文件预览器——基于 OpenCascade WASM + Three.js。直接在 Obsidian 中旋转、缩放和检查 CAD 模型。

---

##### 导航与搜索

[CFR Find](https://obsidian.md/plugins?id=cfr-find) By _cferrugem_

> 使用快速的工作线程驱动索引搜索库。容错模糊匹配、文件内搜索，以及可选的 PDF、图片和 Office 文档索引。灵感来自 Omnisearch。

[SideCard](https://obsidian.md/plugins?id=sidecard) By _shuuul_

> 用于交叉引用 Markdown 笔记、PDF 和图片的侧边栏卡片库。

[MCP Notes Tools](https://obsidian.md/plugins?id=mcp-notes-tools) By _msnp1381_

> 暴露本地 MCP 工具，用于在项目库中搜索、读取和追加已确认的变更笔记。

[Community Helper](https://obsidian.md/plugins?id=plugin-helper) By _zqdejob_

> 在侧边栏中浏览已安装的社区插件，包含官方描述、中文注释和可编辑的个人笔记。

[Subtle TOC](https://obsidian.md/plugins?id=subtle-toc) By _leandro_

> 边缘带有小地图的浮动式 Capacities 风格目录，支持活动标题追踪、点击滚动和文档统计。

[Vimium+](https://obsidian.md/plugins?id=vimium-plus) By _stianlyng_

> 使用 Vimium 风格键导航：f 显示点击提示，j/k/d/u 滚动，J/K 切换标签，i 进入编辑器原生 Vim 模式。

[Note Nav Cards](https://obsidian.md/plugins?id=note-nav-cards) By _davidtorro_

> 用于链接到上一篇和下一篇笔记的导航组件。

[Single Click Focusing](https://obsidian.md/plugins?id=single-click-focusing) By _thisiselijah_

> 允许在文件浏览器中通过单击左键聚焦文件和文件夹。

![图片](https://api.star-history.com/svg?repos=thisiselijah/obsidian-single-click-focusing-plugin&type=Date)

[Table of Content](https://obsidian.md/plugins?id=table-of-content) By _secum3r_

> 在笔记顶部插入可点击的目录，可配置最大标题深度。

[Glossary Linker](https://obsidian.md/plugins?id=glossary-linker) By _max-fluff_

> 高亮任何词形的术语表术语，将它们转换为链接，并从你已创建的链接中学习别名。

[HY Canvas Minimap](https://obsidian.md/plugins?id=hy-canvas-minimap) By _lugglory_

> 为白板添加小地图

[Copy Note Wikilink](https://obsidian.md/plugins?id=copy-note-wikilink) By _sharfaroz_

> 将选中的笔记或搜索结果复制为 wiki 链接。

[Empty Tab](https://obsidian.md/plugins?id=empty-tab) By _waldemar-one_

> 添加命令将当前标签页替换为空白页面，与打开新标签页时显示的画面相同。

[MD Reader](https://obsidian.md/plugins?id=md-reader) By _mrrepac_

> 像电子书一样阅读笔记：渲染的 Markdown 以页面形式布局，你可以通过滑动、点击或方向键横向翻页，支持单页或双页跨页，在桌面端和移动端均可使用。

---

##### 数据与属性

[YAML Databases](https://obsidian.md/plugins?id=yaml-databases) By _ondreu_

> YAML 数据库将 YAML 文件转换为交互式 Obsidian 数据库——支持电子表格/表单/原始格式编辑，包含子表、查找/替换、代码检查和导出（CSV/XLSX/YAML/HTML）。

[Knowledge Forge](https://obsidian.md/plugins?id=kg-forge) By _jimmycarroll2021_

> 从你的库构建带三元组、溯源、GraphRAG 提示和能力问题的类型化知识图谱。

[Bases Toolbox](https://obsidian.md/plugins?id=bases-toolbox) By _grub-basket_

> Bases 和属性的实用工具：跨库查找和替换属性值，防止数字属性在方向键上更改，以及每个属性的可搜索索引。

[Bonds](https://obsidian.md/plugins?id=bonds) By _zakiruz_

> 链接作为一等公民笔记。原子之间的键携带自己的内容，在两端渲染。

[Property Streak](https://obsidian.md/plugins?id=property-streak) By _git-hub-dangel_

> 从每日笔记前言创建和维持类多邻国的习惯连续天数，带小部件、颜色和可自定义的连续类型。

[MultiDim Virtual Folders](https://obsidian.md/plugins?id=multidim-virtual-folders) By _arislan-x_

> 从前言创建多维虚拟文件夹，无需移动真实文件。

[Mark as Read](https://obsidian.md/plugins?id=explorer-property-attributes) By _hemy301_

> 一键标记笔记为已读或完成，并在文件浏览器中查看：完成的笔记会变灰并带有对勾。任何前言属性都可以通过 CSS 片段设置文件样式，即时更新。

![图片](https://raw.githubusercontent.com/hemy301/explorer-property-attributes/master/demo.gif)

[Uncertainty Calculator](https://obsidian.md/plugins?id=uncertainty-calc) By _masoudmim_

> 传播测量不确定度的电子表格风格计算器：输入表单、有效数字、扩展不确定度、不确定度预算和蒙特卡洛方法，遵循 GUM 及其补充 1。

---

##### 导入与导出

[mergdowntotex](https://obsidian.md/plugins?id=mergdowntotex) By _dvrch_

> 合并并导出所有内容——嵌入内容、Zotero/Pandoc 引用、Mermaid、公式、交叉引用——到单个.tex 文件。编译为 PDF、DOCX 或 InDesign。WASM 引擎，零构建步骤。

[VaultPack](https://obsidian.md/plugins?id=vaultpack) By _akisantin_

> 将选定笔记和 Bases 视图导出为自包含的离线网站——可作为文件夹、加密 ZIP 或密码保护的网络包分享。

![图片](https://raw.githubusercontent.com/akisantin/VaultPack/master/_files/VaultPack_01.png)

[Vuln Report Kit](https://obsidian.md/plugins?id=vuln-report-kit) By _aleff-github_

> Obsidian 内用于漏洞案例、报告、模板、机密审查、清理、仪表板和导出的本地优先工具包。

[ToWrite Open Questions](https://obsidian.md/plugins?id=towrite-open-questions) By _gitmorric_

> 在源笔记旁边追踪待思考和待写作注释。

![图片](https://raw.githubusercontent.com/gitmorric/towrite-open-questions/master/docs/assets/sidebar-current-note%20and%20selection-toolbar.png)

[Code File Embed](https://obsidian.md/plugins?id=codefile) By _williansaez_

> 通过 codefile 围栏块将库文件的内容作为语法高亮代码块嵌入。

[Smart RED](https://obsidian.md/plugins?id=smart-red) By _viy1204_

> 将 Obsidian 笔记转换为小红书风格图片

[MinerU Parser](https://obsidian.md/plugins?id=mineru-parser) By _luffysolution-svg_

> 右键单击文档，使用 MinerU 或 markitdown 将其解析为 Markdown，将笔记和图片附件保存到自定义文件夹。

[SourceDown](https://obsidian.md/plugins?id=sourcedown) By _0libote_

> 使用 Microsoft MarkItDown 将文档、媒体、存档和网页导入为 Markdown。

[Read It Never](https://obsidian.md/plugins?id=read-it-never) By _leweii_

> 将在线内容保存到你的库，利用嵌入式模板引擎并根据需要组织阅读列表。用 Read It Never 保存网络内容。

[Style HTML Viewer](https://obsidian.md/plugins?id=style-html-viewer) By _taihoe_

> 在 Obsidian 工作区标签页中原生渲染 HTML 文档，支持本地 CSS、图片和脚本资源解析、CSP 安全和链接拦截。

[Stashpad Classic](https://obsidian.md/plugins?id=stashpad-classic) By _grub-basket_

> 聊天风格的嵌套笔记工作区：快速捕获、大纲导航、快速搜索、任务和按文件夹模板，支持导出笔记而非使用系统资源管理器。

[Ishibashi Web Clipper](https://obsidian.md/plugins?id=ishibashi-web-clipper) By _ishibashi-c_

> 将共享网页链接捕获为 Markdown 笔记，包含公共元数据、重复检查、标签和剪辑历史。

[Secret Notes](https://obsidian.md/plugins?id=secret-notes) By _kasukabe-tsumugi_

> 加密和预览可编辑的密码代码块。

---

##### 媒体与附件

[Loft](https://obsidian.md/plugins?id=loft) By _san, opellen_

> 将图片上传到 Google Drive，并用链接替换本地嵌入。

[VideoControlsEnhancer](https://obsidian.md/plugins?id=video-controls-enhancer) By _postpollux_

> 增强本地视频的 HTML5 视频播放器控件——水平拖动进度、垂直音量调节、可配置双击、长按快进等！注意：不会影响 YouTube 播放器等嵌入播放器。

![图片](https://img.youtube.com/vi/ni9dPoO59nE/maxresdefault.jpg)

[Speak Out](https://obsidian.md/plugins?id=speakout) By _landyking_

> 为 Markdown 源中标记的内容添加阅读视图文本转语音控件。

![图片](https://raw.githubusercontent.com/landyking/speak-out-plugin-for-obsidian/master/images/source_and_reading.png)

[Rin Image Toolbar](https://obsidian.md/plugins?id=image-toolbar) By _witheredad_

> 悬停图片显示工具栏：复制、裁剪和全屏

![图片](https://raw.githubusercontent.com/witheredad/Rin-s-Image-Toolbar/master/demo.png)

[Best Downloader](https://obsidian.md/plugins?id=best-downloader) By _trikorka_

> 使用 yt-dlp 将各种格式的视频和音频直接下载到库。仅 Windows

[DXF Viewer and Editor](https://obsidian.md/plugins?id=dxf-viewer-editor) By _ondreu_

> 简单轻量的 DXF 查看器和编辑器，能够测量长度、面积、直径、角度等。也支持简单编辑，如直线、多段线、矩形、圆、椭圆、圆弧、填充、图案填充...

---

##### 第三方集成

[Gmail Mailbox](https://obsidian.md/plugins?id=gmail-mailbox) By _nabheetcloud_

> 将 Gmail 同步到库中，每封邮件一个笔记，加上每个标签的线程索引。增量历史同步、PKCE 认证、可配置标签和 Google 日历即将召开会议侧边栏。

[WhatsApp Local Sync](https://obsidian.md/plugins?id=whatsapp-local-sync) By _nabheetcloud_

> 读取本地 WhatsApp 桌面消息数据库，将聊天镜像到库中，每个对话一个转录笔记。只读、增量、完全本地——无网络、无云、无 API 密钥。

[Outlook Teams and Calendar](https://obsidian.md/plugins?id=outlook-teams-calendar) By _nabheetcloud_

> 将 Microsoft 365 同步到库：Outlook 邮件（每封邮件一个笔记 + 线程索引）、日历事件和 Teams 消息（聊天和频道）。增量同步、PKCE 认证、只读权限范围。

[LeetLog Bridge](https://obsidian.md/plugins?id=leetlog-bridge) By _yzyhhhstudy_

> 接收来自 LeetLog 浏览器扩展的事件，并自动将 LeetCode 练习笔记（计时、提交、通过代码）写入库。
![图片](https://raw.githubusercontent.com/yzyhhhstudy/leetlog/master/docs/demo.svg)

[LibreTranslate](https://obsidian.md/plugins?id=libretranslate) By _p0shkar_

> 使用 LibreTranslate 翻译文本。
![图片](https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png)

[JW Relink](https://obsidian.md/plugins?id=jw-relink) By _floydv149_

> 将 JW.ORG 的链接转换为 JW Library 兼容链接。

[Config Drift Watcher](https://obsidian.md/plugins?id=config-drift-watcher) By _rixct_

> 检测服务器实际配置何时与你在笔记中记录的内容发生偏差。通过 SFTP 只读访问。

[Vestaboardian](https://obsidian.md/plugins?id=vestaboardian) By _patrick-knight_

> 在笔记中撰写消息并发送到你的 Vestaboard 显示屏。

[Space Launches](https://obsidian.md/plugins?id=space-launches) By _elmoneedsarson_

> 在 Obsidian 中追踪即将到来的火箭发射和太空事件。

[One File](https://obsidian.md/plugins?id=one-file) By _rcanand_

> 通过符号链接从 Obsidian 库内编辑机器上的任何 Markdown 文件，提供无干扰专注模式。

---

##### 外观与主题

[Nicons](https://obsidian.md/plugins?id=nicons) By _pilafdob_

> 使用捆绑的 Phosphor 图标资源自定义文件和文件夹图标。

[Folder Limit](https://obsidian.md/plugins?id=folder-limit) By _naggischnulu_

> 限制文件夹中可见文件的数量，并提供显示更多按钮。

[Better Icons](https://obsidian.md/plugins?id=iconic-custom) By _christianlempa_

> 更好的图标自定义，支持 Simple Icons 和 Devicon。
![图片](https://raw.githubusercontent.com/christianlempa/obsidian-iconic/master/banner.webp)

[Sidebar Resource Saver](https://obsidian.md/plugins?id=sidebar-resource-saver) By _kjh-portfolio, kjh-portfolio2_

> 自动挂起折叠侧边栏中未使用的 webview 和 iframe，大幅节省 RAM 和 CPU 使用。

---

##### 效率工具

[Daily Five](https://obsidian.md/plugins?id=daily-five) By _0libote_

> 每日五字母单词游戏，带有每日笔记结果和终身统计。

[Bamboo Walking](https://obsidian.md/plugins?id=bamboo-walking) By _miaoziguan_

> 个人写作专栏阅读器——竹杖芒鞋轻胜马，谁怕？一蓑烟雨任平生。

[Russian Rhymes](https://obsidian.md/plugins?id=russian-rhymes) By _mrrepac_

> 离线俄语押韵词典：所选单词的押韵、重音标记和同义词。按两次 Ctrl+C 查找单词。

[nameForge](https://obsidian.md/plugins?id=nameforge) By _volcanicmole_

> 给它一个名字列表，通过马尔可夫魔法找出它们的规律，然后生成不断变化的新名字，随时可用（请合法使用）。

[Daily Notes Compiler](https://obsidian.md/plugins?id=daily-notes-compiler) By _pragatinath_

> 展示 Obsidian API 的部分功能。

---

##### 学术与研究

[Canvas Template Manager](https://obsidian.md/plugins?id=canvas-template-manager) By _phillip383_

> 支持轻松复制模板。

![图片](https://raw.githubusercontent.com/phillip383/obsidian-canvas-template-manager/master/docs/imgs/Screenshot_2026-07-07_09-23-34.png)

[CodeRecall](https://obsidian.md/plugins?id=coderecall) By _rixct_

> Obsidian 中的 Anki+LeetCode：代码中的填空删除，带自动评分主动回忆和间隔重复。

[ISBN Bulk Import Bookshelf Builder](https://obsidian.md/plugins?id=isbn-bulk-import-bookshelf-builder) By _flex-moto_

> 从 ISBN 管理你的书架。从 NDL、Google Books 和 Open Library 获取图书元数据，然后创建和组织图书笔记。

[Gamebase](https://obsidian.md/plugins?id=gamebase) By _andypandy1189_

> 轻松搜索和提取丰富的电子游戏元数据，使用你自己的自定义 Markdown 模板在库中自动生成格式精美的笔记

---

##### 写作与笔记

[QMD Preview](https://obsidian.md/plugins?id=qmd-preview) By _elliotxx_

> 在 Obsidian 中编辑 QMD 文件，并在侧边栏实时预览。

[Spartito](https://obsidian.md/plugins?id=spartito) By _riccardosilvestri_

> 在大谱表（高音和低音）上编写和渲染乐谱。

[MDX Preview](https://obsidian.md/plugins?id=mdx-preview) By _jovialio_

> 在 Obsidian 中预览 MDX，支持 Code Hike。

---

##### 日历与日期

[MD Calendar](https://obsidian.md/plugins?id=md-calendar) By _mrrepac_

> 单个 Markdown 笔记中的完整日历：月/周/日/议程视图，支持事件、任务、重复、颜色、拖拽重新安排和键盘控制，全部存储在一个代码块中。

---

##### 代码与开发

[CM Code Editor](https://obsidian.md/plugins?id=cm-code-editor) By _gapmiss_

> 带语法高亮和代码折叠的代码文件编辑器。

---

##### 白板与绘图

[Mouse Handwriting](https://obsidian.md/plugins?id=mouse-handwriting-practice) By _khr0907_

> 用鼠标练习手写。在全页白板上描摹字母、单词和著名段落（韩语/英语/日语），带文本或格线引导。

[Excalidraw Stylus Menu](https://obsidian.md/plugins?id=excalidraw-stylus-menu) By _delfinchiknakite-netizen_

> Excalidraw 的触控笔/S Pen 手势：通过点击或侧键打开插入菜单，点击对象进行快速操作，以及复制、粘贴或连接形状。

### PKMer 出品

> [!INFO]
> **PKMer**（[PKMer.cn](https://pkmer.cn/)、[PKMer.net](https://pkmer.net/)）旨在打造东半球强大的知识管理社区。Personal Knowledge Management (PKM) + "er"，其中 "er" 表示人，专注、喜爱个人知识管理工作、追求效率的人们，都可以划入这个行列，希望社区凝聚更多这样的人。

#### Editing Toolbar 更新至 [v4.0.9](https://github.com/PKM-er/obsidian-editing-toolbar/releases#release-4.0.9)

- 背景色不生效修复
- 支持自定义 frontmatter 提示词
- 增加俄语翻译

> [!Warning] 声明
> 本栏目致力于为广大 Obsidian 中文用户汇总全面的官方资讯与插件、外观动态。为了保持信息的全面性，我们的**收录并不等同于推荐**，还请各位用户知悉并理解，根据自身需求进行判断和选择。
