# Awesome DeepSeek Harness

[中文](README.md) | English

> A curated list of open-source projects, plugins, desktop clients, plugin marketplaces, and tutorials for DeepSeek Harness (DSH).

[DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness) (`dsh`) is an open-source agent harness released by DeepSeek on August 13, 2026. Its core philosophy is **"Everything is a Plugin"**, powered by the [Cordis](https://github.com/cordiverse/cordis) plugin framework, MIT licensed. It passed 80k stars within a day of release, and the `dsh-plugin` topic on GitHub already counts 1,400+ ecosystem repositories.

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
- [Integrations & Companion Tools](#integrations--companion-tools)
- [Tutorials & Learning Resources](#tutorials--learning-resources)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing)

## Official Resources

- [deepseek-ai/deepseek-harness](https://github.com/deepseek-ai/deepseek-harness) ⭐ 80.3k - The official repository. Currently in developer preview and iterating rapidly — expect breaking changes.
- [Official homepage](https://deepseek.com/harness) - deepseek.com/harness.
- [Docs directory](https://github.com/deepseek-ai/deepseek-harness/tree/master/docs) - Bilingual docs covering architecture, agent lifecycle, API gateway, and more.
- [Cordis](https://github.com/cordiverse/cordis) - The plugin framework underneath DSH; the technical foundation of "everything is a plugin".
- [dsh-plugin topic](https://github.com/topics/dsh-plugin) - The official plugin discovery mechanism: tag your plugin repo with `dsh-plugin`. 1,400+ repos so far.
- [GitHub Discussions](https://github.com/deepseek-ai/deepseek-harness/discussions) - Official feedback and discussion forum.
- [Discord community](https://discord.gg/Ycq5dCaS4) - Official Discord.

## Plugin Marketplaces & Discovery
- [dhicoc/dsh-reverse-skill](https://github.com/dhicoc/dsh-reverse-skill) - Complete reverse-skill pack (85 SKILL.md) as a DeepSeek Harness Cordis plugin: reverse engineering, authorized pentesting and security-research skill router.
- [AdamPlatin123/awesome-dsh-plugins](https://github.com/AdamPlatin123/awesome-dsh-plugins) ⭐ 625 - Plugin radar: automatically scans and discovers dsh plugin candidates; tested ones graduate into a curated directory.
- [awesome-dsh-plugin/awesome-dsh-plugin](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin) ⭐ 487 - A curated list of DSH plugins (English & Chinese).
- [bruc3van/awesome-dsh-plugin](https://github.com/bruc3van/awesome-dsh-plugin) ⭐ 54 - "Find the right plugin in 30 seconds": navigates by what problem a plugin solves and who it's for, not just a repo dump.
- [LaplaceYoung/oh-my-dsh](https://github.com/LaplaceYoung/oh-my-dsh) ⭐ 39 - A plugin ecosystem for DSH with 700+ plugins, registered only through extension seams without touching the agent-loop core.
- [OBdangshang07/DSH_Creative_Workshop](https://github.com/OBdangshang07/DSH_Creative_Workshop) ⭐ 38 - Steam-Workshop-inspired discovery, trust scoring, graph search, collections, and transactional install planning for DSH plugins.
- [vlln/plugin-registry](https://github.com/vlln/plugin-registry) ⭐ 28 - Ecosystem infrastructure: a thin browser console for managing repository plugins (zero patches) plus a `make-dsh-plugin` development guide skill.
- [bradeGithub/DSH-Plugins-Marketplace](https://github.com/bradeGithub/DSH-Plugins-Marketplace) ⭐ 14 - Browse, install, and update every `dsh-plugin`-tagged plugin with one click inside the DSH Web GUI.
- [hikariming/dshfind](https://github.com/hikariming/dshfind) ⭐ 12 - Learn DSH principles, plugin marketplace, and best practices.

## Desktop Clients

- [hust-open-atom-club/oh-dsh](https://github.com/hust-open-atom-club/oh-dsh) ⭐ 141 - One-stop community distribution: unified TUI, desktop, and Web UI experience with layered, one-step installation.
- [dataelement/dsh-desktop](https://github.com/dataelement/dsh-desktop) ⭐ 106 - Desktop app for DeepSeek Harness.
- [steven-kid/deepseek-harness-desktop](https://github.com/steven-kid/deepseek-harness-desktop) ⭐ 85 - Minimal desktop wrapper: cross-platform, zero-config, works out of the box.
- [turtle2209/Bigfish](https://github.com/turtle2209/Bigfish) ⭐ 69 - Third-party desktop client with a bundled Node runtime — double-click to run, desktop pet included.
- [myYangyunfan/dsh_desktop](https://github.com/myYangyunfan/dsh_desktop) ⭐ 62 - Windows desktop client bundling Node.js and the dsh CLI for one-click launch.
- [Ruler4396/dsh-launcher](https://github.com/Ruler4396/dsh-launcher) ⭐ 50 - Lightweight Windows launcher: silent autostart at logon plus a minimal WebView2 window.
- [ChisaAlter/Deepseek-Harness-Desktop](https://github.com/ChisaAlter/Deepseek-Harness-Desktop) ⭐ 31 - Electron desktop shell with themes, background images, and other personalization.
- [xiincs/deepseek-harness-desktop](https://github.com/xiincs/deepseek-harness-desktop) ⭐ 23 - Native Windows desktop app built on Tauri 2, hosting the dsh web service in a WebView with bundled Node.js.

## Terminal TUI

- [ccch1mneyyy/dsh-TUI](https://github.com/ccch1mneyyy/dsh-TUI) ⭐ 649 - Fills the gap of a missing official TUI: a Claude Code-style full-screen terminal plugin with streaming thoughts, double-Esc rewind, and a context progress bar. One-line npm install.
- [huiliyi37/dsh-tianshu-tui](https://github.com/huiliyi37/dsh-tianshu-tui) ⭐ 106 - Interactive terminal UI plugin that adds TDD and evidence-gate workflows on top of the official harness.

## Web UI Enhancements & Skins

- [zhu1090093659/dsh-web-ui](https://github.com/zhu1090093659/dsh-web-ui) ⭐ 1.3k - Plugin and skin collection: task board, git graph, right-side panel, remote mobile UI, pet, live token stats, and a skin center.
- [omdsh-dev/DSH-better-sidebar](https://github.com/omdsh-dev/DSH-better-sidebar) ⭐ 549 - A full workbench in the sidebar: file rendering/editing, terminal, Git, subagents, with third-party tab registration.
- [Small-tailqwq/dsh-deep-whale](https://github.com/Small-tailqwq/dsh-deep-whale) ⭐ 388 - "Deep-sea maid atelier" whale-girl skin series for the DSH Web UI.
- [Nagi-ovo/dsh-ads](https://github.com/Nagi-ovo/dsh-ads) ⭐ 265 - Parody plugin: 2005-era Chinese-web-style sidebar ads, in-feed ads, and corner popups (all assets fictional).
- [vlln/whale-girl](https://github.com/vlln/whale-girl) ⭐ 101 - QQ-pet-style desktop pet plugin: floats in the corner, draggable, feedable, playable.
- [omdsh-dev/dsh-at-file](https://github.com/omdsh-dev/dsh-at-file) ⭐ 92 - Codex-style `@file` mentions: search workspace files in the composer and attach their contents to prompts.
- [Nagi-ovo/dsh-visualize](https://github.com/Nagi-ovo/dsh-visualize) ⭐ 63 - Generative UI in conversation: the model draws interactive HTML cards directly into the chat stream, with streaming preview and sandboxed rendering.
- [omdsh-dev/dsh-genui](https://github.com/omdsh-dev/dsh-genui) ⭐ 56 - GenUI: interactive components — layouts, charts, forms, quizzes — rendered inline in assistant replies.

## Capability Plugins

- [liustack/modlens](https://github.com/liustack/modlens) ⭐ 1k - The first vision plugin for DSH: paste an image, get structured JSON evidence (OCR, layout, semantics). A vision bridge for any text-only coding agent.
- [Anionex/dsh-vision-toolkit](https://github.com/Anionex/dsh-vision-toolkit) ⭐ 269 - Vision tasks for text-only models: intent-aware image Q&A, long-screenshot OCR, UI restoration, grounding, and pixel diff.
- [NanmiCoder/dsh-agent-teams](https://github.com/NanmiCoder/dsh-agent-teams) ⭐ 187 - AgentTeams multi-agent collaboration plugin for DSH.
- [liustack/modsearch](https://github.com/liustack/modsearch) ⭐ 77 - The web plugin for DSH: ask the web or X, get structured JSON evidence back.
- [Lum1104/dsh-browser](https://github.com/Lum1104/dsh-browser) ⭐ 67 - Chrome sidebar extension that lets DSH operate your browser directly — no vision capabilities required.
- [icetomoyo/dsh_workflow](https://github.com/icetomoyo/dsh_workflow) ⭐ 49 - Upgrades one-shot multi-agent dispatch into a workflow layer that is generatable, savable, governable, observable, and resumable.
- [Anionex/dsh-turn-rewind](https://github.com/Anionex/dsh-turn-rewind) ⭐ 32 - Rewind conversation and workspace state, powered by a persistent Change Ledger.
- [csyangwen/dsh-memory-evolve](https://github.com/csyangwen/dsh-memory-evolve) ⭐ 30 - Plugin-only cross-session long-term memory and background self-evolution: five-track memory, skill self-evolution, todos, and scheduling — zero core modifications.
- [titanwings/dsh-automation](https://github.com/titanwings/dsh-automation) ⭐ 23 - Automation plugin: run coding tasks on schedule in fresh agent sessions, with timer management by user or agent.

## Integrations & Companion Tools

- [nexu-io/open-design](https://github.com/nexu-io/open-design) ⭐ 85.8k - Open-source Claude Design alternative: a local-first desktop app that turns coding agents into a design engine, supporting DSH among 20+ CLIs.
- [CherryHQ/cherry-studio](https://github.com/CherryHQ/cherry-studio) ⭐ 50.5k - AI productivity studio with unified access to frontier LLMs; tagged with `deepseek-harness` support.
- [titanwings/colleague-skill](https://github.com/titanwings/colleague-skill) ⭐ 21.7k - The viral "Digital Life" skill project, plugged into the dsh-plugin ecosystem.
- [Devin-AXIS/iPolloWork](https://github.com/Devin-AXIS/iPolloWork) ⭐ 3.8k - AI workspace that integrates DSH for subagent delegation, combining both plugin ecosystems in one workflow.
- [whiteguo233/OpenBiliClaw](https://github.com/whiteguo233/OpenBiliClaw) ⭐ 2.2k - Local-first self-evolving content discovery agent (Bilibili / Xiaohongshu / YouTube, etc.) with a dedicated [DSH plugin](https://github.com/whiteguo233/dsh-openbiliclaw).
- [xiufengsun/TokenTracker](https://github.com/xiufengsun/TokenTracker) ⭐ 1.3k - Local-first AI token usage and cost tracker covering 31 coding tools, DSH included.
- [yejiming/MuseAI](https://github.com/yejiming/MuseAI) ⭐ 525 - AI roleplay and story worlds, with DSH plugin support.
- [mnemon-dev/mnemon](https://github.com/mnemon-dev/mnemon) ⭐ 426 - Graph-based persistent memory for agents in a single binary, works with DSH.
- [PM-Shawn/Abu-Cowork](https://github.com/PM-Shawn/Abu-Cowork) ⭐ 321 - Open-source alternative to Claude Cowork: a local-first AI agent desktop app; DSH integration in progress.
- [huiliyi37/Tianshu-Tui](https://github.com/huiliyi37/Tianshu-Tui) ⭐ 215 - A standalone harness-engineered terminal coding agent runtime, deeply adapted for DeepSeek V4 with prefix-cache optimization.

## Tutorials & Learning Resources

- [alchaincyf/deepseek-harness-orange-book](https://github.com/alchaincyf/deepseek-harness-orange-book) ⭐ 338 - The "Orange Book": full system prompt, a 129-line boot checklist, and three raw session logs — first-hand findings not in the official docs. Free PDF/EPUB/HTML.
- [Electricitysheep/dsh-handbook](https://github.com/Electricitysheep/dsh-handbook) ⭐ 128 - A zero-to-one deep-dive handbook: installation, plugin development, performance tuning, field cases, and same-model multi-agent comparisons (Chinese & English PDF).
- [yanhua1010/dsh-harness-tutorial](https://github.com/yanhua1010/dsh-harness-tutorial) ⭐ 28 - How DSH works and how to build one: a Chinese tutorial implementing an AI agent from scratch (VitePress site + 8 demos + a mini-harness teaching project).
- [pingfanfan/hello-dsh](https://github.com/pingfanfan/hello-dsh) ⭐ 22 - Zero-to-plugin tutorial for understanding "everything is a plugin", with 22 Chinese skill examples.

## Other Awesome Lists

- [0xsline/awesome-deepseek-harness](https://github.com/0xsline/awesome-deepseek-harness) ⭐ 289 - Curated plugins, tools, and infrastructure from dsh-external/hub and the public `dsh-plugin` topic.
- [Alex-Yanggg/awesome-DSH-plugin](https://github.com/Alex-Yanggg/awesome-DSH-plugin) ⭐ 45 - Curated plugins, extensions, tools, and development resources for DSH.
- [Zhiyuan-Fan/Awesome-DeepSeek-Harness-Plugins](https://github.com/Zhiyuan-Fan/Awesome-DeepSeek-Harness-Plugins) ⭐ 34 - A curated list of DSH plugins.
- [Dominic789654/awesome-deepseek-harness](https://github.com/Dominic789654/awesome-deepseek-harness) ⭐ 24 - Categorized list of plugins, skills, MCP servers, orchestrators, and UIs.
- [libukai/awesome-deepseek-harness](https://github.com/libukai/awesome-deepseek-harness) ⭐ 22 - The ultimate guide to DSH: quickstart, resources, plugins, and toolkit.

## Contributing

PRs are welcome. Guidelines: repositories should be directly related to DeepSeek Harness, with a clear README and genuinely working functionality.

> Note: star counts are a snapshot taken on 2026-08-14 and are for reference only — this ecosystem moves fast.
