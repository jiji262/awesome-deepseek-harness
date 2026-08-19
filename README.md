# Awesome DeepSeek Harness

中文 | [English](README_EN.md)

> 精选 DeepSeek Harness (DSH) 相关的开源项目、插件、桌面客户端、插件市场与教程。

[DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness)（`dsh`）是 DeepSeek 于 2026 年 8 月 13 日开源的 Agent Harness，核心理念是 **"Everything is a Plugin"（万物皆插件）**，基于 [Cordis](https://github.com/cordiverse/cordis) 插件架构，MIT 协议。发布不到一周 star 突破 16 万，GitHub 上 `dsh-plugin` topic 下已有 7800+ 个生态仓库。

一行命令启动 Web UI（默认 `http://127.0.0.1:3080`）：

```sh
npx @deepseek-ai/dsh web
```

## 目录

- [官方资源](#官方资源)
- [插件市场与插件发现](#插件市场与插件发现)
- [桌面客户端](#桌面客户端)
- [终端 TUI](#终端-tui)
- [Web UI 增强与皮肤](#web-ui-增强与皮肤)
- [功能扩展插件](#功能扩展插件)
- [Agent Skills](#agent-skills)
- [记忆与上下文](#记忆与上下文)
- [相关 Harness 与 Agent 运行时](#相关-harness-与-agent-运行时)
- [集成与周边工具](#集成与周边工具)
- [教程与学习资源](#教程与学习资源)
- [其他 Awesome 列表](#其他-awesome-列表)
- [友情链接](#友情链接)
- [贡献](#贡献)

## 官方资源

- [deepseek-ai/deepseek-harness](https://github.com/deepseek-ai/deepseek-harness) ⭐ 164k - 官方仓库。目前处于 developer preview 阶段，迭代很快，存在破坏性变更。
- [官方主页](https://deepseek.com/harness) - deepseek.com/harness。
- [官方中文 README](https://github.com/deepseek-ai/deepseek-harness/blob/master/README.zh.md) / [docs 文档目录](https://github.com/deepseek-ai/deepseek-harness/tree/master/docs) - 架构、Agent 生命周期、API Gateway 等中英双语文档。
- [Cordis](https://github.com/cordiverse/cordis) ⭐ 6.3k - DSH 底层的插件化框架，"万物皆插件"的技术基座。
- [dsh-plugin topic](https://github.com/topics/dsh-plugin) - 官方推荐的插件发现入口：给插件仓库打上 `dsh-plugin` topic 即可被发现，目前已有 7800+ 仓库。
- [GitHub Discussions](https://github.com/deepseek-ai/deepseek-harness/discussions) - 官方反馈与讨论区。
- [Discord 社区](https://discord.gg/Ycq5dCaS4) - 官方 Discord。

## 插件市场与插件发现

- [awesome-dsh-plugin/awesome-dsh-plugin](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin) ⭐ 9.7k - DSH 插件精选列表（中英双语），目前社区最大的插件清单。
- [AdamPlatin123/awesome-dsh-plugins](https://github.com/AdamPlatin123/awesome-dsh-plugins) ⭐ 1.2k - 插件雷达与精选榜：自动发现 7600+ 候选，容器内真实安装实测（883/1415 可用），Top 50 人工策展。
- [dsh-market/dsh-market](https://github.com/dsh-market/dsh-market) ⭐ 1.2k - DSH 内置可视化插件市场：浏览、搜索、一键安装。
- [Anil-matcha/awesome-dsh-plugin](https://github.com/Anil-matcha/awesome-dsh-plugin) ⭐ 946 - DSH 插件生态精选列表。
- [bruc3van/awesome-dsh-plugin](https://github.com/bruc3van/awesome-dsh-plugin) ⭐ 242 - 每日脚本抓取 + 人工逐个核实：真插件进目录、蹭热度进黑名单，剔除理由公开可查。
- [hikariming/dshfind](https://github.com/hikariming/dshfind) ⭐ 176 - DSH 原理学习、插件市场与最佳实践。
- [Nagi-ovo/dsh-find-plugins](https://github.com/Nagi-ovo/dsh-find-plugins) ⭐ 151 - 帮 DSH 搜索、安装并验证 GitHub 插件的 Skill。
- [OBdangshang07/DSH_Creative_Workshop](https://github.com/OBdangshang07/DSH_Creative_Workshop) ⭐ 60 - Steam 创意工坊式的插件发现、信任评估、图搜索、合集与事务化安装规划。

## 桌面客户端

- [anywhere-labs/deepseek-harness-desktop](https://github.com/anywhere-labs/deepseek-harness-desktop) ⭐ 14.6k - 目前 star 最高的桌面端：为 DSH 插件生态打造，"桌面本身也是插件"。
- [zhukunpenglinyutong/desktop-cc-gui](https://github.com/zhukunpenglinyutong/desktop-cc-gui) ⭐ 4k - Tauri 多引擎 AI 编码桌面客户端：Claude Code、Codex、Gemini、OpenCode、DSH 统一 GUI。
- [edison7009/EchoBird](https://github.com/edison7009/EchoBird) ⭐ 3.1k - 一键安装与模型切换：Claude Code、Codex CLI、Grok Build、DSH、Kimi Code 等。
- [GCWing/BitFun](https://github.com/GCWing/BitFun) ⭐ 1.8k - Rust 编写的高性能 Agent 运行时 + 桌面应用。
- [dataelement/dsh-desktop](https://github.com/dataelement/dsh-desktop) ⭐ 1k - DeepSeek Harness Desktop。
- [zouyuxuan122/Deepseek-Harness-EAC](https://github.com/zouyuxuan122/Deepseek-Harness-EAC) ⭐ 905 - Windows / Linux 客户端，捆绑 Node.js 与 dsh CLI，内置 10 套 UI 皮肤。
- [hairyf/deepseek-harness-desktop](https://github.com/hairyf/deepseek-harness-desktop) ⭐ 585 - Tauri 桌面版，安装包仅 5MB，零环境配置、预置插件，全平台。
- [vibeinging/deepseek-harness-desktop-app](https://github.com/vibeinging/deepseek-harness-desktop-app) ⭐ 487 - 本地 AI 桌面工作空间：DSH 会话、项目、文件、网页调研、插件与 Office 产物。
- [myYangyunfan/dsh_desktop](https://github.com/myYangyunfan/dsh_desktop) ⭐ 475 - Windows 桌面客户端，捆绑 Node.js 与 dsh CLI，一键启动。
- [fufankeji/deepseek-harness-studio](https://github.com/fufankeji/deepseek-harness-studio) ⭐ 322 - 零代码桌面端：内置插件发现、热点推送、一键安装管理与 AI 推荐。
- [turtle2209/Bigfish](https://github.com/turtle2209/Bigfish) ⭐ 276 - 第三方桌面端，内置 Node 运行时，双击即用，附带桌面萌宠。
- [hust-open-atom-club/oh-dsh](https://github.com/hust-open-atom-club/oh-dsh) ⭐ 255 - 一套 DSH runtime，Desktop、Web 与 TUI 三种开发体验。
- [lencx/Minke](https://github.com/lencx/Minke) ⭐ 225 - 🐳 DeepSeek Harness Desktop。
- [op7418/pilot-harness](https://github.com/op7418/pilot-harness) ⭐ 211 - CodePilot 风格的桌面客户端与插件套件，支持 macOS / Windows / Linux。
- [shaobeichen/dsh-pocket](https://github.com/shaobeichen/dsh-pocket) ⭐ 202 - 把 DSH 装进口袋：电脑跑 dsh web，手机扫码同步访问（局域网 + 公网实时同屏）。
- [steven-kid/deepseek-harness-desktop](https://github.com/steven-kid/deepseek-harness-desktop) ⭐ 155 - 极简桌面封装，跨平台、免配置、开箱即用。
- [Ruler4396/dsh-launcher](https://github.com/Ruler4396/dsh-launcher) ⭐ 150 - Windows 轻量启动器：开机静默自启 + WebView2 极简窗口。

## 终端 TUI

- [ccch1mneyyy/dsh-TUI](https://github.com/ccch1mneyyy/dsh-TUI) ⭐ 2k - DSH 官方公众号收录的 TUI 补位插件：Claude Code 风格，鲸鱼顶栏、实时状态、流式思考、双击 Esc 回滚、上下文进度 + TPS，npm 一键安装。
- [huiliyi37/dsh-tianshu-tui](https://github.com/huiliyi37/dsh-tianshu-tui) ⭐ 217 - 自研 ANSI 极简渲染核心：流式 Markdown/工具卡、多会话 tab、16+ 主题、slash 命令与选择器。

## Web UI 增强与皮肤

- [zhu1090093659/dsh-web-ui](https://github.com/zhu1090093659/dsh-web-ui) ⭐ 4.8k - 插件与皮肤合集：任务板、Git graph、右侧面板、移动端远程 UI、桌宠、实时 token 统计、皮肤中心。
- [chuspeeism/dashi-taskboard](https://github.com/chuspeeism/dashi-taskboard) ⭐ 2.3k - DSH 任务看板插件。
- [omdsh-dev/DSH-better-sidebar](https://github.com/omdsh-dev/DSH-better-sidebar) ⭐ 2.3k - 开放的侧边栏底座，支持三方扩展注册新页面，内置文件渲染编辑 / 终端 / Git / 子代理。
- [Small-tailqwq/dsh-deep-whale](https://github.com/Small-tailqwq/dsh-deep-whale) ⭐ 1.4k - "深海女仆工坊"鲸鱼娘皮肤系列。
- [Nagi-ovo/dsh-ads](https://github.com/Nagi-ovo/dsh-ads) ⭐ 508 - 整活插件：把 DSH 变成 2005 年门户网站——侧栏广告、假游戏与弹窗（素材全虚构）。
- [bowenliang123/dsh-context](https://github.com/bowenliang123/dsh-context) ⭐ 425 - 上下文洞察与管理：上下文面板 / 浏览器 + context 命令，看清上下文窗口的组成与演变。
- [omdsh-dev/dsh-at-file](https://github.com/omdsh-dev/dsh-at-file) ⭐ 403 - Codex 风格 `@file` 引用：在输入框搜索工作区文件并附加到提示词。
- [WYH66666666/DSH-Transparent-UI-Plugin](https://github.com/WYH66666666/DSH-Transparent-UI-Plugin) ⭐ 315 - 高自由度玻璃质感主题：顶栏、侧边栏、输入框全变磨砂玻璃，模糊度与壁纸可调。
- [vlln/whale-girl](https://github.com/vlln/whale-girl) ⭐ 243 - QQ 宠物形态的桌面宠物插件：右下角悬浮，可拖拽、投喂、玩耍。
- [omdsh-dev/dsh-genui](https://github.com/omdsh-dev/dsh-genui) ⭐ 237 - GenUI：回复内直接渲染布局、图表、表单、测验等交互组件。
- [PC2005-cloud/dsh-pet](https://github.com/PC2005-cloud/dsh-pet) ⭐ 187 - 桌面宠物：一行命令装 28 个透明动画宠物，或用 AI 视频自造专属宠物。
- [Nagi-ovo/dsh-visualize](https://github.com/Nagi-ovo/dsh-visualize) ⭐ 182 - 在 DSH 对话中生成交互式可视化卡片。
- [d-dev0101/open-sea-skin](https://github.com/d-dev0101/open-sea-skin) ⭐ 179 - WebGPU 海洋皮肤，提供插件、浏览器扩展与静态安装器多种形态。
- [Js2Hou/dsh-mcp-manager](https://github.com/Js2Hou/dsh-mcp-manager) ⭐ 8 - MCP 可视化管理插件：设置 → MCP 页查看/新增/删除/启停 MCP 服务器，实时显示连接状态与工具数。

## 功能扩展插件

- [xiaobright/dsh-anchored-standard](https://github.com/xiaobright/dsh-anchored-standard) ⭐ 3.6k - 两阶段 DSH preset：极简对齐引导后加载完整 Standard 工具。
- [liustack/modlens](https://github.com/liustack/modlens) ⭐ 3.2k - 首个 DSH 视觉插件：粘贴图片，输出结构化 JSON 证据（OCR、布局、语义），也是纯文本 Agent 的通用视觉桥。
- [ysr666/dsh-vision-router](https://github.com/ysr666/dsh-vision-router) ⭐ 806 - 给纯文本 DSH Agent 装上眼睛：内置免 key 视觉链 + 像素级视觉工具。
- [Anionex/dsh-vision-toolkit](https://github.com/Anionex/dsh-vision-toolkit) ⭐ 736 - 更强的视觉工具箱：免费使用、粘贴图片直接识别、多图问答、截图还原前端 UI。
- [NanmiCoder/dsh-agent-teams](https://github.com/NanmiCoder/dsh-agent-teams) ⭐ 593 - AgentTeams 多智能体协作插件。
- [yjh051108/dsh-router-standard](https://github.com/yjh051108/dsh-router-standard) ⭐ 345 - 任务感知的推理模式路由：spec / mixed / react 三档实测行为带与阶段转换。
- [Lum1104/dsh-browser](https://github.com/Lum1104/dsh-browser) ⭐ 311 - Chrome 侧边栏扩展，让 DSH 无需视觉能力直接操作你的浏览器。
- [liustack/modsearch](https://github.com/liustack/modsearch) ⭐ 164 - Web 搜索插件：问 Web 或 X，返回结构化 JSON 证据。
- [Anionex/dsh-turn-rewind](https://github.com/Anionex/dsh-turn-rewind) ⭐ 86 - 对话与代码状态回退，基于持久化 Change Ledger。
- [omdsh-dev/dsh_workflow](https://github.com/omdsh-dev/dsh_workflow) ⭐ 85 - 把一次性多 Agent 调度升级为可生成、可保存、可治理、可恢复的 Workflow 层。
- [Nwflower/dsh-chat-import](https://github.com/Nwflower/dsh-chat-import) ⭐ 71 - 13 种编码 Agent（Claude Code / Codex / Cursor / Gemini / OpenClaw 等）的历史会话全保真导入为可续聊 DSH 会话，并支持反向导出同步回 Claude Code。
- [slywalker2006/dsh-passwords](https://github.com/slywalker2006/dsh-passwords) ⭐ 12 - dsh 登录网关（密码门）：多用户账号、bcrypt 加密、防爆破锁定、审计日志、自动 HTTPS。

## Agent Skills

> 可在 DSH 及多家 Agent 上通用的技能包，均已接入 `dsh-plugin` 生态。

- [titanwings/colleague-skill](https://github.com/titanwings/colleague-skill) ⭐ 23.5k - 现象级"数字生命"Skill：把告别做成温暖的技能包。
- [tt-a1i/archify](https://github.com/tt-a1i/archify) ⭐ 14.4k - 架构图、流程图、时序图、数据流与生命周期图生成 Skill：自包含 HTML、可校验。
- [foryourhealth111-pixel/Vibe-Skills](https://github.com/foryourhealth111-pixel/Vibe-Skills) ⭐ 2.9k - 通用技能路由：自动调度本地 Skills 并智能编排 harness 工作。
- [hyhmrright/brooks-lint](https://github.com/hyhmrright/brooks-lint) ⭐ 1.4k - 基于 12 本经典软件工程书籍的 AI 代码审查：衰减风险诊断、书目引用、严重度标注。
- [Tencent/BrowserSkill](https://github.com/Tencent/BrowserSkill) ⭐ 1.2k - 腾讯开源：让 Agent 使用你已登录的真实浏览器，CLI + 扩展形态，不打断你的工作。
- [GanyuanRan/Aegis](https://github.com/GanyuanRan/Aegis) ⭐ 1.1k - 让编码 Agent 具备架构感知：基线优先、证据校验、漂移检查。
- [Jayden-X-L/forkprobe](https://github.com/Jayden-X-L/forkprobe) ⭐ 67 - 同一任务上对比多个 Skill 并选出最优。
- [dhicoc/dsh-reverse-skill](https://github.com/dhicoc/dsh-reverse-skill) ⭐ 40 - 把上游 [reverse-skill](https://github.com/zhaoxuya520/reverse-skill)（26.5k⭐）的 85 个 SKILL.md 封装成 Cordis 插件：逆向工程、授权渗透测试、CTF 与安全研究技能路由。仅限授权场景使用。

## 记忆与上下文

> DSH 发布后爆发的一类方向：给 Agent 装上跨会话的长期记忆。

- [volcengine/OpenViking](https://github.com/volcengine/OpenViking) ⭐ 29.8k - 火山引擎开源：Agent 自进化上下文数据库，统一记忆、知识 RAG 与技能。
- [EverMind-AI/EverOS](https://github.com/EverMind-AI/EverOS) ⭐ 12.2k - 跨 Agent 通用记忆层：本地优先、Markdown 原生、用户自持、可自进化。
- [MemTensor/MemOS](https://github.com/MemTensor/MemOS) ⭐ 10.8k - 面向 LLM 与 Agent 的自进化记忆 OS：超持久记忆、混合检索、跨任务技能复用。
- [adoresever/graph-memory](https://github.com/adoresever/graph-memory) ⭐ 554 - 知识图谱记忆插件，从对话中抽取结构化三元组。
- [mnemon-dev/mnemon](https://github.com/mnemon-dev/mnemon) ⭐ 484 - 图结构的 Agent 持久记忆，单二进制，支持 DSH。
- [csyangwen/dsh-memory-evolve](https://github.com/csyangwen/dsh-memory-evolve) ⭐ 188 - 纯插件实现跨会话长期记忆 + 后台自我进化：五轨记忆、技能自我进化、待办与调度。

## 相关 Harness 与 Agent 运行时

> 同期涌现的其他开源 harness / Agent 运行时，与 DSH 生态互相打通。

- [Hmbown/CodeWhale](https://github.com/Hmbown/CodeWhale) ⭐ 40.8k - 开源、社区驱动的 Agent harness。
- [esengine/DeepSeek-Reasonix](https://github.com/esengine/DeepSeek-Reasonix) ⭐ 34.8k - DeepSeek 原生终端编码 Agent，围绕前缀缓存稳定性做工程优化。
- [YaoApp/yao](https://github.com/YaoApp/yao) ⭐ 7.7k - 把所有 Agent 与工作空间收拢到一处，跨设备访问、看板式任务追踪。
- [Q00/ouroboros](https://github.com/Q00/ouroboros) ⭐ 5.6k - Agent OS：Agent 自我进化，评分命令与预期结果不进上下文。
- [xintaofei/codeg](https://github.com/xintaofei/codeg) ⭐ 2.8k - 多 Agent 协作编码工作台，聚合 Claude Code、Codex、OpenCode、Pi 等会话。
- [paean-ai/deeptide](https://github.com/paean-ai/deeptide) ⭐ 1.1k - Swift 原生的 macOS 编码 Agent，由 DeepSeek 打造。
- [huiliyi37/Tianshu-harness](https://github.com/huiliyi37/Tianshu-harness) ⭐ 244 - 天枢：基于 harness 工程的终端编程智能体运行时（TUI × GUI），针对 DeepSeek V4 做前缀缓存优化（长会话命中率 97–99%）。

## 集成与周边工具

- [nexu-io/open-design](https://github.com/nexu-io/open-design) ⭐ 89.2k - 开源 Claude Design 替代品，本地优先桌面应用，把编码 Agent 变成设计引擎，支持 DSH 在内的 20+ CLI。
- [CherryHQ/cherry-studio](https://github.com/CherryHQ/cherry-studio) ⭐ 50.8k - AI 生产力工作台，统一接入前沿大模型，已标注 `deepseek-harness` 支持。
- [Nagi-ovo/voyager](https://github.com/Nagi-ovo/voyager) ⭐ 19.7k - Gemini / AI Studio / Claude / ChatGPT 增强套件，含面向任意 Web UI 的提示词管理器，支持 DSH。
- [Devin-AXIS/iPolloWork](https://github.com/Devin-AXIS/iPolloWork) ⭐ 4.2k - AI 工作空间，集成 DSH 做子代理委派，融合双方插件生态。
- [crafter-station/petdex](https://github.com/crafter-station/petdex) ⭐ 3.9k - Codex、Claude Code、DSH 等 Agent 的动画宠物公共图鉴。
- [strukto-ai/mirage](https://github.com/strukto-ai/mirage) ⭐ 3.5k - AI Agent 统一虚拟文件系统。
- [whiteguo233/OpenBiliClaw](https://github.com/whiteguo233/OpenBiliClaw) ⭐ 2.9k - 本地私有的自进化内容发现 Agent（B 站 / 小红书 / YouTube 等），提供 [DSH 插件](https://github.com/whiteguo233/dsh-openbiliclaw)。
- [Javis603/token-monitor](https://github.com/Javis603/token-monitor) ⭐ 1.5k - 本地优先桌面挂件，追踪 30+ AI 编码工具的 token 用量、成本与额度。
- [xiufengsun/TokenTracker](https://github.com/xiufengsun/TokenTracker) ⭐ 1.4k - 本地优先的 token 用量与成本追踪，覆盖 31 种编码工具。
- [alvinunreal/openpets](https://github.com/alvinunreal/openpets) ⭐ 1.1k - 本地优先桌面伙伴平台：动画宠物 + 插件 SDK + 编码 Agent 集成。
- [tong-io/tongflow](https://github.com/tong-io/tongflow) ⭐ 867 - 多模态工作流工作室与引擎（画布 + Python 插件引擎），含 dsh-tongflow 插件。
- [yejiming/MuseAI](https://github.com/yejiming/MuseAI) ⭐ 589 - AI 角色扮演与故事世界，支持 DSH 插件接入。
- [PM-Shawn/Abu-Cowork](https://github.com/PM-Shawn/Abu-Cowork) ⭐ 337 - Claude Cowork 的开源替代：本地优先 AI Agent 桌面应用。
- [alaliqing/claude-paper](https://github.com/alaliqing/claude-paper) ⭐ 319 - 跨 Agent 论文研读工具包（Claude Code / Codex / OpenCode / DSH）。

## 教程与学习资源

- [walkinglabs/learn-harness-engineering](https://github.com/walkinglabs/learn-harness-engineering) ⭐ 12.3k - Harness 工程从 0 到 1 的入门教程，目前最受欢迎的 harness 教学项目。
- [alchaincyf/deepseek-harness-orange-book](https://github.com/alchaincyf/deepseek-harness-orange-book) ⭐ 1.1k - 橙皮书《从开机到拆开》：完整系统提示词、129 行启动清单、三份原始会话日志，PDF/EPUB/HTML 免费下载。
- [Electricitysheep/dsh-handbook](https://github.com/Electricitysheep/dsh-handbook) ⭐ 522 - 从 0 到 1 深度手册：安装、插件开发、性能调优、实测案例、同模型多 Agent 对比（中英 PDF）。
- [ht426/deepseek-harness-tutorial](https://github.com/ht426/deepseek-harness-tutorial) ⭐ 178 - DeepSeek Harness 中文详细学习教程。
- [adongwanai/learn-workbuddy](https://github.com/adongwanai/learn-workbuddy) ⭐ 183 - 从 0 复刻桌面 AI 助手 Harness：24 章 Python 教程，覆盖 Agent Loop、工具调用、记忆系统、沙盒审计。
- [pingfanfan/hello-dsh](https://github.com/pingfanfan/hello-dsh) ⭐ 77 - 零基础看懂"万物皆插件"：插件开发入门教程，含 22 个中文技能实例。
- [yanhua1010/dsh-harness-tutorial](https://github.com/yanhua1010/dsh-harness-tutorial) ⭐ 52 - DSH 原理与实现：从零到一实现一个 AI Agent（VitePress 站点 + 8 个 Demo + mini-harness）。
- [yu-xin-c/agent-unpacked](https://github.com/yu-xin-c/agent-unpacked) ⭐ 18 - Agent 源码拆解教程：DSH、PI Agent 与 nanobot。
- [NanmiCoder/learn-deepseek-harness](https://github.com/NanmiCoder/learn-deepseek-harness) ⭐ 11 - 交互式教程：20 节课，从"模型只会说话"讲到写出能装进真实 DSH 的插件，含可跑 demo。

## 其他 Awesome 列表

- [0xsline/awesome-deepseek-harness](https://github.com/0xsline/awesome-deepseek-harness) ⭐ 744 - 基于 dsh-external/hub 与 `dsh-plugin` topic 整理的插件、工具与基础设施列表。
- [Zhiyuan-Fan/Awesome-DeepSeek-Harness-Plugins](https://github.com/Zhiyuan-Fan/Awesome-DeepSeek-Harness-Plugins) ⭐ 180 - 插件、扩展、工具、Skills、客户端、运行时与已验证参考的分类清单。
- [Dominic789654/awesome-deepseek-harness](https://github.com/Dominic789654/awesome-deepseek-harness) ⭐ 158 - 插件、Skills、MCP、编排器与 UI 的分类清单。
- [libukai/awesome-deepseek-harness](https://github.com/libukai/awesome-deepseek-harness) ⭐ 153 - DSH 终极指南：快速入门、资源推荐、精选插件与实用工具。
- [Alex-Yanggg/awesome-DSH-plugin](https://github.com/Alex-Yanggg/awesome-DSH-plugin) ⭐ 72 - 覆盖生产力、开发资源等方向的插件与工具精选。

## 友情链接

- [LINUX DO](https://linux.do/) - 新的理想型社区。

## 贡献

欢迎提交 PR 补充优质的 DSH 相关项目。建议：仓库需与 DeepSeek Harness 直接相关，有清晰的 README 与真实可用的功能。

> 数据说明：star 数为 2026-08-19 快照，仅供参考；生态迭代极快，欢迎随时更新。
