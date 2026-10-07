<div align="center">

<img src="https://raw.githubusercontent.com/vergil-astro/vergil-astro-theme/main/public/favicon.svg" width="96" alt="Vergil">

# Vergil

</div>

<details>
<summary>简体中文（点击展开 / 收起）</summary>

<div align="center">

**基于 Astro 的博客与文档主题。提示框、时间线、图表、相册都用 Markdown 指令来写，不用写组件。**

博客、文档、相册、项目展示都能放在同一个站点里，也不用碰 CSS。

[在线演示](https://vergil-astro-theme.vercel.app/) · [使用文档](https://vergil-astro-theme.vercel.app/docs/) · [主题仓库](https://github.com/vergil-astro/vergil-astro-theme)

![Vergil 深色文档页与浅色首页](https://raw.githubusercontent.com/vergil-astro/vergil-astro-theme/main/public/assets/site/vergil-preview.jpg)

</div>

## 仓库

[vergil-astro-theme](https://github.com/vergil-astro/vergil-astro-theme) 是主题本体，页面、样式和 50 个内容指令都在这里。

[vergil-cli](https://github.com/vergil-astro/vergil-cli) 是命令行工具 `vg`，用来初始化站点，在终端里新建文章、相册、文档，以及本地预览和部署。

[vergil-writing-skills](https://github.com/vergil-astro/vergil-writing-skills) 是给 Claude Code、Codex、Cursor 这类 AI 编程助手用的写作技能，让它帮你把普通的 Markdown 改成用上 Vergil 指令的文章。

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

**An Astro theme for blogs and docs. Callouts, timelines, charts and galleries are Markdown directives — no components to write.**

Your blog, docs, galleries and projects can all live on one site, and you never have to touch CSS.

[Live demo](https://vergil-astro-theme.vercel.app/) · [Documentation](https://vergil-astro-theme.vercel.app/docs/) · [Theme repository](https://github.com/vergil-astro/vergil-astro-theme)

![Vergil documentation in dark mode and homepage in light mode](https://raw.githubusercontent.com/vergil-astro/vergil-astro-theme/main/public/assets/site/vergil-preview.jpg)

</div>

## Repositories

[vergil-astro-theme](https://github.com/vergil-astro/vergil-astro-theme) is the theme itself. Pages, styles, and all 50 content directives live here.

[vergil-cli](https://github.com/vergil-astro/vergil-cli) is the `vg` command-line tool. It sets up new sites, creates posts, galleries, and docs from the terminal, and handles local preview and deployment.

[vergil-writing-skills](https://github.com/vergil-astro/vergil-writing-skills) gives AI coding assistants like Claude Code, Codex, and Cursor a set of writing skills, so they can turn plain Markdown into posts that use Vergil directives.

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
