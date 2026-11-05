<div align="center">

<img src="https://raw.githubusercontent.com/vergil-astro/vergil-astro-theme/main/public/favicon.svg" width="96" alt="Vergil">

# Vergil

</div>

<details>
<summary>简体中文（点击展开 / 收起）</summary>

<div align="center">

**基于 Astro 的博客、文档与个人站点主题。提示框、标签页、时间线、图表、相册、思维导图都用 Markdown 指令来写，不用写组件。**

博客、知识库文档、相册、项目展示都能放在同一个站点里，也不用碰 CSS。访客还能在页面上自己切换皮肤和配色。

[在线演示](https://vergil-astro-theme.vercel.app/) · [使用文档](https://vergil-astro-theme.vercel.app/docs/) · [主题仓库](https://github.com/vergil-astro/vergil-astro-theme)

![Vergil 深色文档页与浅色首页](https://raw.githubusercontent.com/vergil-astro/vergil-astro-theme/main/public/assets/site/vergil-preview.jpg)

</div>

## 仓库

[vergil-astro-theme](https://github.com/vergil-astro/vergil-astro-theme) 是主题本体，页面、样式、51 个内容指令和知识库文档都在这里，还有内置的 classic 皮肤和 A–I、K 配色。

[vergil-cli](https://github.com/vergil-astro/vergil-cli) 是命令行工具 `vg`，用来初始化站点，在终端里新建文章、页面、相册、动态和文档，发布草稿、本地预览、构建和部署，也能用 `vg skin` 安装和切换皮肤。它支持 `--json` 输出，agent 和脚本也能直接调用。

[vergil-skills](https://github.com/vergil-astro/vergil-skills) 是 agent 插件，让 AI 助手用 Vergil 的内容指令帮你写文章、排版，每次改完自动检查指令写法。Claude Code 里从插件市场安装；Codex CLI、Cursor 等用 `npx skills add vergil-astro/vergil-skills` 装上写作技能。

[vergil-skins](https://github.com/vergil-astro/vergil-skins) 收录 Vergil 的皮肤，官方的 island 和 brutalism 都在这里。谁都可以提 PR 加一个 `skins/<名字>/`，CI 会检查清单和 CSS 作用域，再完整构建一遍主题。用 `vg skin add <名字>` 安装。

## 快速开始

需要 Node.js 22 和 pnpm。

```bash
git clone https://github.com/vergil-astro/vergil-astro-theme.git my-blog
cd my-blog
pnpm install
pnpm dev
```

用命令行工具也行，在一个空目录里运行：

```bash
mkdir my-blog && cd my-blog
npx @vergil-astro/vergil-cli init
```

</details>

<details open>
<summary>English (click to collapse / expand)</summary>

<div align="center">

**An Astro theme for blogs, docs and personal sites. Callouts, tabs, timelines, charts, galleries and mind maps are Markdown directives — no components to write.**

Your blog, knowledge-base docs, galleries and projects can all live on one site, and you never have to touch CSS. Visitors can even switch skins and color schemes on the page.

[Live demo](https://vergil-astro-theme.vercel.app/) · [Documentation](https://vergil-astro-theme.vercel.app/docs/) · [Theme repository](https://github.com/vergil-astro/vergil-astro-theme)

![Vergil documentation in dark mode and homepage in light mode](https://raw.githubusercontent.com/vergil-astro/vergil-astro-theme/main/public/assets/site/vergil-preview.jpg)

</div>

## Repositories

[vergil-astro-theme](https://github.com/vergil-astro/vergil-astro-theme) is the theme itself. Pages, styles, all 51 content directives and knowledge-base docs live here, along with the built-in classic skin and color schemes A–I and K.

[vergil-cli](https://github.com/vergil-astro/vergil-cli) is the `vg` command-line tool. It sets up new sites, creates posts, pages, galleries, moments, and docs from the terminal, publishes drafts, handles local preview, builds, and deployment, and installs and switches skins with `vg skin`. With `--json` output, agents and scripts can call it directly.

[vergil-skills](https://github.com/vergil-astro/vergil-skills) is an agent plugin that helps AI assistants write and typeset posts with Vergil's content directives, and checks directive syntax after every edit. Install it from the plugin marketplace in Claude Code; Codex CLI, Cursor, and others can get the writing skill with `npx skills add vergil-astro/vergil-skills`.

[vergil-skins](https://github.com/vergil-astro/vergil-skins) collects Vergil skins, including the official island and brutalism. Anyone can open a PR that adds `skins/<name>/`; CI checks the manifest and CSS scoping, then runs a full theme build. Install one with `vg skin add <name>`.

## Quick Start

Requires Node.js 22 and pnpm.

```bash
git clone https://github.com/vergil-astro/vergil-astro-theme.git my-blog
cd my-blog
pnpm install
pnpm dev
```

Or use the CLI. Run this in an empty directory:

```bash
mkdir my-blog && cd my-blog
npx @vergil-astro/vergil-cli init
```

</details>
