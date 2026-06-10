# Шаблон сайта заметок (markdown-publish)

Твои Markdown/Obsidian-заметки → быстрый статический сайт: поиск, граф связей, тёмная тема.

**Документация и живое демо:** https://abstractwebunit.github.io/markdown-publish/

## Опубликовать за пару кликов

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/abstractwebunit/markdown-publish-template)
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/abstractwebunit/markdown-publish-template&project-name=my-notes&repository-name=my-notes)

Или через GitHub Pages: нажми **Use this template** → в новом репозитории включи **Settings → Pages → Source: GitHub Actions** → запусти workflow «Publish site» во вкладке Actions.

## Структура

- `vault/` — твои заметки (`.md`), это и есть сайт
- `markdown-publish.config.json` — название сайта, язык и прочее
- `.github/workflows/publish.yml` — автосборка для GitHub Pages
- `netlify.toml`, `vercel.json` — конфиги для Netlify/Vercel

Сделано на [markdown-publish](https://github.com/abstractwebunit/markdown-publish) (MIT). Не аффилировано с Obsidian.MD.
