<h1 align="center">Leonardo Xavier Rodrigues</h1>

<p align="center">
  Backend and full-stack developer focused on APIs, realtime systems, business platforms, native macOS apps, and game server tooling.
</p>

<p align="center">
  <a href="https://github.com/leonardoxr?tab=repositories">Repositories</a>
  ·
  <a href="https://github.com/leonardoxr/dsh-plugins">DSH Plugins</a>
  ·
  <a href="https://github.com/leonardoxr/GrowattMenuBar">GrowattMenuBar</a>
  ·
  <a href="https://github.com/leonardoxr/IP-Camera">IP Camera Viewer</a>
  ·
  <a href="https://github.com/leonardoxr/PhraseCue">PhraseCue</a>
  ·
  <a href="https://github.com/leonardoxr/iThinkQ">iThinkQ</a>
  ·
  <a href="https://github.com/leonardoxr/MCSR_Ranked_Companion">MCSR Companion</a>
  ·
  <a href="mailto:lxavier.dev@outlook.com">Email</a>
</p>

---

I build practical software across APIs, relational databases, web platforms, internal tools, client-facing systems, native macOS utilities, and game server infrastructure.

I care about software that feels reliable in daily use: clear interfaces, predictable behavior, maintainable architecture, and enough technical depth under the hood to support real product needs.

## What I Work On

- **Backend development** with PHP, Laravel, Yii2, MySQL, MSSQL, REST APIs, and integrations for internal and external systems.
- **Full-stack web products** with TypeScript, React, Next.js, PHP, and relational databases.
- **Native macOS apps** with Swift and SwiftUI, including device control, IP camera viewing, discovery flows, streaming, and menu bar experiences.
- **AI-assisted development tooling** around DeepSeek Harness: plugins, aggregate bundles, usage dashboards, subagent routing, and workspace automation for AI coding agents.
- **Game server infrastructure** with REST APIs, WebSocket communication, database-backed tooling, C++ networking, and plugin development.
- **Systems and simulation work** in C and C++, including numerical methods, physics-style modeling, and lower-level architecture.

## Professional Experience

Since 2018, I have built and maintained web systems, APIs, databases, and tools for different products and teams. My work has included requirements gathering with clients, backend development with PHP/Laravel/Yii2, MySQL and MSSQL database work, API integrations, performance and security testing, and support for other developers.

I have also worked on game-related systems, including backend APIs for support workflows and C++ game-server infrastructure involving networking, database integration, and scripting workflows.

## Featured Projects

| Project | Focus | Stack |
| --- | --- | --- |
| [PhraseCue](https://github.com/leonardoxr/PhraseCue) | Local-first podcast search player for macOS, with podcast import, transcript indexing, timestamped search, playback from matching moments, transcription backend setup, and beta release packaging. | Swift, SwiftUI, AVFoundation, SQLite FTS5, GRDB, macOS |
| [MCSR_Ranked_Companion](https://github.com/leonardoxr/MCSR_Ranked_Companion) | Public companion app for MCSR Ranked players, with player stats, match history, leaderboards, comparisons, live match views, playoffs, records, API validation, and desktop packaging. | TypeScript, Next.js, React, Tailwind CSS, TanStack Query, Zustand, Tauri |
| [IP-Camera](https://github.com/leonardoxr/IP-Camera) | Native macOS IP camera viewer with discovery, RTSP bridging, PTZ controls, saved views, and AirPlay-capable view casting. | Swift, SwiftUI, RTSP, FFmpeg, ONVIF |
| [GrowattMenuBar](https://github.com/leonardoxr/GrowattMenuBar) | Native macOS menu bar app that monitors a local Growatt solar inverter directly over Modbus TCP, surfacing live production data without depending on the vendor cloud. | Swift, SwiftUI, Modbus TCP, macOS |
| [iThinkQ](https://github.com/leonardoxr/iThinkQ) | Native macOS app for controlling LG ThinQ devices. | Swift, SwiftUI, macOS |

## AI & Agent Development

A growing share of my work goes into building *on top of* AI coding agents — not just using them daily, but extending them and wiring them into real products and engineering workflows.

- **DeepSeek Harness platform plugins** — I maintain an open ecosystem of web plugins and aggregate bundles for [DeepSeek Harness](https://github.com/leonardoxr/deepseek-harness), an everything-is-a-plugin AI coding agent platform: usage dashboards, complexity-routed subagent delegation, workspace Git integration, native shells, and more (full catalog below).
- **Private Claude Code plugin suites** — for professional client environments I build internal-only Claude Code plugin collections: custom tools with typed schemas, guardrails around sensitive workflows, task automation, and preferences surfaced directly in the agent UI. The repositories stay private by design; the engineering discipline mirrors the public suite — lifecycle-safe registration, schema-driven configuration, hot-reload development, and reviewable changes.
- **Agent-native engineering** — Claude Code and Codex are part of my daily workflow for codebase exploration, implementation planning, refactoring, debugging, documentation, and prototyping, while architecture, product decisions, testing, and final review stay owned by engineers.

## DeepSeek Harness Plugins & Bundles

Most of my current engineering goes into [DeepSeek Harness](https://github.com/leonardoxr/deepseek-harness), an AI coding agent platform where every capability ships as a plugin. I maintain a suite of web plugins for it, collected below. This catalog refreshes automatically from the GitHub API, so newly published plugins and updated descriptions appear here on their own.

<!-- repo-catalog:start -->
<!-- Generated by scripts/generate-repos.mjs -- do not edit by hand. -->

### 📦 [dsh-plugins](https://github.com/leonardoxr/dsh-plugins) — the all-in-one bundle

One install wires up the whole collection: this repository publishes **dsh-all-in-one**, an aggregate bundle that mounts every plugin below as a single layer, keeping each plugin’s canonical row ID so existing config overrides survive the migration.

```sh
dsh plugin --profile <name> add dsh-all-in-one
```

### 🔌 Plugins (12)

| Plugin | What it does | Language |
| --- | --- | --- |
| [dsh-companion](https://github.com/leonardoxr/dsh-companion) | Read-only workspace and session JSON API plugin for DeepSeek Harness native clients. | JavaScript |
| [dsh-auto-chat-titles](https://github.com/leonardoxr/dsh-auto-chat-titles) | Semantic, configurable chat titles for DeepSeek Harness | TypeScript |
| [dsh-native](https://github.com/leonardoxr/dsh-native) | Native desktop and iOS shell for trusted HTTPS web apps, with saved servers and first-class DeepSeek Harness support. | JavaScript |
| [dsh-claude-usage](https://github.com/leonardoxr/dsh-claude-usage) | Anthropic Claude plan usage indicator for DeepSeek Harness | TypeScript |
| [dsh-codex-usage](https://github.com/leonardoxr/dsh-codex-usage) | OpenAI Codex plan usage indicator for DeepSeek Harness | TypeScript |
| [dsh-image-preview](https://github.com/leonardoxr/dsh-image-preview) | Inline read_image previews for DeepSeek Harness | TypeScript |
| [dsh-harness-updater](https://github.com/leonardoxr/dsh-harness-updater) | Claude Code / Codex CLI update detection, prompting, and one-click channel updates for DeepSeek Harness | TypeScript |
| [dsh-workspace-git](https://github.com/leonardoxr/dsh-workspace-git) | DeepSeek Harness plugin for cloning Git repositories as workspaces | TypeScript |
| [dsh-status-bar-config](https://github.com/leonardoxr/dsh-status-bar-config) | Configurable conversation statistics row for DeepSeek Harness | TypeScript |
| [dsh-routed-subagent](https://github.com/leonardoxr/dsh-routed-subagent) | Complexity-routed subagent delegation for DeepSeek Harness: the model picks the runtime tier per task. | TypeScript |
| [dsh-plugin-manager](https://github.com/leonardoxr/dsh-plugin-manager) | Safe loopback-only Web UI for managing DeepSeek Harness profile plugins | TypeScript |
| [dsh-coding-tools](https://github.com/leonardoxr/dsh-coding-tools) | Secure bounded coding tools for DeepSeek Harness | TypeScript |

### 🍍 Related forks

- [DSH-better-sidebar](https://github.com/leonardoxr/DSH-better-sidebar) — 开放的侧边栏底座，支持三方拓展注册新侧边栏页面。内置文件渲染编辑/终端/侧边对话/Git/子代理页面 ｜ Open sidebar foundation, supports third-party extensions to register new sidebar pages. Built-in file rendering/editing, terminal, side chat, Git, and sub-agent pages.
- [deepseek-harness](https://github.com/leonardoxr/deepseek-harness) — DeepSeek Harness: Everything is a Plugin.

---

_Auto-refreshed 2026-09-07 UTC from the GitHub API by [.github/workflows/update-repos.yml](https://github.com/leonardoxr/leonardoxr/blob/main/.github/workflows/update-repos.yml)._

<!-- repo-catalog:end -->






## Hobby and Community Projects

I also build tools around games and communities I enjoy. These projects are useful portfolio pieces because they show practical Java plugin work, desktop app packaging, API integration, realtime UI, game-server tooling, and performance-focused engineering outside client work.

| Project | Focus | Stack |
| --- | --- | --- |
| [hytale-api](https://github.com/leonardoxr/hytale-api) | Secure REST and WebSocket API plugin for Hytale game servers, focused on server control, realtime communication, and external tooling. | Java, REST, WebSocket |
| [hytale-dashboard](https://github.com/leonardoxr/hytale-dashboard) | Real-time admin dashboard for Hytale game servers, built as a browser-based companion for server monitoring and management. | TypeScript, Next.js, React |
| [jingle-e-counter-plugin](https://github.com/leonardoxr/jingle-e-counter-plugin) | Jingle plugin for Minecraft speedrunning that pairs a thin game window with a zoomed realtime entity counter, configurable capture settings, persistent options, and a hotkey-driven workflow. | Java, Gradle, Swing, JNA, Windows GDI/User32, Jingle plugin API |
| [jingle-ez-nav-helper-plugin](https://github.com/leonardoxr/jingle-ez-nav-helper-plugin) | Jingle navigation helper that integrates with Ninjabrain Bot, showing stronghold direction, distance, coordinate tracking, dimension-aware conversion, and configurable API settings. | Java, Gradle, Swing, REST API integration, navigation math |

## Public Forks

I also keep public forks of projects that help me explore tooling, architecture, and lower-level engineering ideas.

- [t3code](https://github.com/leonardoxr/t3code) - a fork I use while studying and adapting AI-assisted coding workflows, developer tooling, and TypeScript monorepo patterns.
- [bgfx](https://github.com/leonardoxr/bgfx) - a fork of the cross-platform rendering library that I use as a reference for graphics architecture, rendering backends, and C++ systems design.

## Featured Private Projects

A significant part of my work lives in private repositories. I keep client context, source code, infrastructure details, and product-specific logic private, but these summaries show the domains and technical skills behind that work.

| Project Type | What I Worked On | Skills Demonstrated |
| --- | --- | --- |
| Healthcare management platform | Contributions across a private healthcare system, including frontend workflows, backend services, shared UI components, clinical worklists, viewer/editor flows, and product polish. | Angular, Node.js, Express, TypeScript, MySQL, Prisma, Sequelize, Playwright, Vitest, healthcare workflows |
| Recruitment and job platform systems | PHP-based job search and recruitment platforms, including backend features, database work, frontend maintenance, and production support. | PHP, Yii2-style MVC, MySQL, JavaScript, CSS, HTML, recruitment workflows |
| SaaS and internal web platforms | Backend systems for dashboards, business workflows, search/filtering, user-facing forms, and operational tools. | PHP, Laravel, Yii2, MySQL, API design, data modeling |
| Client-facing systems | Requirements gathering, backend implementation, maintenance, and support for systems used by real clients and teams. | Product thinking, communication, reliability, iterative delivery |
| Game support platform | Backend API work for an integrated support system connected to a game environment. | REST APIs, integrations, backend architecture, production support |
| Game server systems | Systems around networking, persistence, databases, and scripting workflows for C++ game-server infrastructure. | C++, networking, MSSQL/MySQL, Python scripting, systems design |
| Automation and AI-assisted tools | Prototypes and tools that automate workflows, organize information, and speed up product development with AI-assisted coding workflows. | TypeScript, backend services, workflow design, Claude Code, Codex, t3code |

## UFRGS School Projects

Before moving fully into software development, I studied seven of ten semesters of Engineering Physics at the Federal University of Rio Grande do Sul (UFRGS). That was where I first became deeply involved with programming, and I eventually chose to move into software development because I genuinely enjoyed building things with code. During that period, I worked on small C projects focused on numerical methods, simulation, and computational physics.

- [onda1d-leapfrog](https://github.com/leonardoxr/onda1d-leapfrog) - 1D wave simulation using the leapfrog method.
- [onda2d-leapfrog](https://github.com/leonardoxr/onda2d-leapfrog) - 2D wave simulation using the leapfrog method.
- [deriva-lax](https://github.com/leonardoxr/deriva-lax) - advection/drift numerical modeling with the Lax method.
- [difusao-estacionario](https://github.com/leonardoxr/difusao-estacionario) - stationary diffusion modeling.
- [radiacao-estacionaria](https://github.com/leonardoxr/radiacao-estacionaria) - stationary radiation modeling.
- [interacao-particulas](https://github.com/leonardoxr/interacao-particulas) - particle interaction simulation.
- [particulas-em-caixa](https://github.com/leonardoxr/particulas-em-caixa) - random particle placement inside a box.
- [dinamica-nmolas](https://github.com/leonardoxr/dinamica-nmolas) - dynamics of coupled spring systems.
- [dilema-prisioneiro](https://github.com/leonardoxr/dilema-prisioneiro) - computational model of the prisoner's dilemma.

## Technical Toolkit

**Languages:** PHP, TypeScript, Swift, Java, C, C++, R  
**Backend:** Laravel, Yii2, Node.js, Express, REST APIs, WebSockets, MySQL, MSSQL, Prisma, Sequelize  
**Frontend:** Angular, React, Next.js, SwiftUI  
**Testing and QA:** Playwright, Vitest, Jest, visual regression checks, browser-based debugging  
**Native and Systems:** macOS development, RTSP, FFmpeg, ONVIF, Modbus TCP, numerical methods, networking  
**AI-assisted engineering:** DeepSeek Harness plugin and bundle development; Claude Code, Codex, and t3code workflows for codebase exploration, implementation planning, refactoring, debugging, documentation, and faster prototyping  
**Workflow:** Git, GitHub, requirements analysis, team support, iterative prototyping, product-focused engineering, human review of AI-generated changes

I use AI coding tools as part of my daily engineering workflow, especially for navigating large codebases, comparing implementation approaches, generating first drafts, reviewing changes, writing documentation, and speeding up repetitive development tasks. On larger private projects, I use Claude Code, Codex, and t3code-style workflows heavily while still treating architecture, product decisions, testing, and final code review as engineering responsibilities.

## Education and Languages

**Degree:** Analysis and Systems Development  
**UFRGS:** Engineering Physics, 7 of 10 semesters completed before moving fully into software development  
**Languages:** Portuguese native, English advanced, French basic

## Current Direction

Right now I am especially interested in backend platforms, realtime interfaces, native macOS software, connected-device tooling, AI agent ecosystems, and infrastructure for games and creator-focused products. I like projects where the interface looks simple because the hard engineering is handled carefully behind it.

## Contact

For professional opportunities or technical conversations, reach me at [lxavier.dev@outlook.com](mailto:lxavier.dev@outlook.com).

---

<p align="center">
  Building useful software, learning in public, and turning rough ideas into working products.
</p>
