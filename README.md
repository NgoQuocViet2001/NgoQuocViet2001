<div align="center">

![Ngo Quoc Viet — open-source adventurer](./assets/rpg-hero.svg?v=20261111)

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

Public contribution data for [`NgoQuocViet2001`](https://github.com/NgoQuocViet2001), refreshed **2026-11-11**. The merged count covers public PRs submitted from this account and accepted into repositories it does not own during the preceding 12 months.

<div align="center">
  <img src="./assets/github-activity.svg?v=20261111" alt="Retro RPG board showing 199 merged pull requests across 81 community repositories and 82 active pull requests" width="1200" />
</div>

| Stat | Total | Meaning |
| --- | ---: | --- |
| **Merged quests** | **199** | External PRs merged by community maintainers in the last 12 months |
| **Worlds visited** | **81** | Community repositories with at least one merged contribution |
| **Active quests** | **82** | External PRs currently open for maintainer review |

## ⚔️ Latest Quests Cleared

The most recent merges, newest first. Earlier merged work is summarized in the Guild History table below.

| Project | PR | Quest result | Merged |
| --- | --- | --- | --- |
| [Vue Router](https://github.com/vuejs/router) | [#2860](https://github.com/vuejs/router/pull/2860) | Reads quoted `definePage()` keys such as `'name'` and `'alias'` at build time, as it already does for identifier keys, so they are no longer stripped unread and a quoted `'meta'` still reaches the route. | 2026-11-10 |
| [h3](https://github.com/h3js/h3) | [#1615](https://github.com/h3js/h3/pull/1615) | Keeps `iterable()` reading until it enqueues a chunk or the iterator ends, so skipped `undefined` values, or values the serializer turns into `undefined`, no longer leave a read pending and the response always finishes. | 2026-11-10 |
| [Socket.IO](https://github.com/socketio/socket.io) | [#5574](https://github.com/socketio/socket.io/pull/5574) | Keeps everything after the first `=` when the client decodes a query string, so `?token=abc==&flag` reaches the server as `{ token: "abc==", flag: "" }` instead of `abc` and the string `"undefined"`. | 2026-11-10 |
| [Claude Code Templates](https://github.com/davila7/claude-code-templates) | [#551](https://github.com/davila7/claude-code-templates/pull/551) | Fixes the attribution and license links in `cli-tool/README.md` so they resolve from the `cli-tool/` folder. | 2026-11-08 |
| [concurrently](https://github.com/open-cli-tools/concurrently) | [#640](https://github.com/open-cli-tools/concurrently/pull/640) | Registers a command as an input target under its name only when it has one, so with `--handle-input` a line like `:observer.start()` goes unchanged to the default target instead of reaching the last unnamed command with its colon stripped. | 2026-11-07 |
| [{fmt}](https://github.com/fmtlib/fmt) | [#4999](https://github.com/fmtlib/fmt/pull/4999) | Uses the native or generic string the path formatter selected for wide output too, so `L"{:g}"` prints `C:/foo` on Windows like `"{:g}"` does instead of ignoring `g`, and wide `{:g}` and `{:?g}` keep the generic form on POSIX. | 2026-11-06 |
| [indicatif](https://github.com/console-rs/indicatif) | [#854](https://github.com/console-rs/indicatif/pull/854) | Makes `MultiProgress::add` and the `insert*` methods return an existing member unchanged, as documented, so re-adding a bar no longer moves it or leaves a stale slot that stops finished bars from being pruned. | 2026-11-05 |
| [MikroORM](https://github.com/mikro-orm/mikro-orm) | [#8518](https://github.com/mikro-orm/mikro-orm/pull/8518) | Reads the collation, inline check and generated expression of the first column during SQLite introspection, so a collated or enum primary key no longer makes `getUpdateSchemaSQL()` rebuild the table right after `schema.create()`. | 2026-11-04 |
| [Puppeteer](https://github.com/puppeteer/puppeteer) | [#15694](https://github.com/puppeteer/puppeteer/pull/15694) | Records the `buildIdAlias` in the cache metadata even when the build is already installed, so `launch chrome@canary` finds a cached Canary build and an alias that pointed to an older build is updated. | 2026-11-03 |
| [TypeScript-DOM-lib-generator](https://github.com/microsoft/TypeScript-DOM-lib-generator) | [#2576](https://github.com/microsoft/TypeScript-DOM-lib-generator/pull/2576) | Matches the member name as a whole word when bolding it in generated MDN comments, so the `DOMPointReadOnly.y` comment bolds the standalone `y` instead of the last letter of `DOMPointReadOnly`. | 2026-11-03 |
| [Redux Toolkit](https://github.com/reduxjs/redux-toolkit) | [#5472](https://github.com/reduxjs/redux-toolkit/pull/5472) | Stops merging `name[]` array params, and `name[prop]` params that clash with a plain `name` param, into one object, so the codegen no longer emits empty-key array wrappers or duplicate keys that fail `tsc`. | 2026-11-03 |
| [Chai](https://github.com/chaijs/chai) | [#1893](https://github.com/chaijs/chai/pull/1893) | Makes `.empty` throw `.empty was passed a function` for async, generator and async generator functions too, as in chai 4, instead of passing them as objects with no own keys. | 2026-11-03 |
| [Vue DevTools](https://github.com/vuejs/devtools) | [#1181](https://github.com/vuejs/devtools/pull/1181) | Lists the records from `router.getRoutes()` once on the Pages tab instead of also walking each record's `children`, so nested routes no longer appear twice with relative paths that navigate to the wrong URL. | 2026-11-03 |
| [Unhead](https://github.com/unjs/unhead) | [#1028](https://github.com/unjs/unhead/pull/1028) | Ends extracted `<script>`, `<style>` and `<title>` content at the first closing tag, as browsers do, so a quote in a comment or regex no longer leaves script source as text in `<head>` or merges adjacent scripts. | 2026-11-03 |
| [Pinia](https://github.com/vuejs/pinia) | [#3203](https://github.com/vuejs/pinia/pull/3203) | Removes stale getters and actions at the start of `_hotUpdate`, before the new definitions are applied, so a property that switches between getter, action and state during HMR no longer becomes `undefined` until a reload. | 2026-11-03 |
| [tRPC](https://github.com/trpc/trpc) | [#7721](https://github.com/trpc/trpc/pull/7721) | Passes each page's cursor and direction to the procedure in the `fetchInfinite`, `prefetchInfinite` and `infiniteQueryOptions` server-side helpers, falling back to `initialCursor`, so prefetched infinite queries fetch the requested pages instead of repeating the first one. | 2026-11-02 |
| [marked](https://github.com/markedjs/marked) | [#4161](https://github.com/markedjs/marked/pull/4161) | Ends a block quote before a lazy line that follows a table, as cmark-gfm does, so the unquoted line renders as a paragraph after the quote instead of inside it. | 2026-11-02 |
| [Mongoose](https://github.com/Automattic/mongoose) | [#16634](https://github.com/Automattic/mongoose/pull/16634) | Converts ObjectId keys to strings in `MongooseMap#has()`, as `get()`, `set()` and `delete()` already do, so `has(userId)` returns `true` for a key that `get(userId)` finds. | 2026-11-01 |
| [Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | [#2371](https://github.com/SBoudrias/Inquirer.js/pull/2371) | Merges the locale strings in `@inquirer/i18n` prompts before the user's `theme`, so a custom `maskedText`, `keysHelpTip` or `confirm` keyword is no longer replaced, and a custom `keysHelpTip` receives the translated labels. | 2026-10-31 |
| [vscode-js-debug](https://github.com/microsoft/vscode-js-debug) | [#2445](https://github.com/microsoft/vscode-js-debug/pull/2445) | Leaves `%` unescaped in a logpoint message that interpolates no `{expression}`, since `console.log` only applies format specifiers when it gets more than one argument, so `50% done` no longer logs as `50%% done`. | 2026-10-31 |
| [Vue Test Utils](https://github.com/vuejs/test-utils) | [#2983](https://github.com/vuejs/test-utils/pull/2983) | Treats any DOM `Node` ref as an element in `findComponent({ ref })`, not only an `HTMLElement`, so a ref on an `<svg>` returns an empty wrapper instead of throwing a `TypeError`. | 2026-10-30 |
| [Pake](https://github.com/tw93/Pake) | [#1426](https://github.com/tw93/Pake/pull/1426) | Decodes the percent-encoded last URL path segment when naming downloads, as browsers do, so a link to `Annual%20Report.pdf` saves as `Annual Report.pdf`, while unsafe or malformed names keep their encoded form. | 2026-10-30 |
| [Ghost](https://github.com/TryGhost/Ghost) | [#32355](https://github.com/TryGhost/Ghost/pull/32355) | Closes the outermost format the next text lacks, with every format nested inside it, in the Lexical HTML renderer, so bold that ends while italic continues no longer spreads onto italic-only text in posts and newsletters. | 2026-10-30 |
| [vscode-languageserver-node](https://github.com/microsoft/vscode-languageserver-node) | [#1931](https://github.com/microsoft/vscode-languageserver-node/pull/1931) | Accepts relative patterns in `NotebookDocumentFilter.is`, as `TextDocumentFilter.is` already does, so the client's `asDocumentSelector` no longer drops a notebook filter with a relative pattern or turns it into a plain language filter. | 2026-10-30 |
| [Go-MySQL-Driver](https://github.com/go-sql-driver/mysql) | [#1832](https://github.com/go-sql-driver/mysql/pull/1832) | Flips the inverted unknown-collation check in the handshake, so `charset=utf8mb4&collation=utf8mb4_0900_as_ci` connects and sets the collation with `SET NAMES`, while an unknown collation without `charset` fails instead of silently using the default. | 2026-10-30 |
| [Solid](https://github.com/solidjs/solid) | [#4424](https://github.com/solidjs/solid/pull/4424) | Reads a getter `class` through the props object when `h` merges it with selector classes, so a component forwarding props to `h("button.btn", props)` gets a reactive merged class instead of throwing `Invalid property descriptor`. | 2026-10-30 |
| [Xinference](https://github.com/xorbitsai/inference) | [#5915](https://github.com/xorbitsai/inference/pull/5915) | Replaces a dangling cache symlink when an image, audio, video or world model with a local `model_uri` is launched, so re-registering a model after moving its weights no longer fails every launch with `FileExistsError`. | 2026-10-30 |
| [MiniJinja](https://github.com/mitsuhiko/minijinja) | [#991](https://github.com/mitsuhiko/minijinja/pull/991) | Formats floats like Python's `str()` in the `pycompat` `str.format` when no precision is given, so floats keep all their digits and `'{}'.format(1234567.0)` gives `1234567.0` instead of `1.23457e+06`. | 2026-10-29 |
| [dotenv](https://github.com/motdotla/dotenv) | [#1078](https://github.com/motdotla/dotenv/pull/1078) | Exits with the shell's `128 + signal` status when the command started by `dotenv run` dies from a signal Node ignores, such as `SIGPIPE`, so piping its output into `head` no longer hangs the pipeline. | 2026-10-29 |
| [Knip](https://github.com/webpro-nl/knip) | [#2254](https://github.com/webpro-nl/knip/pull/2254) | Escapes pipe characters in symbols in the markdown reporter, so a duplicate export row keeps its three cells instead of putting `default` under Location, the file path under Severity and dropping the severity. | 2026-10-29 |
| [VitePress](https://github.com/vuejs/vitepress) | [#5555](https://github.com/vuejs/vitepress/pull/5555) | Compares the code block language case-insensitively in `isShell`, so the copy button strips the `$` prompt from `Bash`, `SH`, `Shell` and `ZSH` blocks the same way it does for `bash` instead of copying it. | 2026-10-29 |
| [eslint-plugin-vue](https://github.com/vuejs/eslint-plugin-vue) | [#3211](https://github.com/vuejs/eslint-plugin-vue/pull/3211) | Applies the `ignore` and `ignoreParents` options of `vue/no-deprecated-slot-attribute` to `v-bind:slot` as well, so `--fix` no longer rewrites a bound slot under an ignored web component into `<template v-slot:[...]>`. | 2026-10-29 |
| [Ghost](https://github.com/TryGhost/Ghost) | [#32192](https://github.com/TryGhost/Ghost/pull/32192) | Maps the `kg-style-accent` class to `accent` and only converts inline button colours when parsing CTA cards from HTML, so brand colour buttons are no longer stored as `#00NaNNaN` and keep the accent style in newsletters. | 2026-10-27 |
| [vscode-js-debug](https://github.com/microsoft/vscode-js-debug) | [#2441](https://github.com/microsoft/vscode-js-debug/pull/2441) | Keeps the outer range's end when `Range.simplify` merges a range nested inside it, so the step `skipList` for WASM/DWARF frames no longer cuts off the tail of a region that should be skipped. | 2026-10-26 |
| [vscode-languageserver-node](https://github.com/microsoft/vscode-languageserver-node) | [#1918](https://github.com/microsoft/vscode-languageserver-node/pull/1918) | Counts the change annotations passed to `new WorkspaceChange(edit)` and skips ids already in use, so wrapping an existing `WorkspaceEdit` keeps its labels and `needsConfirmation` and adding an annotation no longer throws `Id 1 is already in use`. | 2026-10-26 |

## 🏰 Guild History

| Community project | Merged quests | Contribution territory |
| --- | ---: | --- |
| [HakanSeven12/OpenCADStudio](https://github.com/HakanSeven12/OpenCADStudio) | **16** | CAD geometry, commands, expression evaluation, dimension styling, unit formatting, DWG rendering, Windows file locking, and printer integration |
| [mksglu/context-mode](https://github.com/mksglu/context-mode) | **13** | Codex/MCP reliability, Windows shells, plugin installs, analytics, cache behavior, docs, and regression coverage |
| [slidevjs/slidev](https://github.com/slidevjs/slidev) | **11** | Base-path routing, reactive frontmatter, addon preprocessing, test lifecycle cleanup, local exports, scaffold setup, slide-patch bounds, parser input validation, Monaco write-back paths, and code-fence language parsing |
| [mountain-loop/yaak](https://github.com/mountain-loop/yaak) | **9** | Curl import parsing, shell-safe curl and gRPCurl export, OAuth 1.0 PLAINTEXT signing, JSON template escaping, Postman API key import, UUID v6 timestamps, and XPath attribute and text-node values |
| [tinyhumansai/openhuman](https://github.com/tinyhumansai/openhuman) | **9** | Desktop OAuth, deep links, packaging, startup cleanup, RPC security, AppImage release safety, Windows contributor setup, and Windows installer failure reporting |
| [CJackHwang/ds2api](https://github.com/CJackHwang/ds2api) | **8** | OpenAI-compatible routes, streaming, citations, tool output, Vercel sync, and file metadata |
| [github/spec-kit](https://github.com/github/spec-kit) | **6** | Development agent symlinks, safe Kiro multi-install behavior, authentication host matching, workflow step-type validation, and workflow expression indexing and grouping |
| [Anil-matcha/Open-Generative-AI](https://github.com/Anil-matcha/Open-Generative-AI) | **5** | Local AI model storage, onboarding, endpoint fallback, startup feedback, and reproducible setup |
| [earthtojake/text-to-cad](https://github.com/earthtojake/text-to-cad) | **5** | Windows SMB write resilience, cross-language CAD selector and label parity, and DXF arc angle parsing |
| [microsoft/vscode-languageserver-node](https://github.com/microsoft/vscode-languageserver-node) | **5** | JSON-RPC parallelism slot accounting, semantic-token delta baselines, notebook cell-map cleanup for deleted cells, change-annotation preservation in wrapped workspace edits, and relative-pattern notebook document filters |
| [Crosstalk-Solutions/project-nomad](https://github.com/Crosstalk-Solutions/project-nomad) | **4** | Offline content download reliability, benchmark startup correctness, orphaned download-job handling, and chat stream cleanup |
| [DayuanJiang/next-ai-draw-io](https://github.com/DayuanJiang/next-ai-draw-io) | **4** | MCP diagram edit consistency, stale-state protection, multi-page export preservation, and admin settings path validation |
| [drawdb-io/drawdb](https://github.com/drawdb-io/drawdb) | **4** | Clipboard schema validation, self-referencing foreign keys, SQL literal escaping for enum values, and SQL Server export of fieldless custom types |
| [jdx/mise](https://github.com/jdx/mise) | **4** | Filesystem-safe install linking, portable generated bootstrap paths, and nushell and elvish activation correctness |
| [repowise-dev/repowise](https://github.com/repowise-dev/repowise) | **4** | Health-analysis precision, sink-reachability sharing, wiki page scoping, and CLI exit-code correctness |
| [markedjs/marked](https://github.com/markedjs/marked) | **3** | CommonMark link reference label normalization and block quote lazy-continuation boundaries after headings, thematic breaks, HTML blocks, and tables |
| [microsoft/vscode-js-debug](https://github.com/microsoft/vscode-js-debug) | **3** | Zero-directory matching for middle `**` in skipFiles globs, contained-range merging in step skip lists, and literal `%` in logpoint messages that interpolate nothing |
| [neurosnap/zmx](https://github.com/neurosnap/zmx) | **3** | Session wildcard matching, prefixed picker behavior, and nested-session documentation |
| [puppeteer/puppeteer](https://github.com/puppeteer/puppeteer) | **3** | Cookie deletion filters by domain, path, URL, and partition key, WebDriver BiDi `Space` key input, and alias recording for already installed browser builds |
| [SBoudrias/Inquirer.js](https://github.com/SBoudrias/Inquirer.js) | **3** | Whitespace-only input handling in number prompts, empty `VISUAL` and `EDITOR` fallback in the external editor, and user theme precedence over locale defaults in localized prompts |
| [tt-a1i/archify](https://github.com/tt-a1i/archify) | **3** | CLI validation, renderer-bound safety, and full-width text measurement |
| [Automattic/mongoose](https://github.com/Automattic/mongoose) | **2** | `ReadPreference` instance handling for index and collection auto-creation and ObjectId key lookups in `MongooseMap#has()` |
| [logto-io/logto](https://github.com/logto-io/logto) | **2** | Tenant initialization error observability and accurate contributor prerequisites |
| [microsoft/vscode-css-languageservice](https://github.com/microsoft/vscode-css-languageservice) | **2** | CSS Color 4 `rgb()` completions and ICSS `:import` property linting |
| [mitsuhiko/minijinja](https://github.com/mitsuhiko/minijinja) | **2** | Multi-attribute `sort` filter keys and `str()`-style float formatting in `str.format` |
| [nodejs/undici](https://github.com/nodejs/undici) | **2** | Decompression encoding lookup safety and cookie `Expires` serialization |
| [ruvnet/RuView](https://github.com/ruvnet/RuView) | **2** | ESP32 swarm configuration validation and mesh-to-dashboard documentation |
| [solidjs/solid](https://github.com/solidjs/solid) | **2** | Character reference decoding in static `html` template attributes and selector-class merging with getter `class` props in `h` |
| [TryGhost/Ghost](https://github.com/TryGhost/Ghost) | **2** | CTA card accent button colours parsed from HTML and overlapping text-format nesting in the Lexical HTML renderer |
| [tw93/Pake](https://github.com/tw93/Pake) | **2** | CLI startup independence from native image dependencies and percent-encoded file name decoding for downloads |
| [virgiliojr94/book-to-skill](https://github.com/virgiliojr94/book-to-skill) | **2** | Literal handling for bracketed input paths and invisible-carrier sanitization |
| [vitejs/vite](https://github.com/vitejs/vite) | **2** | Config-bundle resource cleanup on failed generation and srcset density-descriptor parsing |
| [vuejs/devtools](https://github.com/vuejs/devtools) | **2** | Ancestor-only circular reference detection in value encoding and one row per route on the Pages tab |
| [vuejs/vitepress](https://github.com/vuejs/vitepress) | **2** | Include marker handling inside nested code fences and shell prompt stripping for uppercase fence languages |
| [xorbitsai/inference](https://github.com/xorbitsai/inference) | **2** | Truthful ban accounting in bulk unban responses and dangling `model_uri` cache link replacement for image, audio, video, and world models |

### First clears

Community repositories with one merged contribution so far:

| Community project | Contribution territory |
| --- | --- |
| [3b1b/manim](https://github.com/3b1b/manim) | Graph point lookup on manual curves outside unit x-ranges |
| [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) | Eval grader-result validation and summary integrity |
| [agegr/pi-web](https://github.com/agegr/pi-web) | Wrapper process lifecycle, signal forwarding, and exit statuses |
| [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design) | Accessible keyboard navigation for diagram gallery choices |
| [chaijs/chai](https://github.com/chaijs/chai) | `.empty` rejection of async and generator functions |
| [console-rs/indicatif](https://github.com/console-rs/indicatif) | Re-adding existing `MultiProgress` members |
| [davila7/claude-code-templates](https://github.com/davila7/claude-code-templates) | CLI README relative links |
| [esengine/DeepSeek-Reasonix](https://github.com/esengine/DeepSeek-Reasonix) | Remote install manifest size enforcement |
| [fmtlib/fmt](https://github.com/fmtlib/fmt) | Generic path formatting for wide strings |
| [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) | Unknown collation handling in the handshake with and without a charset |
| [h3js/h3](https://github.com/h3js/h3) | `iterable()` streaming past skipped values |
| [honojs/hono](https://github.com/honojs/hono) | Base-path resolution for regex route params |
| [infiniflow/ragflow](https://github.com/infiniflow/ragflow) | CLI benchmark failure accounting by response envelope |
| [microsoft/AI-For-Beginners](https://github.com/microsoft/AI-For-Beginners) | Quiz completion driven by each quiz's own question count |
| [microsoft/TypeScript-DOM-lib-generator](https://github.com/microsoft/TypeScript-DOM-lib-generator) | Whole-word member name bolding in MDN doc comments |
| [mikro-orm/mikro-orm](https://github.com/mikro-orm/mikro-orm) | First-column definitions in SQLite table introspection |
| [mitsuhiko/insta](https://github.com/mitsuhiko/insta) | JSON snapshot map keys for large unsigned integers |
| [motdotla/dotenv](https://github.com/motdotla/dotenv) | CLI exit status for commands killed by SIGPIPE |
| [NVIDIA-NeMo/Switchyard](https://github.com/NVIDIA-NeMo/Switchyard) | Nested protocol metadata normalization and header precedence |
| [NVIDIA/cuda-rust](https://github.com/NVIDIA/cuda-rust) | Early validation for variadic CUDA device extern declarations |
| [OmniNull/OmniWM](https://github.com/OmniNull/OmniWM) | Complete public CLI and IPC command reference |
| [open-cli-tools/concurrently](https://github.com/open-cli-tools/concurrently) | Input routing for commands without a name |
| [opengeos/GeoLibre](https://github.com/opengeos/GeoLibre) | Geographic-to-planar projection for buffer processing |
| [paperless-ngx/paperless-ngx](https://github.com/paperless-ngx/paperless-ngx) | Sanity-check data correctness and regression coverage |
| [pingdotgg/t3code](https://github.com/pingdotgg/t3code) | Cross-platform repository symlink integrity |
| [pnpm/pnpm](https://github.com/pnpm/pnpm) | Prerelease range-style preservation across TypeScript and Rust update paths |
| [pranshuparmar/witr](https://github.com/pranshuparmar/witr) | Localized Windows netstat listener detection |
| [python-poetry/poetry](https://github.com/python-poetry/poetry) | Extension wheel tag handling in the build tests |
| [reduxjs/redux-toolkit](https://github.com/reduxjs/redux-toolkit) | Bracketed query parameter grouping in RTK Query OpenAPI codegen |
| [rollup/rollup](https://github.com/rollup/rollup) | CRLF-safe line-break removal when suppressing ASI |
| [rorkai/App-Store-Connect-CLI](https://github.com/rorkai/App-Store-Connect-CLI) | CLI argument validation before authentication |
| [socketio/socket.io](https://github.com/socketio/socket.io) | Client query values that contain `=` |
| [supertone-oss-archive/supertonic](https://github.com/supertone-oss-archive/supertonic) | Multi-language CLI option documentation |
| [TheJoeFin/Text-Grab](https://github.com/TheJoeFin/Text-Grab) | Language-aware Latin correction across OCR capture paths |
| [trpc/trpc](https://github.com/trpc/trpc) | Cursor forwarding in `createServerSideHelpers` infinite helpers |
| [tryatlas/atlas](https://github.com/tryatlas/atlas) | Agent turn epoch handling and late transcript events |
| [unjs/unhead](https://github.com/unjs/unhead) | Closing-tag detection for extracted script, style, and title content |
| [vectorize-io/hindsight](https://github.com/vectorize-io/hindsight) | Weekend-relative date resolution |
| [vuejs/eslint-plugin-vue](https://github.com/vuejs/eslint-plugin-vue) | `ignore` and `ignoreParents` options for `v-bind:slot` in `no-deprecated-slot-attribute` |
| [vuejs/pinia](https://github.com/vuejs/pinia) | HMR updates for store properties that change kind |
| [vuejs/router](https://github.com/vuejs/router) | Quoted `definePage()` keys at build time |
| [vuejs/test-utils](https://github.com/vuejs/test-utils) | `findComponent` ref lookups on SVG and other non-HTML elements |
| [webpro-nl/knip](https://github.com/webpro-nl/knip) | Pipe escaping for symbols in the markdown reporter |
| [withastro/astro](https://github.com/withastro/astro) | Page-directory boundary correctness and regression coverage |
| [xuanyustudio/LocalMiniDrama](https://github.com/xuanyustudio/LocalMiniDrama) | Volcengine Omni endpoint routing for custom video providers |
| [ZSeven-W/openpencil](https://github.com/ZSeven-W/openpencil) | CLI positional argument forwarding |

## 🔥 Active Quest Queue

The newest open contributions waiting for maintainer review, ordered by creation time. **82** are open in total; the 20 most recent are listed here.

| Project | PR | Quest in progress |
| --- | --- | --- |
| [msgspec](https://github.com/msgspec/msgspec) | [#1320](https://github.com/msgspec/msgspec/pull/1320) | Caps the integer part of each ISO 8601 duration segment at the largest `timedelta` in seconds rather than `2**47`, so day counts like `P106751991167301D` raise `ValidationError` instead of wrapping to a wrong `timedelta` or a bare `OverflowError`. |
| [Floating UI](https://github.com/floating-ui/floating-ui) | [#3540](https://github.com/floating-ui/floating-ui/pull/3540) | Skips disabled cells when `useListNavigation` or `Composite` loops vertically in a grid with `cols > 1`, so `ArrowUp` from the top row lands on the nearest enabled item in the column and `ArrowDown` wraps even when every cell below is disabled. |
| [insta](https://github.com/mitsuhiko/insta) | [#958](https://github.com/mitsuhiko/insta/pull/958) | Writes an indentation indicator such as `\|2-` for YAML literal blocks whose first line starts with a space or tab, so with `INSTA_YAML_BLOCK_STYLE=1` that leading whitespace survives a read and the snapshot file still parses. |
| [eslint-plugin-vue](https://github.com/vuejs/eslint-plugin-vue) | [#3231](https://github.com/vuejs/eslint-plugin-vue/pull/3231) | Makes a bare `<!-- eslint-enable -->` in `<template>` clear rule-specific block disables, and `<!-- eslint-enable vue/no-v-html -->` re-enable that rule under a bare `<!-- eslint-disable -->`, so template directives turn rules back on where ESLint does instead of keeping them off until `</template>`. |
| [Crossterm](https://github.com/crossterm-rs/crossterm) | [#1159](https://github.com/crossterm-rs/crossterm/pull/1159) | Implements `Ord` and `PartialOrd` for `KeyEvent` on the same case-normalized fields that `eq` and `hash` use, so a `BTreeMap` or `BTreeSet` keyed by `KeyEvent` or `Event` finds Shift+letter bindings that a `HashMap` already finds. |
| [Sarama](https://github.com/IBM/sarama) | [#3848](https://github.com/IBM/sarama/pull/3848) | Unlocks `txnLock` before the transactional `mocks.AsyncProducer` reports a message sent outside a transaction, so the violation fails fast instead of blocking `BeginTxn`, `CommitTxn`, `TxnStatus` and the next input until the `go test` timeout. |
| [zerolog](https://github.com/rs/zerolog) | [#826](https://github.com/rs/zerolog/pull/826) | Computes `TimeFormatUnixMs` and `TimeFormatUnixMicro` values the way `UnixMilli` and `UnixMicro` do instead of dividing `UnixNano`, so times before 1678 or after 2262, like the zero `time.Time`, are no longer logged as unrelated dates. |
| [unimport](https://github.com/unjs/unimport) | [#579](https://github.com/unjs/unimport/pull/579) | Checks for leftover Vue directives with `String#search` instead of `RE_DIRECTIVE.test()`, so the global regex keeps no stale `lastIndex` and a repeated or following transform no longer skips directive imports or drops the `resolveDirective` import. |
| [Magicast](https://github.com/unjs/magicast) | [#188](https://github.com/unjs/magicast/pull/188) | Builds non-identifier keys of assigned objects as `StringLiteral` nodes, so the object proxy can read, list, delete and overwrite a key like `"@"` it just wrote, and a second `deepMergeObject` merges instead of adding a duplicate key. |
| [vscode-pull-request-github](https://github.com/microsoft/vscode-pull-request-github) | [#9097](https://github.com/microsoft/vscode-pull-request-github/pull/9097) | Decodes the percent-encoded path of blob permalinks before the local file check, so links in PR and issue overviews to files like `docs/My Notes.md` or `app/[slug]/page.tsx` open locally instead of staying plain GitHub links. |
| [jq](https://github.com/jqlang/jq) | [#3695](https://github.com/jqlang/jq/pull/3695) | Passes every digit of a number literal to `jvp_strtod()` rather than rounding to 17 significant digits first, so `100000000000000041 * 1` prints `100000000000000050` like a `--disable-decnum` build instead of `100000000000000030`. |
| [Koa](https://github.com/koajs/koa) | [#2022](https://github.com/koajs/koa/pull/2022) | Gives a JSON `null` body the same status and length handling as a string body, so `ctx.type = 'json'; ctx.body = null` responds `200` instead of `404` and no longer keeps a stale `Content-Length` that leaves clients waiting. |
| [vscode-eslint](https://github.com/microsoft/vscode-eslint) | [#2251](https://github.com/microsoft/vscode-eslint/pull/2251) | Adds the problem's fixability to the rule severity cache key, so an `eslint.rules.customizations` entry with `fixable` applies to each problem instead of letting the first problem of a rule like `eqeqeq` decide for all later ones. |
| [Supabase JS SDK](https://github.com/supabase/supabase-js) | [#2790](https://github.com/supabase/supabase-js/pull/2790) | Writes the `Resources:` header with its colon when `signInWithWeb3` builds a Sign-In-With-Solana message for a wallet without `signIn()`, so the Auth server parses messages that list `resources` instead of rejecting them with 400 `validation_failed`. |
| [Payload](https://github.com/payloadcms/payload) | [#19049](https://github.com/payloadcms/payload/pull/19049) | Sends `fallback-locale=false` when an SDK call passes `fallbackLocale: false`, so the REST API turns locale fallback off instead of filling untranslated localized fields with default-locale content. |
| [Hugging Face Datasets](https://github.com/huggingface/datasets) | [#8891](https://github.com/huggingface/datasets/pull/8891) | Ignores `.md` and `.toml` files other than `task.toml` and `instruction.md` when inferring the builder, so folders with a `LICENSE.md` or `pyproject.toml` beside their data load with the `json`, `csv` or `fasta` builder instead of failing as a Harbor dataset. |
| [PixiJS](https://github.com/pixijs/pixijs) | [#12335](https://github.com/pixijs/pixijs/pull/12335) | Reads `x` and `y` into locals before writing in math-extras `Point.rotate`, so `p.rotate(radians, p)` on a `Point` or `ObservablePoint` no longer computes `y` from the already rotated `x`. |
| [axum](https://github.com/tokio-rs/axum) | [#3972](https://github.com/tokio-rs/axum/pull/3972) | Returns `None` from `Option<Path<T>>` and `Option<InnerPath<T>>` on a route without captures for every `T`, not only scalars and tuples, so a struct target on `/users` no longer gets a 400 `missing field` error. |
| [chi](https://github.com/go-chi/chi) | [#1240](https://github.com/go-chi/chi/pull/1240) | Collapses consecutive `/*/` subrouter connectors in `Walk` the same way `RoutePattern()` does, so a `Route("/")` inside a mounted subrouter is walked as `/v1/resources/{resource_id}` instead of keeping a stray `/*`. |
| [Tailwind CSS](https://github.com/tailwindlabs/tailwindcss) | [#20612](https://github.com/tailwindlabs/tailwindcss/pull/20612) | Rebases the `url()`s that sit next to an `image-set()` in an imported stylesheet, so Vite no longer warns about and drops images like `overlay.png`, while the URLs inside `image-set()` are still rewritten only once. |

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
