<div align="center">

<img src="https://raw.githubusercontent.com/vergil-astro/vergil-astro-theme/main/public/favicon.svg" width="96" alt="Vergil">

# Vergil

**写 Markdown，剩下的交给主题。**

一套基于 Astro 的内容站点主题。博客、文档、相册、项目展示放在同一个站点里，提示框、时间线、图表、看板这些都写成 Markdown 指令就行，不用写组件，也不用碰 CSS。

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
