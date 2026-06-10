<p align="center">
  <img src="https://raw.githubusercontent.com/abstractwebunit/markdown-publish/main/.github/media/logo.svg" width="80" alt="logo">
</p>

<h1 align="center">Шаблон сайта заметок</h1>

<p align="center">
  Твои Markdown/Obsidian-заметки → быстрый сайт: поиск, граф связей, тёмная тема.<br>
  <sub>Starter template for <a href="https://github.com/abstractwebunit/markdown-publish">markdown-publish</a> · English docs <a href="https://abstractwebunit.github.io/markdown-publish-docs/en/">here</a></sub>
</p>

<p align="center">
  <b>Документация и живое демо:</b>
  <a href="https://abstractwebunit.github.io/markdown-publish-docs/">Русский</a> ·
  <a href="https://abstractwebunit.github.io/markdown-publish-docs/en/">English</a> ·
  <a href="https://abstractwebunit.github.io/markdown-publish-docs/es/">Español</a> ·
  <a href="https://abstractwebunit.github.io/markdown-publish-docs/de/">Deutsch</a> ·
  <a href="https://abstractwebunit.github.io/markdown-publish-docs/fr/">Français</a> ·
  <a href="https://abstractwebunit.github.io/markdown-publish-docs/zh/">中文</a>
</p>

![Так выглядит опубликованный сайт](https://raw.githubusercontent.com/abstractwebunit/markdown-publish/main/.github/media/home.png)

## Опубликовать за пару кликов

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/abstractwebunit/markdown-publish-template)
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/abstractwebunit/markdown-publish-template&project-name=my-notes&repository-name=my-notes)

Кнопка создаст копию этого шаблона в твоём GitHub и сразу соберёт сайт. Дальше просто кладёшь `.md`-файлы в папку `vault/` — сайт пересобирается сам.

**Через GitHub Pages (без сторонних сервисов):** нажми **Use this template** → в новом репозитории включи **Settings → Pages → Source: GitHub Actions** → запусти workflow «Publish site» во вкладке Actions.

## Структура

| Что | Зачем |
|---|---|
| `vault/` | Твои заметки — это и есть сайт |
| `markdown-publish.config.json` | Название сайта, язык, режим публикации |
| `.github/workflows/publish.yml` | Автосборка для GitHub Pages |
| `netlify.toml`, `vercel.json` | Конфиги для кнопок выше |

Как обновлять сайт, скрывать заметки, менять имя — [в документации](https://abstractwebunit.github.io/markdown-publish-docs/).

---

<sub>Сделано на <a href="https://github.com/abstractwebunit/markdown-publish">markdown-publish</a> (MIT). Не аффилировано с Obsidian.MD.</sub>
