# Awesome DeepSeek Harness

[中文](README.md) | English

> A curated list of open-source projects, plugins, desktop clients, plugin marketplaces, and tutorials for DeepSeek Harness (DSH).

[DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness) (`dsh`) is an open-source agent harness released by DeepSeek on August 13, 2026. Its core philosophy is **"Everything is a Plugin"**, powered by the [Cordis](https://github.com/cordiverse/cordis) plugin framework, MIT licensed. It passed 100k stars within two days of release, and the `dsh-plugin` topic on GitHub already counts 2,800+ ecosystem repositories.

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
- [Integrations & Companion Tools](#integrations--companion-tools)
- [Tutorials & Learning Resources](#tutorials--learning-resources)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing)

## Official Resources

- [deepseek-ai/deepseek-harness](https://github.com/deepseek-ai/deepseek-harness) ⭐ 102k - The official repository. Currently in developer preview and iterating rapidly — expect breaking changes.
- [Official homepage](https://deepseek.com/harness) - deepseek.com/harness.
- [Docs directory](https://github.com/deepseek-ai/deepseek-harness/tree/master/docs) - Bilingual docs covering architecture, agent lifecycle, API gateway, and more.
- [Cordis](https://github.com/cordiverse/cordis) - The plugin framework underneath DSH; the technical foundation of "everything is a plugin".
- [dsh-plugin topic](https://github.com/topics/dsh-plugin) - The official plugin discovery mechanism: tag your plugin repo with `dsh-plugin`. 2,800+ repos so far.
- [GitHub Discussions](https://github.com/deepseek-ai/deepseek-harness/discussions) - Official feedback and discussion forum.
- [Discord community](https://discord.gg/Ycq5dCaS4) - Official Discord.

## Plugin Marketplaces & Discovery

- [awesome-dsh-plugin/awesome-dsh-plugin](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin) ⭐ 1.7k - A curated list of DSH plugins (English & Chinese) — currently the largest community plugin index.
- [AdamPlatin123/awesome-dsh-plugins](https://github.com/AdamPlatin123/awesome-dsh-plugins) ⭐ 887 - Plugin radar: automatically scans and discovers dsh plugin candidates; tested ones graduate into a curated directory.
- [dsh-market/dsh-market](https://github.com/dsh-market/dsh-market) ⭐ 127 - The plugin market inside DeepSeek Harness: browse, search, one-click install.
- [bruc3van/awesome-dsh-plugin](https://github.com/bruc3van/awesome-dsh-plugin) ⭐ 114 - "Find the right plugin in 30 seconds": navigates by what problem a plugin solves and who it's for, not just a repo dump.
- [Nagi-ovo/dsh-find-plugins](https://github.com/Nagi-ovo/dsh-find-plugins) ⭐ 75 - A DSH skill that finds, installs, and verifies GitHub plugins.
- [hikariming/dshfind](https://github.com/hikariming/dshfind) ⭐ 71 - Learn DSH principles, plugin marketplace, and best practices.
- [OBdangshang07/DSH_Creative_Workshop](https://github.com/OBdangshang07/DSH_Creative_Workshop) ⭐ 53 - Steam-Workshop-inspired discovery, trust scoring, graph search, collections, and transactional install planning for DSH plugins.
- [LaplaceYoung/oh-my-dsh](https://github.com/LaplaceYoung/oh-my-dsh) ⭐ 44 - A plugin ecosystem for DSH with 700+ plugins, registered only through extension seams without touching the agent-loop core.

## Desktop Clients

- [anywhere-labs/deepseek-harness-desktop](https://github.com/anywhere-labs/deepseek-harness-desktop) ⭐ 3.1k - A modern desktop experience for the DSH ecosystem — currently the most-starred desktop client.
- [dataelement/dsh-desktop](https://github.com/dataelement/dsh-desktop) ⭐ 202 - Desktop app for DeepSeek Harness.
- [turtle2209/Bigfish](https://github.com/turtle2209/Bigfish) ⭐ 188 - Third-party desktop client with a bundled Node runtime — double-click to run, desktop pet included.
- [hust-open-atom-club/oh-dsh](https://github.com/hust-open-atom-club/oh-dsh) ⭐ 176 - One-stop community distribution: unified TUI, desktop, and Web UI experience with layered, one-step installation.
- [myYangyunfan/dsh_desktop](https://github.com/myYangyunfan/dsh_desktop) ⭐ 129 - Windows desktop client bundling Node.js and the dsh CLI for one-click launch.
- [steven-kid/deepseek-harness-desktop](https://github.com/steven-kid/deepseek-harness-desktop) ⭐ 126 - Minimal desktop wrapper: cross-platform, zero-config, works out of the box.
- [hairyf/deepseek-harness-desktop](https://github.com/hairyf/deepseek-harness-desktop) ⭐ 123 - One-click desktop app with zero environment setup. Windows / macOS / Linux.
- [vibeinging/deepseek-harness-desktop-app](https://github.com/vibeinging/deepseek-harness-desktop-app) ⭐ 109 - A local AI desktop workspace for DSH sessions, projects, files, web research, plugins, and Office artifacts.
- [Ruler4396/dsh-launcher](https://github.com/Ruler4396/dsh-launcher) ⭐ 81 - Lightweight Windows launcher: silent autostart at logon plus a minimal WebView2 window.

## Terminal TUI

- [ccch1mneyyy/dsh-TUI](https://github.com/ccch1mneyyy/dsh-TUI) ⭐ 992 - Fills the gap of a missing official TUI: a Claude Code-style full-screen terminal plugin with streaming thoughts, double-Esc rewind, and a context progress bar. One-line npm install.
- [huiliyi37/dsh-tianshu-tui](https://github.com/huiliyi37/dsh-tianshu-tui) ⭐ 140 - Interactive terminal UI plugin that adds TDD and evidence-gate workflows on top of the official harness.

## Web UI Enhancements & Skins

- [zhu1090093659/dsh-web-ui](https://github.com/zhu1090093659/dsh-web-ui) ⭐ 2.2k - Plugin and skin collection: task board, git graph, right-side panel, remote mobile UI, pet, live token stats, and a skin center.
- [omdsh-dev/DSH-better-sidebar](https://github.com/omdsh-dev/DSH-better-sidebar) ⭐ 866 - A full workbench in the sidebar: file rendering/editing, terminal, Git, subagents, with third-party page registration.
- [Small-tailqwq/dsh-deep-whale](https://github.com/Small-tailqwq/dsh-deep-whale) ⭐ 697 - "Deep-sea maid atelier" whale-girl skin series for the DSH Web UI.
- [Nagi-ovo/dsh-ads](https://github.com/Nagi-ovo/dsh-ads) ⭐ 364 - Parody plugin that turns DSH into a 2005-era web portal: sidebar ads, fake games, and popups (all assets fictional).
- [omdsh-dev/dsh-at-file](https://github.com/omdsh-dev/dsh-at-file) ⭐ 154 - Codex-style `@file` mentions: search workspace files in the composer and attach their contents to prompts.
- [vlln/whale-girl](https://github.com/vlln/whale-girl) ⭐ 145 - QQ-pet-style desktop pet plugin: floats in the corner, draggable, feedable, playable.
- [Nagi-ovo/dsh-visualize](https://github.com/Nagi-ovo/dsh-visualize) ⭐ 86 - Generative visualization in conversation: the model renders interactive HTML cards directly into the chat stream.
- [omdsh-dev/dsh-genui](https://github.com/omdsh-dev/dsh-genui) ⭐ 82 - GenUI: interactive components — layouts, charts, forms, quizzes — rendered inline in assistant replies.

## Capability Plugins

- [liustack/modlens](https://github.com/liustack/modlens) ⭐ 1.4k - The first vision plugin for DSH: paste an image, get structured JSON evidence (OCR, layout, semantics). A vision bridge for any text-only coding agent.
- [xiaobright/dsh-anchored-standard](https://github.com/xiaobright/dsh-anchored-standard) ⭐ 1.1k - Two-phase DSH preset: minimal-aligned bootstrap, then the full Standard toolset.
- [Anionex/dsh-vision-toolkit](https://github.com/Anionex/dsh-vision-toolkit) ⭐ 371 - Vision tasks for text-only models: intent-aware image Q&A, long-screenshot OCR, UI restoration, grounding, and pixel diff.
- [NanmiCoder/dsh-agent-teams](https://github.com/NanmiCoder/dsh-agent-teams) ⭐ 277 - AgentTeams multi-agent collaboration plugin for DSH.
- [Lum1104/dsh-browser](https://github.com/Lum1104/dsh-browser) ⭐ 107 - Chrome sidebar extension that lets DSH operate your browser directly — no vision capabilities required.
- [liustack/modsearch](https://github.com/liustack/modsearch) ⭐ 98 - The web plugin for DSH: ask the web or X, get structured JSON evidence — a search bridge for models without native web access.
- [ysr666/dsh-vision-router](https://github.com/ysr666/dsh-vision-router) ⭐ 81 - Eyes for text-only DSH agents: a built-in key-free vision chain plus pixel-level vision tools (Q&A, grounding, crop, pixel diff).
- [csyangwen/dsh-memory-evolve](https://github.com/csyangwen/dsh-memory-evolve) ⭐ 64 - Plugin-only cross-session long-term memory and background self-evolution: five-track memory, skill self-evolution, todos, and scheduling — zero core modifications.
- [icetomoyo/dsh_workflow](https://github.com/icetomoyo/dsh_workflow) ⭐ 55 - Upgrades one-shot multi-agent dispatch into a workflow layer that is generatable, savable, governable, and resumable.
- [Anionex/dsh-turn-rewind](https://github.com/Anionex/dsh-turn-rewind) ⭐ 47 - Rewind conversation and workspace state, powered by a persistent Change Ledger.
- [slywalker2006/dsh-passwords](https://github.com/slywalker2006/dsh-passwords) ⭐ 3 - Login gateway (password door) for the DSH web UI: first-run setup, multi-user accounts, bcrypt encryption, brute-force lockout, audit log, and automatic HTTPS.

## Agent Skills

> Cross-agent skill packages that work in DSH (and other harnesses), all plugged into the `dsh-plugin` ecosystem.

- [titanwings/colleague-skill](https://github.com/titanwings/colleague-skill) ⭐ 22.2k - The viral "Digital Life" skill: transforming cold farewells into warm skills.
- [tt-a1i/archify](https://github.com/tt-a1i/archify) ⭐ 12.7k - Agent skill for architecture, workflow, sequence, data-flow, and lifecycle diagrams — self-contained, verifiable HTML.
- [foryourhealth111-pixel/Vibe-Skills](https://github.com/foryourhealth111-pixel/Vibe-Skills) ⭐ 2.8k - General-purpose skill router: automatically routes local skills and intelligently orchestrates harness work.
- [hyhmrright/brooks-lint](https://github.com/hyhmrright/brooks-lint) ⭐ 1.3k - AI code reviews grounded in 12 classic engineering books: decay-risk diagnostics with book citations and severity labels.
- [GanyuanRan/Aegis](https://github.com/GanyuanRan/Aegis) ⭐ 1k - Makes AI coding agents architecture-aware: baseline-first, evidence-verified, drift-checked.
- [Jayden-X-L/forkprobe](https://github.com/Jayden-X-L/forkprobe) ⭐ 65 - Compare multiple skills on the same task and pick the winner.

## Integrations & Companion Tools

- [nexu-io/open-design](https://github.com/nexu-io/open-design) ⭐ 86.5k - Open-source Claude Design alternative: a local-first desktop app that turns coding agents into a design engine, supporting DSH among 20+ CLIs.
- [CherryHQ/cherry-studio](https://github.com/CherryHQ/cherry-studio) ⭐ 50.5k - AI productivity studio with unified access to frontier LLMs; tagged with `deepseek-harness` support.
- [Devin-AXIS/iPolloWork](https://github.com/Devin-AXIS/iPolloWork) ⭐ 4k - AI workspace that integrates DSH for subagent delegation, combining both plugin ecosystems in one workflow.
- [crafter-station/petdex](https://github.com/crafter-station/petdex) ⭐ 3.8k - A public gallery of animated pets for Codex, Claude Code, DeepSeek Harness, and more.
- [strukto-ai/mirage](https://github.com/strukto-ai/mirage) ⭐ 3.4k - A unified virtual filesystem for AI agents, plugged into the dsh-plugin ecosystem.
- [whiteguo233/OpenBiliClaw](https://github.com/whiteguo233/OpenBiliClaw) ⭐ 2.4k - Local-first self-evolving content discovery agent (Bilibili / Xiaohongshu / YouTube, etc.) with a dedicated [DSH plugin](https://github.com/whiteguo233/dsh-openbiliclaw).
- [xiufengsun/TokenTracker](https://github.com/xiufengsun/TokenTracker) ⭐ 1.3k - Local-first AI token usage and cost tracker covering 31 coding tools, DSH included.
- [yejiming/MuseAI](https://github.com/yejiming/MuseAI) ⭐ 546 - AI roleplay and story worlds, with DSH plugin support.
- [mnemon-dev/mnemon](https://github.com/mnemon-dev/mnemon) ⭐ 441 - Graph-based persistent memory for agents in a single binary, works with DSH.
- [PM-Shawn/Abu-Cowork](https://github.com/PM-Shawn/Abu-Cowork) ⭐ 326 - Open-source alternative to Claude Cowork: a local-first AI agent desktop app; DSH integration in progress.
- [alaliqing/claude-paper](https://github.com/alaliqing/claude-paper) ⭐ 294 - Cross-agent research paper toolkit for Claude Code, Codex, OpenCode, and DSH: quick summaries and deep study materials.
- [huiliyi37/Tianshu-Tui](https://github.com/huiliyi37/Tianshu-Tui) ⭐ 224 - A standalone harness-engineered terminal coding agent runtime, deeply adapted for DeepSeek V4 with prefix-cache optimization.

## Tutorials & Learning Resources

- [alchaincyf/deepseek-harness-orange-book](https://github.com/alchaincyf/deepseek-harness-orange-book) ⭐ 645 - The "Orange Book": full system prompt, a 129-line boot checklist, and three raw session logs — first-hand findings not in the official docs. Free PDF/EPUB/HTML.
- [Electricitysheep/dsh-handbook](https://github.com/Electricitysheep/dsh-handbook) ⭐ 239 - A zero-to-one deep-dive handbook: installation, plugin development, performance tuning, field cases, and same-model multi-agent comparisons (Chinese & English PDF).
- [pingfanfan/hello-dsh](https://github.com/pingfanfan/hello-dsh) ⭐ 44 - Zero-to-plugin tutorial for understanding "everything is a plugin", with 22 Chinese skill examples.
- [yanhua1010/dsh-harness-tutorial](https://github.com/yanhua1010/dsh-harness-tutorial) ⭐ 39 - How DSH works and how to build one: a Chinese tutorial implementing an AI agent from scratch (VitePress site + 8 demos + a mini-harness teaching project).
- [ht426/deepseek-harness-tutorial](https://github.com/ht426/deepseek-harness-tutorial) ⭐ 36 - A detailed Chinese study tutorial for DeepSeek Harness.

## Other Awesome Lists

- [0xsline/awesome-deepseek-harness](https://github.com/0xsline/awesome-deepseek-harness) ⭐ 430 - Curated plugins, tools, and infrastructure from dsh-external/hub and the public `dsh-plugin` topic.
- [Alex-Yanggg/awesome-DSH-plugin](https://github.com/Alex-Yanggg/awesome-DSH-plugin) ⭐ 57 - Curated plugins, extensions, tools, and development resources for DSH.
- [Zhiyuan-Fan/Awesome-DeepSeek-Harness-Plugins](https://github.com/Zhiyuan-Fan/Awesome-DeepSeek-Harness-Plugins) ⭐ 55 - A curated list of DSH plugins.
- [libukai/awesome-deepseek-harness](https://github.com/libukai/awesome-deepseek-harness) ⭐ 47 - The ultimate guide to DSH: quickstart, resources, plugins, and toolkit.
- [Dominic789654/awesome-deepseek-harness](https://github.com/Dominic789654/awesome-deepseek-harness) ⭐ 38 - Categorized list of plugins, skills, MCP servers, orchestrators, and UIs.

## Contributing

PRs are welcome. Guidelines: repositories should be directly related to DeepSeek Harness, with a clear README and genuinely working functionality.

> Note: star counts are a snapshot taken on 2026-08-15 and are for reference only — this ecosystem moves fast.
