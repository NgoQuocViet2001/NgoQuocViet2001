# Ngo Quoc Viet

<div align="center">

![Ngo Quoc Viet - Community OSS Contributor](https://capsule-render.vercel.app/api?type=waving&height=220&color=0:111827,45:0F766E,100:0369A1&text=Ngo%20Quoc%20Viet&fontColor=FFFFFF&fontSize=48&fontAlignY=38&desc=Community%20OSS%20contributor%20for%20AI%20developer%20tooling%2C%20MCP%2C%20Codex%2C%20desktop%20apps%2C%20and%20DX%20reliability&descSize=15&descAlignY=58)

[![GitHub](https://img.shields.io/badge/GitHub-NgoQuocViet2001-111827?style=for-the-badge&logo=github&logoColor=white)](https://github.com/NgoQuocViet2001)
[![Portfolio](https://img.shields.io/badge/Portfolio-viet--ngo.hinadau.vip-0F766E?style=for-the-badge&logo=vercel&logoColor=white)](https://viet-ngo.hinadau.vip)
[![AWS SAA](https://img.shields.io/badge/AWS_SAA-861%2F1000-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)](https://www.credly.com/badges/b9822361-43e5-40f3-a590-a3c56a1a1d59)
[![Zalo](https://img.shields.io/badge/Zalo-0971933518-0068FF?style=for-the-badge&logo=zalo&logoColor=white)](https://zalo.me/0971933518)

</div>

## Community OSS Work

I spend a lot of my engineering time contributing practical fixes to public open-source projects, especially tools used by developers, AI coding agents, MCP servers, desktop apps, and OpenAI-compatible workflows.

My usual contribution style is small but real maintenance work: reproduce an issue, inspect the current behavior, ship a narrow fix, add regression coverage when possible, and stay around for review or follow-up fixes.

## Public OSS Snapshot

Public GitHub data for `NgoQuocViet2001`, refreshed 2026-06-24.

| Metric | Count | Notes |
| --- | ---: | --- |
| External merged PRs | 36 | Authored PRs merged into community-owned repositories. |
| Community repositories contributed to | 8 | `context-mode`, `openhuman`, `ds2api`, `Open-Generative-AI`, `RuView`, `Slidev`, `Spec Kit`, `Supertonic`. |
| External open PRs | 14 | Active public work still under maintainer review. |
| PR conversations with review/comment activity | 30 | Public PR threads where I participated in review, debugging, validation, or follow-up discussion. |
| Formal reviewed PRs | 6 | Public GitHub review records visible through GitHub search. |
| `mksglu/context-mode` merged PRs | 13 | Main current OSS focus. |
| `mksglu/context-mode` PR discussions | 13 | Review/comment activity in the project around Codex, Windows, docs, and MCP behavior. |

<div align="center">
  <img src="./assets/github-activity.svg" alt="Ngo Quoc Viet GitHub activity summary" width="900" />
</div>

## Core Maintainer-Level Focus: context-mode

[`mksglu/context-mode`](https://github.com/mksglu/context-mode) is my main OSS focus right now. I contribute as a core maintainer-level contributor for the Windows + Codex + MCP surface: dogfooding the project in real Codex sessions, fixing cross-platform issues, validating contributor changes, and sending follow-up patches when the docs or runtime drift.

Project signal: **18.1k+ stars**, **1.2k+ forks**, published on [npm](https://www.npmjs.com/package/context-mode).

| Area | Examples |
| --- | --- |
| Codex plugin reliability | Marketplace/plugin approval defaults, platform env propagation, Windows-safe plugin installs, Zed/Codex docs sync. |
| Windows execution | PowerShell, `pwsh`, `cmd`, Git Bash, WSL-bash fallback paths, symlink-restricted environments, junction-based tests. |
| MCP/runtime correctness | `ctx_execute` cwd behavior, cross-project attribution, fetch cache TTL, upgrade fallback safety. |
| Observability and diagnostics | Insight analytics totals, standalone Codex doctor status, plugin/server detection behavior. |
| Maintainer support | Review/comment activity, manual Windows + Codex validation, concise issue triage, follow-up patches after maintainer requests. |

## Community Contribution Highlights

| Project | Merged PRs | What I helped with |
| --- | ---: | --- |
| [mksglu/context-mode](https://github.com/mksglu/context-mode) | 13 | Codex/MCP reliability, Windows execution, plugin install behavior, analytics, cache, docs, and maintainer follow-up fixes. |
| [CJackHwang/ds2api](https://github.com/CJackHwang/ds2api) | 8 | OpenAI-compatible API behavior, streamed responses, citation replacement, tool output cleanup, Vercel sync, and file metadata routes. |
| [tinyhumansai/openhuman](https://github.com/tinyhumansai/openhuman) | 6 | Desktop OAuth/deep links, auth callback compatibility, runtime packaging, startup cleanup, and security hardening. |
| [Anil-matcha/Open-Generative-AI](https://github.com/Anil-matcha/Open-Generative-AI) | 4 | Local AI model storage, onboarding docs, WAN2GP endpoint fallback, and startup heartbeat feedback. |
| [ruvnet/RuView](https://github.com/ruvnet/RuView) | 2 | ESP32 swarm config validation and mesh-to-dashboard documentation. |
| [github/spec-kit](https://github.com/github/spec-kit) | 1 | Development extension agent symlink handling. |
| [slidevjs/slidev](https://github.com/slidevjs/slidev) | 1 | Monorepo sub-directory deployment route generation. |
| [supertone-inc/supertonic](https://github.com/supertone-inc/supertonic) | 1 | Multi-language CLI option documentation. |

## Recent Merged PRs

| Project | PR | Contribution | Merged |
| --- | --- | --- | --- |
| [mksglu/context-mode](https://github.com/mksglu/context-mode) | [#875](https://github.com/mksglu/context-mode/pull/875) | Synced the Zed `command.path` fix into the next README config so the documented editor setup matches the maintained command path. | 2026-06-24 |
| [tinyhumansai/openhuman](https://github.com/tinyhumansai/openhuman) | [#3800](https://github.com/tinyhumansai/openhuman/pull/3800) | Restored legacy `/auth` web callback compatibility for OAuth-style desktop login redirects, with route coverage. | 2026-06-22 |
| [mksglu/context-mode](https://github.com/mksglu/context-mode) | [#765](https://github.com/mksglu/context-mode/pull/765) | Pinned Claude `ctx_execute` execution to the session working directory and covered cross-project cwd behavior. | 2026-06-13 |
| [mksglu/context-mode](https://github.com/mksglu/context-mode) | [#778](https://github.com/mksglu/context-mode/pull/778) | Detected package-server runtime through `PI_CODING_AGENT` so plugin installs resolve the correct MCP server behavior. | 2026-06-04 |
| [slidevjs/slidev](https://github.com/slidevjs/slidev) | [#2562](https://github.com/slidevjs/slidev/pull/2562) | Used `BASE_URL` in slide path generation so monorepo sub-directory deployments resolve slide routes correctly. | 2026-06-03 |
| [mksglu/context-mode](https://github.com/mksglu/context-mode) | [#766](https://github.com/mksglu/context-mode/pull/766) | Made cross-project attribution shell setup portable across environments without relying on brittle shell assumptions. | 2026-06-02 |
| [mksglu/context-mode](https://github.com/mksglu/context-mode) | [#748](https://github.com/mksglu/context-mode/pull/748) | Avoided marketplace symlink sources on Windows so Codex plugin installs work under restricted symlink privileges. | 2026-06-01 |
| [github/spec-kit](https://github.com/github/spec-kit) | [#2554](https://github.com/github/spec-kit/pull/2554) | Fixed `--dev` extension agent symlinks so development extension installs link the expected agent files. | 2026-05-28 |
| [mksglu/context-mode](https://github.com/mksglu/context-mode) | [#722](https://github.com/mksglu/context-mode/pull/722) | Set platform environment for the Codex plugin MCP server so bundled runtime behavior matches the host platform. | 2026-05-26 |
| [Anil-matcha/Open-Generative-AI](https://github.com/Anil-matcha/Open-Generative-AI) | [#200](https://github.com/Anil-matcha/Open-Generative-AI/pull/200) | Showed local-AI startup heartbeat while models load so users see progress instead of a silent startup delay. | 2026-05-26 |
| [mksglu/context-mode](https://github.com/mksglu/context-mode) | [#709](https://github.com/mksglu/context-mode/pull/709) | Hardened Windows shell execution for PowerShell, `pwsh`, `cmd`, Git Bash, and WSL-bash fallback paths. | 2026-05-25 |
| [mksglu/context-mode](https://github.com/mksglu/context-mode) | [#706](https://github.com/mksglu/context-mode/pull/706) | Counted insight analytics KPI totals from uncapped aggregate queries instead of capped dashboard detail lists. | 2026-05-25 |
| [mksglu/context-mode](https://github.com/mksglu/context-mode) | [#705](https://github.com/mksglu/context-mode/pull/705) | Made `ctx_insight` CORS tests use Windows junctions when symlink privileges are unavailable. | 2026-05-25 |
| [mksglu/context-mode](https://github.com/mksglu/context-mode) | [#704](https://github.com/mksglu/context-mode/pull/704) | Added Codex marketplace MCP approval defaults and regression coverage, with manual Codex plugin validation. | 2026-05-25 |
| [tinyhumansai/openhuman](https://github.com/tinyhumansai/openhuman) | [#2572](https://github.com/tinyhumansai/openhuman/pull/2572) | Hardened RPC bearer token checks with constant-time comparison and prefix-match regression tests. | 2026-05-25 |

## Contribution Themes

- **AI developer tooling:** MCP servers, Codex plugin behavior, context optimization, local analytics, package-server detection, safe upgrade paths.
- **Windows-first reliability:** restricted execution policies, missing symlink privileges, shell compatibility, desktop deep links, OAuth callbacks, packaging quirks.
- **OpenAI-compatible systems:** routes, streaming behavior, uploaded file metadata, citation/reference markers, visible output cleanup.
- **Maintainer-friendly delivery:** narrow PRs, regression tests, concise validation notes, no broad rewrites when a small fix is enough.

## Personal Projects

I still maintain a few tools of my own, but my current profile is intentionally centered on community OSS contribution.

| Project | Focus |
| --- | --- |
| [codex-keyring](https://github.com/NgoQuocViet2001/codex-keyring) | Native multi-account manager for Codex with aliases, health checks, and failover support. |
| [codex-observatory](https://github.com/NgoQuocViet2001/codex-observatory) | Local Codex usage analytics, token trends, model breakdowns, and dashboard views. |
| [google-workspace-mcp](https://github.com/NgoQuocViet2001/google-workspace-mcp) | MCP server for structured Google Docs and Sheets extraction with image-aware output. |

## Engineering Background

Fullstack developer with nearly 4 years of experience across product and outsourced projects, including project-level Dev Lead responsibility in healthcare systems.

- Frontend/backend delivery with TypeScript, React, Vue, Node.js, C#, ASP.NET, Laravel, Python, Go, Rust, SQL.
- Project bootstrapping, source-base design, reusable components, code review, Git flow, mentoring, and internal training.
- AWS, Linux, Docker, Nginx, CI/CD, VPS deployment, staging/production support, and AI-assisted BA/QC/developer workflows.

## Stack

<p>
  <img src="https://skillicons.dev/icons?i=js,ts,nodejs,react,vue,nextjs,vite,tailwind,cs,dotnet,php,laravel,python,java,go,rust,mysql,postgres,mongodb,redis,aws,docker,nginx,linux,githubactions,git,github,figma,postman,vscode&perline=10" alt="Main development stack" />
</p>

![Codex](https://img.shields.io/badge/Codex-111827?style=flat-square&logo=openai&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-0F766E?style=flat-square)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Code Review](https://img.shields.io/badge/Code_Review-2563EB?style=flat-square)
![Windows DX](https://img.shields.io/badge/Windows_DX-0078D4?style=flat-square&logo=windows&logoColor=white)

## Contact

Open to OSS collaboration, maintainer support, developer tooling, automation, and practical fullstack/internal-tool work.

[Portfolio](https://viet-ngo.hinadau.vip) . [GitHub](https://github.com/NgoQuocViet2001) . [Zalo](https://zalo.me/0971933518) . [Facebook](https://www.facebook.com/ngoquocviet2001/)
