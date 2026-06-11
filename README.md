<p align="center">
  <img src="https://raw.githubusercontent.com/abstractwebunit/markdown-publish/main/.github/media/logo.svg" width="80" alt="logo">
</p>

<h1 align="center">Notes site template</h1>

<p align="center">
  Your Markdown/Obsidian notes → a fast static website: search, link graph, dark theme.<br>
  <sub>A free alternative to Obsidian Publish · Starter template for <a href="https://github.com/abstractwebunit/markdown-publish">markdown-publish</a></sub>
</p>

<p align="center">
  <b>Docs & live demo:</b>
  <a href="https://abstractwebunit.github.io/markdown-publish-docs/en/">English</a> ·
  <a href="https://abstractwebunit.github.io/markdown-publish-docs/">Русский</a> ·
  <a href="https://abstractwebunit.github.io/markdown-publish-docs/es/">Español</a> ·
  <a href="https://abstractwebunit.github.io/markdown-publish-docs/de/">Deutsch</a> ·
  <a href="https://abstractwebunit.github.io/markdown-publish-docs/fr/">Français</a> ·
  <a href="https://abstractwebunit.github.io/markdown-publish-docs/zh/">中文</a>
</p>

![What your published site looks like](https://raw.githubusercontent.com/abstractwebunit/markdown-publish/main/.github/media/home.png)

## Publish in a couple of clicks

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/abstractwebunit/markdown-publish-template)
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/abstractwebunit/markdown-publish-template&project-name=my-notes&repository-name=my-notes)

A button clones this template into your GitHub and builds the site. Then just drop `.md` files into `vault/` — the site rebuilds on every commit.

**Via GitHub Pages (no third-party services):** click **Use this template** → in your new repository enable **Settings → Pages → Source: GitHub Actions** → run the «Publish site» workflow in the Actions tab.

## Structure

| What | Why |
|---|---|
| `vault/` | Your notes — this is the site |
| `markdown-publish.config.json` | Site name, language, publish mode |
| `.github/workflows/publish.yml` | Auto-build for GitHub Pages |
| `netlify.toml`, `vercel.json` | Configs for the buttons above |

How to update the site, hide notes, rename things — [in the docs](https://abstractwebunit.github.io/markdown-publish-docs/en/).

---

<sub>Built with <a href="https://github.com/abstractwebunit/markdown-publish">markdown-publish</a> (MIT). Not affiliated with Obsidian.MD.</sub>
