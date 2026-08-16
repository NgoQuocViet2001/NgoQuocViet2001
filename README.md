<div align="center">

![Ngo Quoc Viet — open-source adventurer](./assets/rpg-hero.svg)

[![GitHub](https://img.shields.io/badge/GitHub-NgoQuocViet2001-183143?style=for-the-badge&logo=github&logoColor=white)](https://github.com/NgoQuocViet2001)
[![Portfolio](https://img.shields.io/badge/Portfolio-viet--ngo.hinadau.vip-315A83?style=for-the-badge&logo=vercel&logoColor=white)](https://viet-ngo.hinadau.vip)
[![AWS SAA](https://img.shields.io/badge/AWS_SAA-861%2F1000-F0A928?style=for-the-badge&logo=amazonaws&logoColor=white)](https://www.credly.com/badges/b9822361-43e5-40f3-a590-a3c56a1a1d59)
[![Zalo](https://img.shields.io/badge/Zalo-0971933518-4C86B4?style=for-the-badge&logo=zalo&logoColor=white)](https://zalo.me/0971933518)

</div>

## 🧙 Player Profile

I'm **Ngo Quoc Viet**, a fullstack engineer focused on practical open-source maintenance. I use reproducible diagnostics, test evidence, and agent-assisted implementation to turn concrete upstream issues into narrow, reviewable patches.

| Character stat | Current build |
| --- | --- |
| **Class** | Fullstack Engineer / OSS Contributor |
| **Experience** | Nearly 4 years across product and outsourced projects |
| **Party role** | Project-level Dev Lead experience in healthcare systems |
| **Main quests** | Developer platforms, AI tooling, MCP, desktop apps, Windows DX |
| **Play style** | Reproduce the issue → ship a narrow fix → add regression coverage → follow through on review |

My favorite contributions are the ones maintainers can immediately use: broken runtime paths, cross-platform bugs, stale setup flows, incorrect API behavior, missing safety checks, and tests that prevent the same regression from returning.

## 📊 Adventure Log

Public contribution data for [`NgoQuocViet2001`](https://github.com/NgoQuocViet2001), refreshed **2026-08-16**. The merged count covers public PRs submitted from this account and accepted into repositories it does not own during the preceding 12 months.

<div align="center">
  <img src="./assets/github-activity.svg" alt="Retro RPG board showing 71 merged pull requests across 29 community repositories and 60 active pull requests" width="1200" />
</div>

| Stat | Total | Meaning |
| --- | ---: | --- |
| **Merged quests** | **71** | External PRs merged by community maintainers in the last 12 months |
| **Worlds visited** | **29** | Community repositories with at least one merged contribution |
| **Active quests** | **60** | External PRs currently open for maintainer review |

## ⚔️ Latest Quests Cleared

The most recent merges, newest first. Earlier merged work is summarized in the Guild History table below.

| Project | PR | Quest result | Merged |
| --- | --- | --- | --- |
| [pi-web](https://github.com/agegr/pi-web) | [#502](https://github.com/agegr/pi-web/pull/502) | Forwards `SIGINT` and `SIGTERM` from the wrapper to the Next.js child, allows a bounded grace period, then force-stops the child while preserving conventional exit statuses. | 2026-08-15 |
| [t3code](https://github.com/pingdotgg/t3code) | [#3929](https://github.com/pingdotgg/t3code/pull/3929) | Restores the `CLAUDE.md` symlink target to exactly `AGENTS.md`, removing a trailing newline that made macOS and Linux resolve the link as missing. | 2026-08-15 |
| [OpenCADStudio](https://github.com/HakanSeven12/OpenCADStudio) | [#770](https://github.com/HakanSeven12/OpenCADStudio/pull/770) | Allows case-only layer renames in the case-insensitive layer table and updates the active layer and document header when the current layer is renamed. | 2026-08-15 |
| [OmniWM](https://github.com/BarutSRB/OmniWM) | [#579](https://github.com/BarutSRB/OmniWM/pull/579) | Documents the 15 public CLI command paths missing from the IPC and CLI reference, covering focus, column, consume/expel, and system-stat commands. | 2026-08-15 |
| [drawDB](https://github.com/drawdb-io/drawdb) | [#1105](https://github.com/drawdb-io/drawdb/pull/1105) | Resolves foreign keys against the table currently being parsed so self-referencing relationships survive MySQL, MariaDB, PostgreSQL, SQLite, and Oracle imports. | 2026-08-15 |
| [Pake](https://github.com/tw93/Pake) | [#1352](https://github.com/tw93/Pake/pull/1352) | Defers `sharp` and `icon-gen` loading until icon processing, so `pake --version` no longer depends on native image dependencies loading successfully. | 2026-08-15 |
| [OpenPencil](https://github.com/ZSeven-W/openpencil) | [#215](https://github.com/ZSeven-W/openpencil/pull/215) | Forwards every positional node ID to `op read-nodes` in argument order instead of silently keeping only the first. | 2026-08-15 |
| [GeoLibre](https://github.com/opengeos/GeoLibre) | [#1900](https://github.com/opengeos/GeoLibre/pull/1900) | Projects WGS84 input to Web Mercator before the multiple-ring-buffer WASM call so planar buffer distances are applied in the units the algorithm expects. | 2026-08-14 |
| [Agent Skills](https://github.com/addyosmani/agent-skills) | [#473](https://github.com/addyosmani/agent-skills/pull/473) | Requires one grader result per declared expectation and rejects pass/fail totals that disagree with the individual results, closing a path where evals passed ungraded. | 2026-08-14 |
| [NeMo Switchyard](https://github.com/NVIDIA-NeMo/Switchyard) | [#422](https://github.com/NVIDIA-NeMo/Switchyard/pull/422) | Normalizes nested JSON metadata strings like flat headers so a whitespace-only high-priority value falls back instead of becoming a whitespace identity. | 2026-08-14 |
| [text-to-cad](https://github.com/earthtojake/text-to-cad) | [#244](https://github.com/earthtojake/text-to-cad/pull/244) | Retries only Windows SMB sharing violations during the atomic GLB rename with bounded backoff, while other replace errors still propagate immediately. | 2026-08-14 |
| [App Store Connect CLI](https://github.com/rorkai/App-Store-Connect-CLI) | [#2008](https://github.com/rorkai/App-Store-Connect-CLI/pull/2008) | Rejects trailing positional arguments for `builds add-groups` with a usage error before authentication or any API request. | 2026-08-14 |
| [Atlas](https://github.com/pacifio/atlas) | [#159](https://github.com/pacifio/atlas/pull/159) | Clears the turn epoch only on successful completion so late assistant output still reaches the transcript, keeping stale-event protection for cancelled and failed turns. | 2026-08-14 |
| [archify](https://github.com/tt-a1i/archify) | [#73](https://github.com/tt-a1i/archify/pull/73) | Rejects `--quality` without a value instead of exiting successfully on the default profile, covering the bare, followed-by-option, and `--quality=` forms. | 2026-08-14 |
| [GitHub Spec Kit](https://github.com/github/spec-kit) | [#4111](https://github.com/github/spec-kit/pull/4111) | Validates non-string workflow step types before registry lookup so malformed YAML produces an actionable error instead of an unhashable-type traceback. | 2026-08-14 |
| [zmx](https://github.com/neurosnap/zmx) | [#237](https://github.com/neurosnap/zmx/pull/237) | Lets a bare `*` build an empty-prefix matcher so the documented "target every session" form works, with scoped wildcards and prefix validation unchanged. | 2026-08-14 |

## 🏰 Guild History

| Community project | Merged quests | Contribution territory |
| --- | ---: | --- |
| [mksglu/context-mode](https://github.com/mksglu/context-mode) | **13** | Codex/MCP reliability, Windows shells, plugin installs, analytics, cache behavior, docs, and regression coverage |
| [CJackHwang/ds2api](https://github.com/CJackHwang/ds2api) | **8** | OpenAI-compatible routes, streaming, citations, tool output, Vercel sync, and file metadata |
| [tinyhumansai/openhuman](https://github.com/tinyhumansai/openhuman) | **8** | Desktop OAuth, deep links, packaging, startup cleanup, RPC security, AppImage release safety, and Windows contributor setup |
| [Anil-matcha/Open-Generative-AI](https://github.com/Anil-matcha/Open-Generative-AI) | **5** | Local AI model storage, onboarding, endpoint fallback, startup feedback, and reproducible setup |
| [slidevjs/slidev](https://github.com/slidevjs/slidev) | **5** | Base-path routing, reactive frontmatter, addon preprocessing, Cypress lifecycle cleanup, and export-local navigation |
| [github/spec-kit](https://github.com/github/spec-kit) | **4** | Development agent symlinks, safe Kiro multi-install behavior, authentication host matching, and workflow step-type validation |
| [Crosstalk-Solutions/project-nomad](https://github.com/Crosstalk-Solutions/project-nomad) | **2** | Offline content download reliability and benchmark startup correctness |
| [DayuanJiang/next-ai-draw-io](https://github.com/DayuanJiang/next-ai-draw-io) | **2** | MCP diagram edit consistency, stale-state protection, and multi-page export preservation |
| [drawdb-io/drawdb](https://github.com/drawdb-io/drawdb) | **2** | Clipboard schema validation and self-referencing foreign keys in SQL imports |
| [jdx/mise](https://github.com/jdx/mise) | **2** | Filesystem-safe install linking and portable generated bootstrap paths |
| [ruvnet/RuView](https://github.com/ruvnet/RuView) | **2** | ESP32 swarm configuration validation and mesh-to-dashboard documentation |

### First clears

Community repositories with one merged contribution so far:

| Community project | Contribution territory |
| --- | --- |
| [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) | Eval grader-result validation and summary integrity |
| [agegr/pi-web](https://github.com/agegr/pi-web) | Wrapper process lifecycle, signal forwarding, and exit statuses |
| [BarutSRB/OmniWM](https://github.com/BarutSRB/OmniWM) | Complete public CLI and IPC command reference |
| [earthtojake/text-to-cad](https://github.com/earthtojake/text-to-cad) | Windows SMB rename resilience during CAD artifact writes |
| [HakanSeven12/OpenCADStudio](https://github.com/HakanSeven12/OpenCADStudio) | Case-insensitive layer rename correctness |
| [logto-io/logto](https://github.com/logto-io/logto) | Tenant initialization error observability |
| [neurosnap/zmx](https://github.com/neurosnap/zmx) | Session wildcard matching in the socket parser |
| [NVIDIA-NeMo/Switchyard](https://github.com/NVIDIA-NeMo/Switchyard) | Nested protocol metadata normalization and header precedence |
| [opengeos/GeoLibre](https://github.com/opengeos/GeoLibre) | Geographic-to-planar projection for buffer processing |
| [pacifio/atlas](https://github.com/pacifio/atlas) | Agent turn epoch handling and late transcript events |
| [paperless-ngx/paperless-ngx](https://github.com/paperless-ngx/paperless-ngx) | Sanity-check data correctness and regression coverage |
| [pingdotgg/t3code](https://github.com/pingdotgg/t3code) | Cross-platform repository symlink integrity |
| [rorkai/App-Store-Connect-CLI](https://github.com/rorkai/App-Store-Connect-CLI) | CLI argument validation before authentication |
| [supertone-inc/supertonic](https://github.com/supertone-inc/supertonic) | Multi-language CLI option documentation |
| [tt-a1i/archify](https://github.com/tt-a1i/archify) | CLI flag-value validation and packaged artifact freshness |
| [tw93/Pake](https://github.com/tw93/Pake) | CLI startup independence from native image dependencies |
| [withastro/astro](https://github.com/withastro/astro) | Page-directory boundary correctness and regression coverage |
| [ZSeven-W/openpencil](https://github.com/ZSeven-W/openpencil) | CLI positional argument forwarding |

## 🔥 Active Quest Queue

Some of the current work waiting for maintainer review:

| Project | PR | Quest in progress |
| --- | --- | --- |
| [Neovim](https://github.com/neovim/neovim) | [#41299](https://github.com/neovim/neovim/pull/41299) | Report only implemented kitty keyboard flags from `:terminal`, preserving correct set/reset behavior and legacy input. |
| [pnpm](https://github.com/pnpm/pnpm) | [#13900](https://github.com/pnpm/pnpm/pull/13900) | Preserve existing semver range operators when updates resolve to prerelease versions in both TypeScript and Rust implementations. |
| [Vite](https://github.com/vitejs/vite) | [#23256](https://github.com/vitejs/vite/pull/23256) | Close config bundles in failure paths so rejected generation releases plugin and native resources. |
| [Vite](https://github.com/vitejs/vite) | [#22941](https://github.com/vitejs/vite/pull/22941) | Add Rollup-compatible `onLog` hooks to the dev plugin container, including filtering, re-emission, ordering, and lazy-log coverage. |
| [Poetry](https://github.com/python-poetry/poetry) | [#11014](https://github.com/python-poetry/poetry/pull/11014) | Parse the generated extension wheel filename instead of assuming the build backend picks the first supported tag. |
| [manim](https://github.com/3b1b/manim) | [#2502](https://github.com/3b1b/manim/pull/2502) | Search manual curves over 0–1 proportions rather than the axes x range, so graph point lookup works on non-unit ranges. |
| [bat](https://github.com/sharkdp/bat) | [#3889](https://github.com/sharkdp/bat/pull/3889) | Escape Unicode bidi and zero-width format controls in terminal metadata while keeping ordinary Unicode unchanged. |
| [LocalSend](https://github.com/localsend/localsend) | [#3303](https://github.com/localsend/localsend/pull/3303) | Reject unexpected prepare-upload file IDs instead of panicking and leaving the CLI transfer UI stuck. |
| [Catch2](https://github.com/catchorg/Catch2) | [#3175](https://github.com/catchorg/Catch2/pull/3175) | Add opt-in relocatable paths for PRE_TEST discovery across single- and multi-config CMake generators. |
| [Astro](https://github.com/withastro/astro) | [#17694](https://github.com/withastro/astro/pull/17694) | Require a directory boundary when classifying MDX pages so `src/pages-old` no longer receives page-only charset injection. |
| [Slidev](https://github.com/slidevjs/slidev) | [#2704](https://github.com/slidevjs/slidev/pull/2704) | Return 404 for out-of-range slide patches so a stale editor save cannot dereference a missing slide and stop the dev server. |
| [Slidev](https://github.com/slidevjs/slidev) | [#2703](https://github.com/slidevjs/slidev/pull/2703) | Default manual setup to npm when `create-slidev` runs without a detectable package manager. |
| [Visual Studio Code](https://github.com/microsoft/vscode) | [#325925](https://github.com/microsoft/vscode/pull/325925) | Propagate real `asExternalUri` resolver failures while preserving the normal unhandled-HTTP fallback. |
| [Visual Studio Code](https://github.com/microsoft/vscode) | [#325897](https://github.com/microsoft/vscode/pull/325897) | Enable the extension-host inspector before launching the debug flow. |
| [RAGFlow](https://github.com/infiniflow/ragflow) | [#18292](https://github.com/infiniflow/ragflow/pull/18292) | Classify CLI benchmark responses by envelope code as well as HTTP status so failed calls stop inflating the success count. |
| [Text-Grab](https://github.com/TheJoeFin/Text-Grab) | [#670](https://github.com/TheJoeFin/Text-Grab/pull/670) | Apply Latin character correction only when the selected capture language is Latin-based, across every OCR path. |
| [SQLBot](https://github.com/dataease/SQLBot) | [#1323](https://github.com/dataease/SQLBot/pull/1323) | Keep the standard Hive `DESCRIBE` fields while ignoring trailing driver-specific columns returned by ArgoDB. |
| [witr](https://github.com/pranshuparmar/witr) | [#231](https://github.com/pranshuparmar/witr/pull/231) | Detect Windows listeners by their zero-port remote endpoint so localized `netstat` state names are no longer dropped. |

## 🎒 Inventory / Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=js,ts,nodejs,react,vue,nextjs,vite,tailwind,cs,dotnet,php,laravel,python,java,go,rust,mysql,postgres,mongodb,redis,aws,docker,nginx,linux,githubactions,git,github,figma,postman,vscode&perline=10" alt="Ngo Quoc Viet's development stack" />
</p>

| Inventory slot | Equipped tools |
| --- | --- |
| **Frontend** | JavaScript, TypeScript, React, Vue, Next.js, Vite, Tailwind CSS |
| **Backend** | Node.js, C#, ASP.NET, PHP, Laravel, Python, Java, Go, Rust |
| **Data stores** | MySQL, PostgreSQL, MongoDB, Redis |
| **Infrastructure** | AWS, Linux, Docker, Nginx, CI/CD, GitHub Actions, VPS operations |
| **AI developer tooling** | Codex, MCP, Claude Code, OpenAI-compatible APIs, agent workflows |
| **Product toolkit** | Git, GitHub, Figma, Postman, VS Code |

## 🧭 Preferred Quest Types

- **AI developer tooling:** MCP servers, Codex integrations, context optimization, local analytics, safe upgrade paths.
- **Windows-first reliability:** PowerShell, `pwsh`, `cmd`, Git Bash, WSL, symlink restrictions, desktop deep links, packaging quirks.
- **API and data correctness:** OpenAI-compatible routes, streaming behavior, file metadata, citation markers, validation, and counting semantics.
- **Release safety:** dependency checks, runtime guards, reproducible setup, CI and test lifecycle fixes.
- **Maintainer-friendly delivery:** narrow diffs, issue-backed scope, concrete tests, concise validation, and follow-up fixes.

## 🛠️ Personal Artifacts

| Project | What it equips |
| --- | --- |
| [codex-keyring](https://github.com/NgoQuocViet2001/codex-keyring) | Native multi-account manager for Codex with aliases, health checks, and failover support |
| [codex-observatory](https://github.com/NgoQuocViet2001/codex-observatory) | Local Codex usage analytics, token trends, model breakdowns, and dashboard views |
| [google-workspace-mcp](https://github.com/NgoQuocViet2001/google-workspace-mcp) | MCP server for structured Google Docs and Sheets extraction with image-aware output |

## 📜 Character Background

- Fullstack delivery across product and outsourced environments, with project bootstrapping, reusable component design, code review, Git flow, mentoring, and internal training.
- Project-level Dev Lead experience in healthcare systems, including BA/QC/developer coordination and legacy-parity work.
- Hands-on deployment and support across AWS, Linux, Docker, Nginx, CI/CD, VPS, staging, and production environments.
- AWS Certified Solutions Architect – Associate, scored **861/1000**.

## 📬 Party Invite

Open to OSS collaboration, maintainer support, developer tooling, automation, and practical fullstack/internal-tool work.

[Portfolio](https://viet-ngo.hinadau.vip) · [GitHub](https://github.com/NgoQuocViet2001) · [Zalo](https://zalo.me/0971933518) · [Facebook](https://www.facebook.com/ngoquocviet2001/)
