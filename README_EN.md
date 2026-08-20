# Awesome DeepSeek Harness

[中文](README.md) | English

> A curated list of open-source projects, plugins, desktop clients, plugin marketplaces, and tutorials for DeepSeek Harness (DSH).

[DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness) (`dsh`) is an open-source agent harness released by DeepSeek on August 13, 2026. Its core philosophy is **"Everything is a Plugin"**, powered by the [Cordis](https://github.com/cordiverse/cordis) plugin framework, MIT licensed. It passed 160k stars in under a week, and the `dsh-plugin` topic on GitHub already counts 7,800+ ecosystem repositories.

Start the Web UI (served at `http://127.0.0.1:3080` by default) with one command:

```sh
npx @deepseek-ai/dsh web
```

## Contents

- [Official Resources](#official-resources)
- [Plugin Marketplaces & Discovery](#plugin-marketplaces--discovery)
- [Desktop Clients](#desktop-clients)
- [Terminal TUI](#terminal-tui)
- [Web UI Enhancements & Skins](#web-ui-enhancements--skins)
- [Capability Plugins](#capability-plugins)
- [Agent Skills](#agent-skills)
- [Memory & Context](#memory--context)
- [Related Harnesses & Agent Runtimes](#related-harnesses--agent-runtimes)
- [Integrations & Companion Tools](#integrations--companion-tools)
- [Tutorials & Learning Resources](#tutorials--learning-resources)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing)

## Official Resources

- [deepseek-ai/deepseek-harness](https://github.com/deepseek-ai/deepseek-harness) ⭐ 164k - The official repository. Currently in developer preview and iterating rapidly — expect breaking changes.
- [Official homepage](https://deepseek.com/harness) - deepseek.com/harness.
- [Docs directory](https://github.com/deepseek-ai/deepseek-harness/tree/master/docs) - Bilingual docs covering architecture, agent lifecycle, API gateway, and more.
- [Cordis](https://github.com/cordiverse/cordis) ⭐ 6.3k - The plugin framework underneath DSH; the technical foundation of "everything is a plugin".
- [dsh-plugin topic](https://github.com/topics/dsh-plugin) - The official plugin discovery mechanism: tag your plugin repo with `dsh-plugin`. 7,800+ repos so far.
- [GitHub Discussions](https://github.com/deepseek-ai/deepseek-harness/discussions) - Official feedback and discussion forum.
- [Discord community](https://discord.gg/Ycq5dCaS4) - Official Discord.

## Plugin Marketplaces & Discovery

- [awesome-dsh-plugin/awesome-dsh-plugin](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin) ⭐ 9.7k - A curated list of DSH plugins (English & Chinese) — the largest community plugin index.
- [AdamPlatin123/awesome-dsh-plugins](https://github.com/AdamPlatin123/awesome-dsh-plugins) ⭐ 1.2k - Plugin radar and leaderboard: 7,600+ auto-discovered candidates, real container install testing (883/1415 working), curated Top 50.
- [dsh-market/dsh-market](https://github.com/dsh-market/dsh-market) ⭐ 1.2k - The plugin market inside DeepSeek Harness: browse, search, one-click install.
- [Anil-matcha/awesome-dsh-plugin](https://github.com/Anil-matcha/awesome-dsh-plugin) ⭐ 946 - A curated list of plugins for the DSH plugin ecosystem.
- [bruc3van/awesome-dsh-plugin](https://github.com/bruc3van/awesome-dsh-plugin) ⭐ 242 - Daily automated crawling plus manual verification: real plugins get listed, hype-chasers get blacklisted, with public rejection reasons.
- [hikariming/dshfind](https://github.com/hikariming/dshfind) ⭐ 176 - Learn DSH principles, plugin marketplace, and best practices.
- [Nagi-ovo/dsh-find-plugins](https://github.com/Nagi-ovo/dsh-find-plugins) ⭐ 151 - A DSH skill that finds, installs, and verifies GitHub plugins.
- [OBdangshang07/DSH_Creative_Workshop](https://github.com/OBdangshang07/DSH_Creative_Workshop) ⭐ 60 - Steam-Workshop-inspired discovery, trust scoring, graph search, collections, and transactional install planning.
- [sandbaseai/dsh-plugin-store](https://github.com/sandbaseai/dsh-plugin-store) ⭐ 1 - A community plugin store embedded in DSH Settings for browsing, searching, filtering, and managing 4,100+ entries; it validates Leaderboard status and package specs before install and ships a reproducible preview package.

## Desktop Clients

- [anywhere-labs/deepseek-harness-desktop](https://github.com/anywhere-labs/deepseek-harness-desktop) ⭐ 14.6k - The most-starred desktop client, built for the DSH plugin ecosystem — "the desktop itself is a plugin".
- [zhukunpenglinyutong/desktop-cc-gui](https://github.com/zhukunpenglinyutong/desktop-cc-gui) ⭐ 4k - Multi-engine AI coding desktop client (Tauri): Claude Code, Codex, Gemini, OpenCode, and DSH in one GUI.
- [edison7009/EchoBird](https://github.com/edison7009/EchoBird) ⭐ 3.1k - One-click install and model switching across Claude Code, Codex CLI, Grok Build, DSH, Kimi Code, and more.
- [GCWing/BitFun](https://github.com/GCWing/BitFun) ⭐ 1.8k - High-performance agent runtime written in Rust, paired with a polished desktop application.
- [dataelement/dsh-desktop](https://github.com/dataelement/dsh-desktop) ⭐ 1k - DeepSeek Harness Desktop.
- [zouyuxuan122/Deepseek-Harness-EAC](https://github.com/zouyuxuan122/Deepseek-Harness-EAC) ⭐ 905 - Windows / Linux client bundling Node.js and the dsh CLI, with 10 built-in UI skins.
- [hairyf/deepseek-harness-desktop](https://github.com/hairyf/deepseek-harness-desktop) ⭐ 585 - Tauri desktop build: 5MB installer, zero environment setup, preset plugins, all platforms.
- [vibeinging/deepseek-harness-desktop-app](https://github.com/vibeinging/deepseek-harness-desktop-app) ⭐ 487 - A local AI desktop workspace for DSH sessions, projects, files, web research, plugins, and Office artifacts.
- [myYangyunfan/dsh_desktop](https://github.com/myYangyunfan/dsh_desktop) ⭐ 475 - Windows desktop client bundling Node.js and the dsh CLI for one-click launch.
- [fufankeji/deepseek-harness-studio](https://github.com/fufankeji/deepseek-harness-studio) ⭐ 322 - Zero-code desktop client with plugin discovery, trending pushes, one-click install/management, and AI recommendations.
- [turtle2209/Bigfish](https://github.com/turtle2209/Bigfish) ⭐ 276 - Third-party desktop client with a bundled Node runtime — double-click to run, desktop pet included.
- [hust-open-atom-club/oh-dsh](https://github.com/hust-open-atom-club/oh-dsh) ⭐ 255 - One DSH runtime, three development experiences: Desktop, Web, and TUI.
- [lencx/Minke](https://github.com/lencx/Minke) ⭐ 225 - 🐳 DeepSeek Harness Desktop.
- [op7418/pilot-harness](https://github.com/op7418/pilot-harness) ⭐ 211 - CodePilot-inspired desktop client and plugin suite for macOS, Windows, and Linux.
- [shaobeichen/dsh-pocket](https://github.com/shaobeichen/dsh-pocket) ⭐ 202 - Put DSH in your pocket: run dsh web on your desktop, scan a QR code to access it live from your phone (LAN and public network).
- [steven-kid/deepseek-harness-desktop](https://github.com/steven-kid/deepseek-harness-desktop) ⭐ 155 - Minimal desktop wrapper: cross-platform, zero-config, works out of the box.
- [Ruler4396/dsh-launcher](https://github.com/Ruler4396/dsh-launcher) ⭐ 150 - Lightweight Windows launcher: silent autostart at logon plus a minimal WebView2 window.

## Terminal TUI

- [ccch1mneyyy/dsh-TUI](https://github.com/ccch1mneyyy/dsh-TUI) ⭐ 2k - The TUI plugin featured by DSH's official WeChat account: Claude Code style, whale header bar, live status, streaming thoughts, double-Esc rewind, context progress and TPS. One-line npm install.
- [huiliyi37/dsh-tianshu-tui](https://github.com/huiliyi37/dsh-tianshu-tui) ⭐ 217 - Custom minimal ANSI rendering core: streaming Markdown/tool cards, multi-session tabs, 16+ themes, slash commands and pickers.

## Web UI Enhancements & Skins

- [zhu1090093659/dsh-web-ui](https://github.com/zhu1090093659/dsh-web-ui) ⭐ 4.8k - Plugin and skin collection: task board, git graph, right-side panel, remote mobile UI, pet, live token stats, and a skin center.
- [chuspeeism/dashi-taskboard](https://github.com/chuspeeism/dashi-taskboard) ⭐ 2.3k - Task board plugin for DSH.
- [omdsh-dev/DSH-better-sidebar](https://github.com/omdsh-dev/DSH-better-sidebar) ⭐ 2.3k - Open sidebar foundation supporting third-party page registration, with built-in file rendering/editing, terminal, Git, and subagents.
- [Small-tailqwq/dsh-deep-whale](https://github.com/Small-tailqwq/dsh-deep-whale) ⭐ 1.4k - "Deep-sea maid atelier" whale-girl skin series for the DSH Web UI.
- [Nagi-ovo/dsh-ads](https://github.com/Nagi-ovo/dsh-ads) ⭐ 508 - Parody plugin that turns DSH into a 2005-era web portal: sidebar ads, fake games, and popups (all assets fictional).
- [bowenliang123/dsh-context](https://github.com/bowenliang123/dsh-context) ⭐ 425 - Context insight and management: context dashboard/browser plus a context command, showing what the context window is made of and how it evolves.
- [omdsh-dev/dsh-at-file](https://github.com/omdsh-dev/dsh-at-file) ⭐ 403 - Codex-style `@file` mentions: search workspace files in the composer and attach their paths to prompts.
- [WYH66666666/DSH-Transparent-UI-Plugin](https://github.com/WYH66666666/DSH-Transparent-UI-Plugin) ⭐ 315 - Highly configurable glassmorphism theme: header, sidebar, and composer become frosted glass, with adjustable blur and wallpaper.
- [vlln/whale-girl](https://github.com/vlln/whale-girl) ⭐ 243 - QQ-pet-style desktop pet plugin: floats in the corner, draggable, feedable, playable.
- [omdsh-dev/dsh-genui](https://github.com/omdsh-dev/dsh-genui) ⭐ 237 - GenUI: interactive components — layouts, charts, forms, quizzes — rendered inline in assistant replies.
- [PC2005-cloud/dsh-pet](https://github.com/PC2005-cloud/dsh-pet) ⭐ 187 - Desktop pet: one-line install for 28 ready-made transparent animations, or build your own from AI video.
- [Nagi-ovo/dsh-visualize](https://github.com/Nagi-ovo/dsh-visualize) ⭐ 182 - Render model-generated interactive cards inside DSH conversations.
- [d-dev0101/open-sea-skin](https://github.com/d-dev0101/open-sea-skin) ⭐ 179 - WebGPU ocean skin, shipped as a DSH plugin, a browser extension, and a static installer.
- [PerryLink/dsh-mcp-panel](https://github.com/PerryLink/dsh-mcp-panel) ⭐ 10 - MCP client console: `/mcp` health diagnostics, server CRUD in Settings (with approval gate and auto-backup), and a tool test bench.
- [Js2Hou/dsh-mcp-manager](https://github.com/Js2Hou/dsh-mcp-manager) ⭐ 8 - Visual MCP manager: inspect, add, remove, enable/disable MCP servers from Settings → MCP, with live connection status and tool counts.

## Capability Plugins

- [xiaobright/dsh-anchored-standard](https://github.com/xiaobright/dsh-anchored-standard) ⭐ 3.6k - Two-phase DSH preset: minimal-aligned bootstrap, then the full Standard toolset.
- [liustack/modlens](https://github.com/liustack/modlens) ⭐ 3.2k - The first vision plugin for DSH: paste an image, get structured JSON evidence (OCR, layout, semantics). A vision bridge for any text-only coding agent.
- [ysr666/dsh-vision-router](https://github.com/ysr666/dsh-vision-router) ⭐ 806 - Eyes for text-only DSH agents: a built-in key-free vision chain plus pixel-level vision tools.
- [Anionex/dsh-vision-toolkit](https://github.com/Anionex/dsh-vision-toolkit) ⭐ 736 - A stronger vision toolkit: free to use, paste-to-recognize, multi-image Q&A, and screenshot-to-UI restoration.
- [NanmiCoder/dsh-agent-teams](https://github.com/NanmiCoder/dsh-agent-teams) ⭐ 593 - AgentTeams multi-agent collaboration plugin for DSH.
- [yjh051108/dsh-router-standard](https://github.com/yjh051108/dsh-router-standard) ⭐ 345 - Task-aware reasoning-mode router: three measured behavior bands (spec/mixed/react) with phase transitions.
- [Lum1104/dsh-browser](https://github.com/Lum1104/dsh-browser) ⭐ 311 - Chrome sidebar extension that lets DSH operate your browser directly — no vision capabilities required.
- [liustack/modsearch](https://github.com/liustack/modsearch) ⭐ 164 - The web search plugin for DSH: ask the web or X, get structured JSON evidence back.
- [Anionex/dsh-turn-rewind](https://github.com/Anionex/dsh-turn-rewind) ⭐ 86 - Rewind conversation and workspace state, powered by a persistent Change Ledger.
- [omdsh-dev/dsh_workflow](https://github.com/omdsh-dev/dsh_workflow) ⭐ 85 - Upgrades one-shot multi-agent dispatch into a workflow layer that is generatable, savable, governable, and resumable.
- [Nwflower/dsh-chat-import](https://github.com/Nwflower/dsh-chat-import) ⭐ 71 - Full-fidelity import of chat history from 13 coding agents (Claude Code, Codex, Cursor, Gemini, OpenClaw, and more) into resumable DSH sessions, with export/sync back to Claude Code.
- [PerryLink/dsh-auto-review](https://github.com/PerryLink/dsh-auto-review) ⭐ 42 - A second model reviewing the approval chain: a read-only subagent returns structured allow/deny verdicts with reasoning and risk levels, fail-closed by default.
- [PerryLink/dsh-permission-rules](https://github.com/PerryLink/dsh-permission-rules) ⭐ 15 - Declarative allow/deny/ask permission rules plus process-level network policy (built-in local HTTP/CONNECT proxy), full session audit logging, and hot rule reload.
- [slywalker2006/dsh-passwords](https://github.com/slywalker2006/dsh-passwords) ⭐ 12 - Login gateway for the DSH web UI: multi-user accounts, bcrypt encryption, brute-force lockout, audit log, and automatic HTTPS.
- [xiaoyuyu6420/dsh-backup](https://github.com/xiaoyuyu6420/dsh-backup) ⭐ 3 - One-click backup and restore for DSH user data (`~/.dsh`): scheduled auto-backup, sha256 integrity checks, hardened restore-path vetting, GitHub private-repo sync, and a Settings panel. Cross-platform.

## Agent Skills

> Cross-agent skill packages that work in DSH (and other harnesses), all plugged into the `dsh-plugin` ecosystem.

- [titanwings/colleague-skill](https://github.com/titanwings/colleague-skill) ⭐ 23.5k - The viral "Digital Life" skill: transforming cold farewells into warm skills.
- [tt-a1i/archify](https://github.com/tt-a1i/archify) ⭐ 14.4k - Agent skill for architecture, workflow, sequence, data-flow, and lifecycle diagrams — self-contained, verifiable HTML.
- [foryourhealth111-pixel/Vibe-Skills](https://github.com/foryourhealth111-pixel/Vibe-Skills) ⭐ 2.9k - General-purpose skill router: automatically routes local skills and intelligently orchestrates harness work.
- [hyhmrright/brooks-lint](https://github.com/hyhmrright/brooks-lint) ⭐ 1.4k - AI code reviews grounded in 12 classic engineering books: decay-risk diagnostics with book citations and severity labels.
- [Tencent/BrowserSkill](https://github.com/Tencent/BrowserSkill) ⭐ 1.2k - By Tencent: let AI agents use your real, logged-in browser without interrupting your work. CLI plus extension.
- [GanyuanRan/Aegis](https://github.com/GanyuanRan/Aegis) ⭐ 1.1k - Makes AI coding agents architecture-aware: baseline-first, evidence-verified, drift-checked.
- [Jayden-X-L/forkprobe](https://github.com/Jayden-X-L/forkprobe) ⭐ 67 - Compare multiple skills on the same task and pick the winner.
- [dhicoc/dsh-reverse-skill](https://github.com/dhicoc/dsh-reverse-skill) ⭐ 40 - Packages the 85 SKILL.md files from upstream [reverse-skill](https://github.com/zhaoxuya520/reverse-skill) (26.5k⭐) into a Cordis plugin: reverse engineering, authorized pentesting, CTF, and security-research skill routing. Authorized use only.

## Memory & Context

> A category that exploded after the DSH release: giving agents long-term memory across sessions.

- [volcengine/OpenViking](https://github.com/volcengine/OpenViking) ⭐ 29.8k - By Volcengine: a self-evolving context database for AI agents, unifying memory, knowledge RAG, and skills.
- [EverMind-AI/EverOS](https://github.com/EverMind-AI/EverOS) ⭐ 12.2k - One portable memory layer for every AI agent: local-first, Markdown-native, user-owned, self-evolving.
- [MemTensor/MemOS](https://github.com/MemTensor/MemOS) ⭐ 10.8k - Self-evolving memory OS for LLMs and agents: ultra-persistent memory, hybrid retrieval, cross-task skill reuse.
- [adoresever/graph-memory](https://github.com/adoresever/graph-memory) ⭐ 554 - Knowledge graph memory plugin that extracts structured triples from conversations.
- [mnemon-dev/mnemon](https://github.com/mnemon-dev/mnemon) ⭐ 484 - Graph-based persistent memory for agents in a single binary, works with DSH.
- [csyangwen/dsh-memory-evolve](https://github.com/csyangwen/dsh-memory-evolve) ⭐ 188 - Plugin-only cross-session long-term memory and background self-evolution: five-track memory, skill self-evolution, todos, and scheduling.
- [PerryLink/dsh-memento](https://github.com/PerryLink/dsh-memento) ⭐ 58 - Bounded, layered, approval-gated, auditable cross-session memory: a `ctx.memory` service, a zero-dependency SQLite provider, and frozen-snapshot injection.

## Related Harnesses & Agent Runtimes

> Other open-source harnesses and agent runtimes that emerged alongside DSH and interoperate with its ecosystem.

- [Hmbown/CodeWhale](https://github.com/Hmbown/CodeWhale) ⭐ 40.8k - Open-source, community-driven agent harness.
- [esengine/DeepSeek-Reasonix](https://github.com/esengine/DeepSeek-Reasonix) ⭐ 34.8k - DeepSeek-native terminal coding agent, engineered around prefix-cache stability.
- [YaoApp/yao](https://github.com/YaoApp/yao) ⭐ 7.7k - All your agents and workspaces in one place, on every device, with board-based task tracking.
- [Q00/ouroboros](https://github.com/Q00/ouroboros) ⭐ 5.6k - Agent OS where the agent improves itself; the grading command and expected result never enter the context.
- [xintaofei/codeg](https://github.com/xintaofei/codeg) ⭐ 2.8k - Collaborative multi-agent AI coding workspace aggregating sessions from Claude Code, Codex, OpenCode, Pi, and others.
- [paean-ai/deeptide](https://github.com/paean-ai/deeptide) ⭐ 1.1k - Built by DeepSeek, for DeepSeek — a Swift-native macOS coding agent.
- [huiliyi37/Tianshu-harness](https://github.com/huiliyi37/Tianshu-harness) ⭐ 244 - Tianshu: a harness-engineered terminal coding agent runtime (TUI × GUI), deeply adapted for DeepSeek V4 with 97–99% prefix-cache hit rates in long sessions.

## Integrations & Companion Tools

- [nexu-io/open-design](https://github.com/nexu-io/open-design) ⭐ 89.2k - Open-source Claude Design alternative: a local-first desktop app that turns coding agents into a design engine, supporting DSH among 20+ CLIs.
- [CherryHQ/cherry-studio](https://github.com/CherryHQ/cherry-studio) ⭐ 50.8k - AI productivity studio with unified access to frontier LLMs; tagged with `deepseek-harness` support.
- [Nagi-ovo/voyager](https://github.com/Nagi-ovo/voyager) ⭐ 19.7k - Enhancement suite for Gemini, AI Studio, Claude, and ChatGPT, plus a prompt manager for any web UI, DSH included.
- [Devin-AXIS/iPolloWork](https://github.com/Devin-AXIS/iPolloWork) ⭐ 4.2k - AI workspace that integrates DSH for subagent delegation, combining both plugin ecosystems.
- [crafter-station/petdex](https://github.com/crafter-station/petdex) ⭐ 3.9k - A public gallery of animated pets for Codex, Claude Code, DeepSeek Harness, and more.
- [strukto-ai/mirage](https://github.com/strukto-ai/mirage) ⭐ 3.5k - A unified virtual filesystem for AI agents.
- [whiteguo233/OpenBiliClaw](https://github.com/whiteguo233/OpenBiliClaw) ⭐ 2.9k - Local-first self-evolving content discovery agent (Bilibili / Xiaohongshu / YouTube, etc.) with a dedicated [DSH plugin](https://github.com/whiteguo233/dsh-openbiliclaw).
- [Javis603/token-monitor](https://github.com/Javis603/token-monitor) ⭐ 1.5k - Local-first desktop widget tracking token usage, costs, and limits across 30+ AI coding tools.
- [xiufengsun/TokenTracker](https://github.com/xiufengsun/TokenTracker) ⭐ 1.4k - Local-first AI token usage and cost tracker covering 31 coding tools.
- [alvinunreal/openpets](https://github.com/alvinunreal/openpets) ⭐ 1.1k - Local-first desktop companion platform with animated pets, a plugin SDK, and coding-agent integrations.
- [tong-io/tongflow](https://github.com/tong-io/tongflow) ⭐ 867 - Multimodal workflow studio and engine (canvas plus Python plugin engine), including the dsh-tongflow plugin.
- [yejiming/MuseAI](https://github.com/yejiming/MuseAI) ⭐ 589 - AI roleplay and story worlds, with DSH plugin support.
- [PM-Shawn/Abu-Cowork](https://github.com/PM-Shawn/Abu-Cowork) ⭐ 337 - Open-source alternative to Claude Cowork: a local-first AI agent desktop app.
- [alaliqing/claude-paper](https://github.com/alaliqing/claude-paper) ⭐ 319 - Cross-agent research paper toolkit for Claude Code, Codex, OpenCode, and DSH.

## Tutorials & Learning Resources

- [walkinglabs/learn-harness-engineering](https://github.com/walkinglabs/learn-harness-engineering) ⭐ 12.3k - Harness engineering beginner tutorial, from 0 to 1 — currently the most popular harness teaching project.
- [alchaincyf/deepseek-harness-orange-book](https://github.com/alchaincyf/deepseek-harness-orange-book) ⭐ 1.1k - The "Orange Book": full system prompt, a 129-line boot checklist, and three raw session logs. Free PDF/EPUB/HTML.
- [Electricitysheep/dsh-handbook](https://github.com/Electricitysheep/dsh-handbook) ⭐ 522 - A zero-to-one deep-dive handbook: installation, plugin development, performance tuning, field cases, and same-model multi-agent comparisons (Chinese & English PDF).
- [adongwanai/learn-workbuddy](https://github.com/adongwanai/learn-workbuddy) ⭐ 183 - Rebuild a desktop AI assistant harness from scratch: 24 Python chapters covering agent loop, tool calling, memory, and sandbox auditing.
- [ht426/deepseek-harness-tutorial](https://github.com/ht426/deepseek-harness-tutorial) ⭐ 178 - A detailed Chinese study tutorial for DeepSeek Harness.
- [pingfanfan/hello-dsh](https://github.com/pingfanfan/hello-dsh) ⭐ 77 - Zero-to-plugin tutorial for understanding "everything is a plugin", with 22 Chinese skill examples.
- [yanhua1010/dsh-harness-tutorial](https://github.com/yanhua1010/dsh-harness-tutorial) ⭐ 52 - How DSH works and how to build one from scratch (VitePress site + 8 demos + a mini-harness project).
- [yu-xin-c/agent-unpacked](https://github.com/yu-xin-c/agent-unpacked) ⭐ 18 - Source-code teardown tutorials for DSH, PI Agent, and nanobot.
- [NanmiCoder/learn-deepseek-harness](https://github.com/NanmiCoder/learn-deepseek-harness) ⭐ 11 - Interactive tutorial: 20 lessons from "the model can only talk" to writing a plugin that installs into real DSH, with runnable demos.

## Other Awesome Lists

- [0xsline/awesome-deepseek-harness](https://github.com/0xsline/awesome-deepseek-harness) ⭐ 744 - Curated plugins, tools, and infrastructure from dsh-external/hub and the public `dsh-plugin` topic.
- [Zhiyuan-Fan/Awesome-DeepSeek-Harness-Plugins](https://github.com/Zhiyuan-Fan/Awesome-DeepSeek-Harness-Plugins) ⭐ 180 - Curated plugins, extensions, tools, skills, clients, runtimes, and verified references.
- [Dominic789654/awesome-deepseek-harness](https://github.com/Dominic789654/awesome-deepseek-harness) ⭐ 158 - Categorized list of plugins, skills, MCP servers, orchestrators, and UIs.
- [libukai/awesome-deepseek-harness](https://github.com/libukai/awesome-deepseek-harness) ⭐ 153 - The ultimate guide to DSH: quickstart, resources, plugins, and toolkit.
- [Alex-Yanggg/awesome-DSH-plugin](https://github.com/Alex-Yanggg/awesome-DSH-plugin) ⭐ 72 - Curated plugins, extensions, tools, and development resources for DSH.

## Contributing

PRs are welcome. Guidelines: repositories should be directly related to DeepSeek Harness, with a clear README and genuinely working functionality.

> Note: star counts are a snapshot taken on 2026-08-19 and are for reference only — this ecosystem moves fast.
