# Awesome DeepSeek Harness

中文 | [English](README_EN.md)

> 精选 DeepSeek Harness (DSH) 相关的开源项目、插件、桌面客户端、插件市场与教程。

[DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness)（`dsh`）是 DeepSeek 于 2026 年 8 月 13 日开源的 Agent Harness，核心理念是 **"Everything is a Plugin"（万物皆插件）**，基于 [Cordis](https://github.com/cordiverse/cordis) 插件架构，MIT 协议。发布次日 star 即突破 8 万，GitHub 上 `dsh-plugin` topic 下已有 1400+ 个生态仓库。

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
- [集成与周边工具](#集成与周边工具)
- [教程与学习资源](#教程与学习资源)
- [其他 Awesome 列表](#其他-awesome-列表)
- [友情链接](#友情链接)
- [贡献](#贡献)

## 官方资源

- [deepseek-ai/deepseek-harness](https://github.com/deepseek-ai/deepseek-harness) ⭐ 80.3k - 官方仓库。目前处于 developer preview 阶段，迭代很快，存在破坏性变更。
- [官方主页](https://deepseek.com/harness) - deepseek.com/harness。
- [官方中文 README](https://github.com/deepseek-ai/deepseek-harness/blob/master/README.zh.md) / [docs 文档目录](https://github.com/deepseek-ai/deepseek-harness/tree/master/docs) - 架构、Agent 生命周期、API Gateway 等中英双语文档。
- [Cordis](https://github.com/cordiverse/cordis) - DSH 底层的插件化框架，"万物皆插件"的技术基座。
- [dsh-plugin topic](https://github.com/topics/dsh-plugin) - 官方推荐的插件发现入口：给插件仓库打上 `dsh-plugin` topic 即可被发现，目前已有 1400+ 仓库。
- [GitHub Discussions](https://github.com/deepseek-ai/deepseek-harness/discussions) - 官方反馈与讨论区。
- [Discord 社区](https://discord.gg/Ycq5dCaS4) - 官方 Discord。

## 插件市场与插件发现

- [AdamPlatin123/awesome-dsh-plugins](https://github.com/AdamPlatin123/awesome-dsh-plugins) ⭐ 625 - 插件雷达：自动扫描发现全网 dsh 插件候选，测试合格后移入精选目录。
- [awesome-dsh-plugin/awesome-dsh-plugin](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin) ⭐ 487 - DSH 插件精选列表（中英双语）。
- [bruc3van/awesome-dsh-plugin](https://github.com/bruc3van/awesome-dsh-plugin) ⭐ 54 - "30 秒找到适合你的插件"：按解决什么问题、适合谁来导航，而不只是仓库罗列。
- [LaplaceYoung/oh-my-dsh](https://github.com/LaplaceYoung/oh-my-dsh) ⭐ 39 - 面向 DSH 的插件生态，收录 700+ 插件，只通过扩展接缝注册、不修改 agent-loop 骨架。
- [OBdangshang07/DSH_Creative_Workshop](https://github.com/OBdangshang07/DSH_Creative_Workshop) ⭐ 38 - Steam 创意工坊式的插件发现、信任评估、图搜索、合集与事务化安装规划。
- [vlln/plugin-registry](https://github.com/vlln/plugin-registry) ⭐ 28 - 插件生态基建：浏览器面板管理官方 repository 插件（零 patch）+ `make-dsh-plugin` 插件开发引导。
- [bradeGithub/DSH-Plugins-Marketplace](https://github.com/bradeGithub/DSH-Plugins-Marketplace) ⭐ 14 - 在 DSH Web GUI 内一键浏览、安装与更新 `dsh-plugin` topic 下的全部插件。
- [hikariming/dshfind](https://github.com/hikariming/dshfind) ⭐ 12 - DSH 原理学习、插件市场与最佳实践。

## 桌面客户端

- [hust-open-atom-club/oh-dsh](https://github.com/hust-open-atom-club/oh-dsh) ⭐ 141 - 一站式社区发行版：TUI、桌面端、Web UI 三种形态统一体验，分层安装、一步到位。
- [dataelement/dsh-desktop](https://github.com/dataelement/dsh-desktop) ⭐ 106 - DeepSeek Harness 桌面应用。
- [steven-kid/deepseek-harness-desktop](https://github.com/steven-kid/deepseek-harness-desktop) ⭐ 85 - 极简桌面封装，跨平台、免配置、开箱即用。
- [turtle2209/Bigfish](https://github.com/turtle2209/Bigfish) ⭐ 69 - 第三方桌面端，内置 Node 运行时，双击即用，附带桌面萌宠。
- [myYangyunfan/dsh_desktop](https://github.com/myYangyunfan/dsh_desktop) ⭐ 62 - Windows 桌面客户端，捆绑 Node.js 与 dsh CLI，一键启动。
- [Ruler4396/dsh-launcher](https://github.com/Ruler4396/dsh-launcher) ⭐ 50 - Windows 轻量启动器：开机静默自启 + WebView2 极简窗口。
- [ChisaAlter/Deepseek-Harness-Desktop](https://github.com/ChisaAlter/Deepseek-Harness-Desktop) ⭐ 31 - Electron 桌面壳，支持主题、背景图等个性化配置。
- [xiincs/deepseek-harness-desktop](https://github.com/xiincs/deepseek-harness-desktop) ⭐ 23 - 基于 Tauri 2 的 Windows 原生桌面版，WebView 托管 dsh Web 服务，内置 Node.js。

## 终端 TUI

- [ccch1mneyyy/dsh-TUI](https://github.com/ccch1mneyyy/dsh-TUI) ⭐ 649 - 补齐官方暂无终端 TUI 的空缺：Claude Code 风格全屏交互终端插件，思考流式展开、双击 Esc 回滚、上下文进度条，npm 一键安装。
- [huiliyi37/dsh-tianshu-tui](https://github.com/huiliyi37/dsh-tianshu-tui) ⭐ 106 - 交互式终端 UI 插件，在官方基础上增加 TDD 与证据门等工作流。

## Web UI 增强与皮肤

- [zhu1090093659/dsh-web-ui](https://github.com/zhu1090093659/dsh-web-ui) ⭐ 1.3k - 插件与皮肤合集：任务板、Git graph、右侧面板、移动端远程 UI、桌宠、实时 token 统计、皮肤中心。
- [omdsh-dev/DSH-better-sidebar](https://github.com/omdsh-dev/DSH-better-sidebar) ⭐ 549 - 侧边栏完整工作台：文件渲染编辑、终端、Git、子代理，支持三方扩展注册新 Tab。
- [Small-tailqwq/dsh-deep-whale](https://github.com/Small-tailqwq/dsh-deep-whale) ⭐ 388 - "深海女仆工坊"鲸鱼娘皮肤系列。
- [Nagi-ovo/dsh-ads](https://github.com/Nagi-ovo/dsh-ads) ⭐ 265 - 整活插件：2005 年中文站点风格的侧栏广告 / 信息流 / 角落弹窗（素材全虚构）。
- [vlln/whale-girl](https://github.com/vlln/whale-girl) ⭐ 101 - QQ 宠物形态的桌面宠物插件：右下角悬浮，可拖拽、投喂、玩耍。
- [omdsh-dev/dsh-at-file](https://github.com/omdsh-dev/dsh-at-file) ⭐ 92 - Codex 风格 `@file` 引用：在输入框搜索工作区文件并附加到提示词。
- [Nagi-ovo/dsh-visualize](https://github.com/Nagi-ovo/dsh-visualize) ⭐ 63 - 对话内生成式 UI：模型把交互式 HTML 卡片直接画进会话流，带流式预览与沙箱渲染。
- [omdsh-dev/dsh-genui](https://github.com/omdsh-dev/dsh-genui) ⭐ 56 - GenUI：回复内直接渲染布局、图表、表单、测验等交互组件。

## 功能扩展插件

- [liustack/modlens](https://github.com/liustack/modlens) ⭐ 1k - 首个 DSH 视觉插件：粘贴图片，输出结构化 JSON 证据（OCR、布局、语义），也是纯文本 Agent 的通用视觉桥。
- [Anionex/dsh-vision-toolkit](https://github.com/Anionex/dsh-vision-toolkit) ⭐ 269 - 让纯文本模型做视觉任务：带意图的图片问答、长截图 OCR、UI 还原、grounding、像素 diff。
- [NanmiCoder/dsh-agent-teams](https://github.com/NanmiCoder/dsh-agent-teams) ⭐ 187 - AgentTeams 多智能体协作插件。
- [liustack/modsearch](https://github.com/liustack/modsearch) ⭐ 77 - Web 搜索插件：问 Web 或 X，返回结构化 JSON 证据。
- [Lum1104/dsh-browser](https://github.com/Lum1104/dsh-browser) ⭐ 67 - Chrome 侧边栏扩展，让 DSH 无需视觉能力直接操作你的浏览器。
- [icetomoyo/dsh_workflow](https://github.com/icetomoyo/dsh_workflow) ⭐ 49 - 把 UltraCode 式多 Agent 调度升级为可生成、可保存、可治理、可恢复的 Workflow 层。
- [Anionex/dsh-turn-rewind](https://github.com/Anionex/dsh-turn-rewind) ⭐ 32 - 对话与代码状态回退，基于持久化 Change Ledger。
- [csyangwen/dsh-memory-evolve](https://github.com/csyangwen/dsh-memory-evolve) ⭐ 30 - 纯插件实现跨会话长期记忆 + 后台自我进化：五轨记忆、技能自我进化、待办与调度，零核心修改。
- [titanwings/dsh-automation](https://github.com/titanwings/dsh-automation) ⭐ 23 - 自动化插件：让任务按计划在全新 Agent Session 中运行，支持定时任务管理。

## 集成与周边工具

- [nexu-io/open-design](https://github.com/nexu-io/open-design) ⭐ 85.8k - 开源 Claude Design 替代品，本地优先桌面应用，把编码 Agent 变成设计引擎，支持 DSH 在内的 20+ CLI。
- [CherryHQ/cherry-studio](https://github.com/CherryHQ/cherry-studio) ⭐ 50.5k - AI 生产力工作台，统一接入前沿大模型，已标注 `deepseek-harness` 支持。
- [titanwings/colleague-skill](https://github.com/titanwings/colleague-skill) ⭐ 21.7k - 现象级"数字生命"Skill 项目，已接入 dsh-plugin 生态。
- [Devin-AXIS/iPolloWork](https://github.com/Devin-AXIS/iPolloWork) ⭐ 3.8k - AI 工作空间，集成 DSH 做子代理委派，融合双方插件生态。
- [whiteguo233/OpenBiliClaw](https://github.com/whiteguo233/OpenBiliClaw) ⭐ 2.2k - 本地私有的自进化内容发现 Agent（B 站 / 小红书 / YouTube 等），提供 [DSH 插件](https://github.com/whiteguo233/dsh-openbiliclaw)。
- [xiufengsun/TokenTracker](https://github.com/xiufengsun/TokenTracker) ⭐ 1.3k - 本地优先的 token 用量与成本追踪，覆盖含 DSH 在内的 31 种编码工具。
- [yejiming/MuseAI](https://github.com/yejiming/MuseAI) ⭐ 525 - AI 角色扮演与故事世界，支持 DSH 插件接入。
- [mnemon-dev/mnemon](https://github.com/mnemon-dev/mnemon) ⭐ 426 - 图结构的 Agent 持久记忆（单二进制），支持 DSH。
- [PM-Shawn/Abu-Cowork](https://github.com/PM-Shawn/Abu-Cowork) ⭐ 321 - Claude Cowork 的开源替代：本地优先 AI Agent 桌面应用，DSH 集成进行中。
- [huiliyi37/Tianshu-Tui](https://github.com/huiliyi37/Tianshu-Tui) ⭐ 215 - 基于 Harness 工程的独立终端编程智能体运行时，针对 DeepSeek V4 做前缀缓存优化与深度适配。

## 教程与学习资源

- [alchaincyf/deepseek-harness-orange-book](https://github.com/alchaincyf/deepseek-harness-orange-book) ⭐ 338 - 橙皮书《从开机到拆开》：完整系统提示词、129 行启动清单、三份原始会话日志，PDF/EPUB/HTML 免费下载。
- [Electricitysheep/dsh-handbook](https://github.com/Electricitysheep/dsh-handbook) ⭐ 128 - 从 0 到 1 深度手册：安装、插件开发、性能调优、实测案例、同模型多 Agent 对比（中英 PDF）。
- [yanhua1010/dsh-harness-tutorial](https://github.com/yanhua1010/dsh-harness-tutorial) ⭐ 28 - DSH 原理与实现：从零到一实现一个 AI Agent 的中文教程（VitePress 站点 + 8 个 Demo + mini-harness 教学项目）。
- [pingfanfan/hello-dsh](https://github.com/pingfanfan/hello-dsh) ⭐ 22 - 零基础看懂"万物皆插件"：插件开发入门教程，含 22 个中文技能实例。

## 其他 Awesome 列表

- [0xsline/awesome-deepseek-harness](https://github.com/0xsline/awesome-deepseek-harness) ⭐ 289 - 基于 dsh-external/hub 与 `dsh-plugin` topic 整理的插件、工具与基础设施列表。
- [Alex-Yanggg/awesome-DSH-plugin](https://github.com/Alex-Yanggg/awesome-DSH-plugin) ⭐ 45 - 覆盖生产力、开发资源等方向的插件与工具精选。
- [Zhiyuan-Fan/Awesome-DeepSeek-Harness-Plugins](https://github.com/Zhiyuan-Fan/Awesome-DeepSeek-Harness-Plugins) ⭐ 34 - DSH 插件精选列表。
- [Dominic789654/awesome-deepseek-harness](https://github.com/Dominic789654/awesome-deepseek-harness) ⭐ 24 - 插件、Skills、MCP、编排器与 UI 的分类清单。
- [libukai/awesome-deepseek-harness](https://github.com/libukai/awesome-deepseek-harness) ⭐ 22 - DSH 终极指南：快速入门、资源推荐、精选插件与实用工具。

## 友情链接

- [LINUX DO](https://linux.do/) - 新的理想型社区。

## 贡献

欢迎提交 PR 补充优质的 DSH 相关项目。建议：仓库需与 DeepSeek Harness 直接相关，有清晰的 README 与真实可用的功能。

> 数据说明：star 数为 2026-08-14 快照，仅供参考；生态迭代极快，欢迎随时更新。
