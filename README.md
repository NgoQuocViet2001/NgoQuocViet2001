<div align="center">

![Ngo Quoc Viet — open-source adventurer](./assets/rpg-hero.svg?v=20261002)

[![GitHub](https://img.shields.io/badge/GitHub-NgoQuocViet2001-183143?style=for-the-badge&logo=github&logoColor=white)](https://github.com/NgoQuocViet2001)
[![Portfolio](https://img.shields.io/badge/Portfolio-viet--ngo.hinadau.vip-315A83?style=for-the-badge)](https://viet-ngo.hinadau.vip)
[![AWS SAA](https://img.shields.io/badge/AWS_SAA-861%2F1000-F0A928?style=for-the-badge)](https://www.credly.com/badges/b9822361-43e5-40f3-a590-a3c56a1a1d59)
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

Public contribution data for [`NgoQuocViet2001`](https://github.com/NgoQuocViet2001), refreshed **2026-10-02**. The merged count covers public PRs submitted from this account and accepted into repositories it does not own during the preceding 12 months.

<div align="center">
  <img src="./assets/github-activity.svg?v=20261002" alt="Retro RPG board showing 139 merged pull requests across 48 community repositories and 66 active pull requests" width="1200" />
</div>

| Stat | Total | Meaning |
| --- | ---: | --- |
| **Merged quests** | **139** | External PRs merged by community maintainers in the last 12 months |
| **Worlds visited** | **48** | Community repositories with at least one merged contribution |
| **Active quests** | **66** | External PRs currently open for maintainer review |

## ⚔️ Latest Quests Cleared

The most recent merges, newest first. Earlier merged work is summarized in the Guild History table below.

| Project | PR | Quest result | Merged |
| --- | --- | --- | --- |
| [Spec Kit](https://github.com/github/spec-kit) | [#4417](https://github.com/github/spec-kit/pull/4417) | Unwraps a group spanning a whole workflow expression, so adding parentheses to make precedence explicit stops inverting the result. | 2026-09-29 |
| [Spec Kit](https://github.com/github/spec-kit) | [#4416](https://github.com/github/spec-kit/pull/4416) | Resolves negative list indices in workflow expressions, so `task_list[-1]` returns the last item instead of rendering empty. | 2026-09-29 |
| [vscode-languageserver-node](https://github.com/microsoft/vscode-languageserver-node) | [#1857](https://github.com/microsoft/vscode-languageserver-node/pull/1857) | Releases the parallelism slot when a dispatched message rejects, so one failed response write no longer stalls every later message on a connection with `maxParallelism`. | 2026-09-29 |
| [DeepSeek-Reasonix](https://github.com/esengine/DeepSeek-Reasonix) | [#7992](https://github.com/esengine/DeepSeek-Reasonix/pull/7992) | Rejects remote install manifests over the documented 2 MiB fetch limit instead of silently truncating them, while still accepting a manifest of exactly that size. | 2026-09-25 |
| [marked](https://github.com/markedjs/marked) | [#4091](https://github.com/markedjs/marked/pull/4091) | Strips leading and trailing whitespace when normalizing link reference labels, so a definition and a reference that differ only in surrounding whitespace match as CommonMark requires. | 2026-09-21 |
| [Poetry](https://github.com/python-poetry/poetry) | [#11014](https://github.com/python-poetry/poetry/pull/11014) | Reads the tags from the built extension wheel's filename instead of assuming the backend picks the first supported tag, so the chef test passes on any compatible platform. | 2026-09-19 |
| [vscode-languageserver-node](https://github.com/microsoft/vscode-languageserver-node) | [#1858](https://github.com/microsoft/vscode-languageserver-node/pull/1858) | Falls back to a full semantic-tokens result when `previousResult` gets an unknown id, instead of returning edits diffed against an older generation. | 2026-09-18 |
| [drawDB](https://github.com/drawdb-io/drawdb) | [#1146](https://github.com/drawdb-io/drawdb/pull/1146) | Skips custom types that have no fields when exporting to SQL Server, which previously threw and left the export disabled. | 2026-09-17 |
| [Yaak](https://github.com/mountain-loop/yaak) | [#647](https://github.com/mountain-loop/yaak/pull/647) | Uses the current time when `uuid.v6` has no timestamp, instead of passing `NaN` to the generator and producing a UUID dated 1582. | 2026-09-15 |
| [Slidev](https://github.com/slidevjs/slidev) | [#2704](https://github.com/slidevjs/slidev/pull/2704) | Answers an out-of-range slide patch with a 404, so a stale editor save no longer dereferences a missing slide and stops the dev server. | 2026-09-15 |
| [Slidev](https://github.com/slidevjs/slidev) | [#2732](https://github.com/slidevjs/slidev/pull/2732) | Rejects a unit-less timestamp that is not a number, so `duration: 30,5` fails at parse time instead of rendering `NaN` in the timer. | 2026-09-15 |
| [Slidev](https://github.com/slidevjs/slidev) | [#2733](https://github.com/slidevjs/slidev/pull/2733) | Strips an optional title and angle brackets from markdown image destinations, so preloading stops requesting URLs that can never resolve. | 2026-09-15 |
| [Slidev](https://github.com/slidevjs/slidev) | [#2740](https://github.com/slidevjs/slidev/pull/2740) | Whitelists the resolved snippet path for `{monaco-write}`, so a relative snippet import can be saved back from the editor instead of being rejected. | 2026-09-15 |
| [undici](https://github.com/nodejs/undici) | [#5808](https://github.com/nodejs/undici/pull/5808) | Keeps a numeric `Expires` of 0 when serializing a cookie, which the truthiness check silently dropped even though the epoch means expire now. | 2026-09-15 |
| [Rollup](https://github.com/rollup/rollup) | [#6514](https://github.com/rollup/rollup/pull/6514) | Removes the whole CRLF pair when suppressing ASI, so a lone CR no longer triggers the semicolon insertion the removal was meant to prevent. | 2026-09-14 |
| [undici](https://github.com/nodejs/undici) | [#5807](https://github.com/nodejs/undici/pull/5807) | Treats inherited `Object.prototype` names such as `constructor` as unsupported encodings in the decompress interceptor instead of calling them as decompressors. | 2026-09-14 |
| [Project N.O.M.A.D.](https://github.com/Crosstalk-Solutions/project-nomad) | [#1245](https://github.com/Crosstalk-Solutions/project-nomad/pull/1245) | Routes the model-download queue through the shared orphan guard, so one orphaned BullMQ job no longer makes `GET /api/downloads/jobs` fail on every poll. | 2026-09-13 |
| [Project N.O.M.A.D.](https://github.com/Crosstalk-Solutions/project-nomad) | [#1220](https://github.com/Crosstalk-Solutions/project-nomad/pull/1220) | Aborts a streaming chat response when the chat is unmounted, disabled or switched, so abandoned streams stop exhausting the browser's connection pool. | 2026-09-13 |
| [Yaak](https://github.com/mountain-loop/yaak) | [#643](https://github.com/mountain-loop/yaak/pull/643) | Stops the Postman importer from swapping an API key's name and value. | 2026-09-12 |
| [OpenHuman](https://github.com/tinyhumansai/openhuman) | [#5455](https://github.com/tinyhumansai/openhuman/pull/5455) | Makes the Windows installer fail with a real PowerShell error and a non-zero exit code when a release, checksum or MSI/EXE step fails, instead of printing a message and returning success. | 2026-09-11 |
| [vscode-css-languageservice](https://github.com/microsoft/vscode-css-languageservice) | [#497](https://github.com/microsoft/vscode-css-languageservice/pull/497) | Treats ICSS `:import(...)` blocks like `:export`, so their aliases stop being reported as unknown properties. | 2026-09-08 |
| [vscode-css-languageservice](https://github.com/microsoft/vscode-css-languageservice) | [#496](https://github.com/microsoft/vscode-css-languageservice/pull/496) | Inserts the CSS Color 4 `rgb(R G B / A)` form for the `rgb` completion, so alpha no longer needs the legacy `rgba` alias. | 2026-09-08 |
| [Hindsight](https://github.com/vectorize-io/hindsight) | [#4076](https://github.com/vectorize-io/hindsight/pull/4076) | Rolls "last weekend" and 上周末 back a full week on both weekend days, so the question asked on a Sunday stops resolving to the weekend in progress. | 2026-09-07 |
| [AI-For-Beginners](https://github.com/microsoft/AI-For-Beginners) | [#733](https://github.com/microsoft/AI-For-Beginners/pull/733) | Completes a quiz on its own question count, so the fourth question of the lesson 24 post-quiz is no longer skipped. | 2026-09-04 |
| [Xinference](https://github.com/xorbitsai/inference) | [#5483](https://github.com/xorbitsai/inference/pull/5483) | Counts records under an active ban when reporting a bulk unban, so the number returned agrees with the banned-IP and banned-key listings instead of including expired and never-banned records. | 2026-09-04 |
| [OpenCADStudio](https://github.com/HakanSeven12/OpenCADStudio) | [#983](https://github.com/HakanSeven12/OpenCADStudio/pull/983) | Renders DIMAUNIT 4 through the dimension's own DMS formatter, so a drawing authored in surveyor units stops annotating bearings as decimal degrees. | 2026-09-03 |
| [OpenCADStudio](https://github.com/HakanSeven12/OpenCADStudio) | [#984](https://github.com/HakanSeven12/OpenCADStudio/pull/984) | Makes `^` right-associative in the expression evaluator, so a chained exponent such as `2^3^2` evaluates to a number instead of returning the text `8^2`. | 2026-09-03 |
| [OpenCADStudio](https://github.com/HakanSeven12/OpenCADStudio) | [#982](https://github.com/HakanSeven12/OpenCADStudio/pull/982) | Reads the per-object DIMCLRE and DIMCLRT overrides in the renderer, so extension-line and text colours set in the Properties panel take effect on screen. | 2026-09-03 |
| [OpenCADStudio](https://github.com/HakanSeven12/OpenCADStudio) | [#981](https://github.com/HakanSeven12/OpenCADStudio/pull/981) | Rounds engineering units before splitting feet from inches, so a measurement of 35.999 inches reads `3'-0.00"` rather than the impossible `2'-12.00"`. | 2026-09-03 |
| [Vite](https://github.com/vitejs/vite) | [#23346](https://github.com/vitejs/vite/pull/23346) | Keeps the image URL when a density descriptor omits its leading zero, so `.5x` candidates are no longer dropped from `srcset` and `image-set()`. | 2026-09-01 |
| [repowise](https://github.com/repowise-dev/repowise) | [#1752](https://github.com/repowise-dev/repowise/pull/1752) | Shares the sink-reachability walk between the cross-function loop and lock passes while preserving call-line accurate first-hop resolution. | 2026-08-29 |
| [repowise](https://github.com/repowise-dev/repowise) | [#1751](https://github.com/repowise-dev/repowise/pull/1751) | Makes `coverage add` exit non-zero when it stores nothing, with opt-in strict handling for partial ingests. | 2026-08-27 |
| [book-to-skill](https://github.com/virgiliojr94/book-to-skill) | [#178](https://github.com/virgiliojr94/book-to-skill/pull/178) | Strips four invisible carriers a `Cf` category filter cannot reach — variation selectors, interlinear annotation controls, the braille blank, and zero-width musical marks — while leaving dotted braille patterns and the code points just outside each range alone. | 2026-08-25 |
| [text-to-cad](https://github.com/earthtojake/text-to-cad) | [#331](https://github.com/earthtojake/text-to-cad/pull/331) | Reads the arc angle keys the DXF parsers actually emit, so a 90° arc stops being drawn as a complete circle. | 2026-08-25 |
| [mise](https://github.com/jdx/mise) | [#12362](https://github.com/jdx/mise/pull/12362) | Emits the list separator when prepending to `PATH` in elvish, so a new entry no longer fuses onto the first existing one. | 2026-08-25 |

## 🏰 Guild History

| Community project | Merged quests | Contribution territory |
| --- | ---: | --- |
| [HakanSeven12/OpenCADStudio](https://github.com/HakanSeven12/OpenCADStudio) | **16** | CAD geometry, commands, expression evaluation, dimension styling, unit formatting, DWG rendering, Windows file locking, and printer integration |
| [mksglu/context-mode](https://github.com/mksglu/context-mode) | **13** | Codex/MCP reliability, Windows shells, plugin installs, analytics, cache behavior, docs, and regression coverage |
| [slidevjs/slidev](https://github.com/slidevjs/slidev) | **10** | Base-path routing, reactive frontmatter, addon preprocessing, test lifecycle cleanup, local exports, scaffold setup, slide-patch bounds, parser input validation, and Monaco write-back paths |
| [tinyhumansai/openhuman](https://github.com/tinyhumansai/openhuman) | **9** | Desktop OAuth, deep links, packaging, startup cleanup, RPC security, AppImage release safety, Windows contributor setup, and Windows installer failure reporting |
| [CJackHwang/ds2api](https://github.com/CJackHwang/ds2api) | **8** | OpenAI-compatible routes, streaming, citations, tool output, Vercel sync, and file metadata |
| [mountain-loop/yaak](https://github.com/mountain-loop/yaak) | **8** | Curl import parsing, shell-safe curl and gRPCurl export, OAuth 1.0 PLAINTEXT signing, JSON template escaping, Postman API key import, and UUID v6 timestamps |
| [github/spec-kit](https://github.com/github/spec-kit) | **6** | Development agent symlinks, safe Kiro multi-install behavior, authentication host matching, workflow step-type validation, and workflow expression indexing and grouping |
| [earthtojake/text-to-cad](https://github.com/earthtojake/text-to-cad) | **5** | Windows SMB write resilience, cross-language CAD selector and label parity, and DXF arc angle parsing |
| [Crosstalk-Solutions/project-nomad](https://github.com/Crosstalk-Solutions/project-nomad) | **4** | Offline content download reliability, benchmark startup correctness, orphaned download-job handling, and chat stream cleanup |
| [drawdb-io/drawdb](https://github.com/drawdb-io/drawdb) | **4** | Clipboard schema validation, self-referencing foreign keys, SQL literal escaping for enum values, and SQL Server export of fieldless custom types |
| [jdx/mise](https://github.com/jdx/mise) | **4** | Filesystem-safe install linking, portable generated bootstrap paths, and nushell and elvish activation correctness |
| [repowise-dev/repowise](https://github.com/repowise-dev/repowise) | **4** | Health-analysis precision, sink-reachability sharing, wiki page scoping, and CLI exit-code correctness |
| [neurosnap/zmx](https://github.com/neurosnap/zmx) | **3** | Session wildcard matching, prefixed picker behavior, and nested-session documentation |
| [tt-a1i/archify](https://github.com/tt-a1i/archify) | **3** | CLI validation, renderer-bound safety, and full-width text measurement |
| [DayuanJiang/next-ai-draw-io](https://github.com/DayuanJiang/next-ai-draw-io) | **2** | MCP diagram edit consistency, stale-state protection, and multi-page export preservation |
| [logto-io/logto](https://github.com/logto-io/logto) | **2** | Tenant initialization error observability and accurate contributor prerequisites |
| [microsoft/vscode-css-languageservice](https://github.com/microsoft/vscode-css-languageservice) | **2** | CSS Color 4 `rgb()` completions and ICSS `:import` property linting |
| [microsoft/vscode-languageserver-node](https://github.com/microsoft/vscode-languageserver-node) | **2** | JSON-RPC parallelism slot accounting and semantic-token delta baselines |
| [nodejs/undici](https://github.com/nodejs/undici) | **2** | Decompression encoding lookup safety and cookie `Expires` serialization |
| [ruvnet/RuView](https://github.com/ruvnet/RuView) | **2** | ESP32 swarm configuration validation and mesh-to-dashboard documentation |
| [virgiliojr94/book-to-skill](https://github.com/virgiliojr94/book-to-skill) | **2** | Literal handling for bracketed input paths and invisible-carrier sanitization |
| [vitejs/vite](https://github.com/vitejs/vite) | **2** | Config-bundle resource cleanup on failed generation and srcset density-descriptor parsing |

### First clears

Community repositories with one merged contribution so far:

| Community project | Contribution territory |
| --- | --- |
| [3b1b/manim](https://github.com/3b1b/manim) | Graph point lookup on manual curves outside unit x-ranges |
| [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) | Eval grader-result validation and summary integrity |
| [agegr/pi-web](https://github.com/agegr/pi-web) | Wrapper process lifecycle, signal forwarding, and exit statuses |
| [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design) | Accessible keyboard navigation for diagram gallery choices |
| [esengine/DeepSeek-Reasonix](https://github.com/esengine/DeepSeek-Reasonix) | Remote install manifest size enforcement |
| [infiniflow/ragflow](https://github.com/infiniflow/ragflow) | CLI benchmark failure accounting by response envelope |
| [markedjs/marked](https://github.com/markedjs/marked) | CommonMark link reference label normalization |
| [microsoft/AI-For-Beginners](https://github.com/microsoft/AI-For-Beginners) | Quiz completion driven by each quiz's own question count |
| [NVIDIA-NeMo/Switchyard](https://github.com/NVIDIA-NeMo/Switchyard) | Nested protocol metadata normalization and header precedence |
| [NVIDIA/cuda-rust](https://github.com/NVIDIA/cuda-rust) | Early validation for variadic CUDA device extern declarations |
| [OmniNull/OmniWM](https://github.com/OmniNull/OmniWM) | Complete public CLI and IPC command reference |
| [opengeos/GeoLibre](https://github.com/opengeos/GeoLibre) | Geographic-to-planar projection for buffer processing |
| [pacifio/atlas](https://github.com/pacifio/atlas) | Agent turn epoch handling and late transcript events |
| [paperless-ngx/paperless-ngx](https://github.com/paperless-ngx/paperless-ngx) | Sanity-check data correctness and regression coverage |
| [pingdotgg/t3code](https://github.com/pingdotgg/t3code) | Cross-platform repository symlink integrity |
| [pnpm/pnpm](https://github.com/pnpm/pnpm) | Prerelease range-style preservation across TypeScript and Rust update paths |
| [python-poetry/poetry](https://github.com/python-poetry/poetry) | Extension wheel tag handling in the build tests |
| [rollup/rollup](https://github.com/rollup/rollup) | CRLF-safe line-break removal when suppressing ASI |
| [rorkai/App-Store-Connect-CLI](https://github.com/rorkai/App-Store-Connect-CLI) | CLI argument validation before authentication |
| [supertone-oss-archive/supertonic](https://github.com/supertone-oss-archive/supertonic) | Multi-language CLI option documentation |
| [TheJoeFin/Text-Grab](https://github.com/TheJoeFin/Text-Grab) | Language-aware Latin correction across OCR capture paths |
| [tw93/Pake](https://github.com/tw93/Pake) | CLI startup independence from native image dependencies |
| [vectorize-io/hindsight](https://github.com/vectorize-io/hindsight) | Weekend-relative date resolution |
| [withastro/astro](https://github.com/withastro/astro) | Page-directory boundary correctness and regression coverage |
| [xorbitsai/inference](https://github.com/xorbitsai/inference) | Truthful ban accounting in bulk unban responses |
| [ZSeven-W/openpencil](https://github.com/ZSeven-W/openpencil) | CLI positional argument forwarding |

## 🔥 Active Quest Queue

The newest open contributions waiting for maintainer review, ordered by creation time. **66** are open in total; the 20 most recent are listed here.

| Project | PR | Quest in progress |
| --- | --- | --- |
| [Astro](https://github.com/withastro/astro) | [#18200](https://github.com/withastro/astro/pull/18200) | Escapes `#` and `?` before resolving `glob()` entry paths, so a file such as `c#-basics.md` is loaded instead of being read from `.../c` and dropped. |
| [Mermaid](https://github.com/mermaid-js/mermaid) | [#8359](https://github.com/mermaid-js/mermaid/pull/8359) | Resets the gantt task-id index in `clear()`, so a later diagram stops resolving `after` dependencies and click handlers against an earlier diagram's tasks. |
| [Hono](https://github.com/honojs/hono) | [#5498](https://github.com/honojs/hono/pull/5498) | Falls back to single-segment matching for regex params in `basePath()`, as the router does, so a `/api/:version{v[0-9]+}` mount reports `/api/v2` instead of `/api/`. |
| [undici](https://github.com/nodejs/undici) | [#5953](https://github.com/nodejs/undici/pull/5953) | Stores repeated response headers as arrays in mock snapshots, so two `Set-Cookie` headers replay as two cookies instead of one comma-joined value. |
| [Slidev](https://github.com/slidevjs/slidev) | [#2760](https://github.com/slidevjs/slidev/pull/2760) | Accepts `#` and `+` in fence languages, so `c#`, `c++` and `f#` blocks keep their grammar, title and ranges, and work in Magic Move. |
| [Svelte](https://github.com/sveltejs/svelte) | [#18903](https://github.com/sveltejs/svelte/pull/18903) | Decodes numeric character references in planes 3, 15 and 16 instead of replacing them with U+0000. |
| [Yaak](https://github.com/mountain-loop/yaak) | [#723](https://github.com/mountain-loop/yaak/pull/723) | Returns the value of attribute, text and CDATA nodes selected by XPath, which previously rendered as empty strings. |
| [Poetry](https://github.com/python-poetry/poetry) | [#11120](https://github.com/python-poetry/poetry/pull/11120) | Normalizes `POETRY_CERTIFICATES_<NAME>_CERT=false` to a boolean, so it disables TLS verification instead of being used as a CA bundle path named `false`. |
| [vscode-js-debug](https://github.com/microsoft/vscode-js-debug) | [#2424](https://github.com/microsoft/vscode-js-debug/pull/2424) | Lets a `**` in the middle of a `skipFiles` glob match zero directories, so `lib/**/*.js` also skips `lib/index.js`. |
| [marked](https://github.com/markedjs/marked) | [#4115](https://github.com/markedjs/marked/pull/4115) | Ends a block quote before a lazy line that follows a heading, thematic break or HTML block, as CommonMark specifies. |
| [vscode-textmate](https://github.com/microsoft/vscode-textmate) | [#302](https://github.com/microsoft/vscode-textmate/pull/302) | Skips a zero-width range in `LineFonts.produceFromScopes`, as `LineTokens` already does, so a zero-width rule end no longer creates an empty font range. |
| [vscode-html-languageservice](https://github.com/microsoft/vscode-html-languageservice) | [#261](https://github.com/microsoft/vscode-html-languageservice/pull/261) | Anchors the `#endregion` marker regex, so a comment that merely contains the word *endregion* stops closing the open region. |
| [vscode-json-languageservice](https://github.com/microsoft/vscode-json-languageservice) | [#368](https://github.com/microsoft/vscode-json-languageservice/pull/368) | Runs the `$vocabulary` gate for keywords introduced in 2019-09 and later, such as `dependentRequired` and `unevaluatedProperties`, instead of enabling them by draft alone. |
| [Express](https://github.com/expressjs/express) | [#7467](https://github.com/expressjs/express/pull/7467) | Treats the app `etag` setting as a default for `res.sendFile()`, so an explicit `etag: false` option is respected again. |
| [Fastify](https://github.com/fastify/fastify) | [#7023](https://github.com/fastify/fastify/pull/7023) | Makes `removeContentTypeParser('*')` and `hasContentTypeParser('*')` find the catch-all parser, which is stored under a different key. |
| [date-fns](https://github.com/date-fns/date-fns) | [#4320](https://github.com/date-fns/date-fns/pull/4320) | Parses Vietnamese quarters II and III as Q2 and Q3 instead of Q1. |
| [manim](https://github.com/3b1b/manim) | [#2532](https://github.com/3b1b/manim/pull/2532) | Uses the step from a three-element `x_range` when extending the right endpoint in `get_riemann_rectangles`, and stops mutating the caller's sequence. |
| [vscode-css-languageservice](https://github.com/microsoft/vscode-css-languageservice) | [#521](https://github.com/microsoft/vscode-css-languageservice/pull/521) | Gives each LCS matrix row its own array in `difference()`, so rows no longer share one array and corrupt each other's values. |
| [page-agent](https://github.com/alibaba/page-agent) | [#704](https://github.com/alibaba/page-agent/pull/704) | Sets a `<select>` through the native value setter and fires `input` before `change`, so React's change tracker sees the new value instead of dropping the agent's selection. |
| [page-agent](https://github.com/alibaba/page-agent) | [#700](https://github.com/alibaba/page-agent/pull/700) | Blends a translucent background over what is behind it when measuring luminance, so a light page carrying a faint tint is no longer painted with the dark-mode mask. |

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
