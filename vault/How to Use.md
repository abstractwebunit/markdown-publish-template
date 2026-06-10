# How to Use

## Add a note

Create a `.md` file in the `vault/` folder — it becomes a page. Subfolders become sections in the navigation.

## Links and the graph

A `[[Note Name]]` link creates a connection: it shows up in backlinks and in the graph (the "Graph view" button).

## Hide a note

In `markdown-publish.config.json` set `"buildMode": "public"` — then only notes that start with this get published:

```markdown
---
publish: public
---
```

## Settings and full guides

Every config key and feature is covered in the docs: https://abstractwebunit.github.io/markdown-publish-docs/en/
