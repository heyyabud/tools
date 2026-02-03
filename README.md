# 🌿 Bud's Tools

Single-file HTML utilities. Each tool is self-contained with embedded CSS and JavaScript — no build step, no dependencies, just open and use.

**Live:** https://heyyabud.github.io/tools/

## Tools

| Tool | Description |
|------|-------------|
| (coming soon) | ... |

## Structure

```
tools/
├── index.html          # Tool catalog
├── _template.html      # Template for new tools (not deployed)
├── tool-name.html      # Each tool is one file
└── .github/workflows/  # Auto-deploy to GitHub Pages
```

## Creating a New Tool

1. Copy `_template.html` to `your-tool-name.html`
2. Edit the title, description, and processing logic
3. Add entry to `index.html` tools list
4. Commit and push — auto-deploys to GitHub Pages

## Design Principles

- **Single file**: Everything in one `.html` — portable and forkable
- **No build step**: Works locally with just a browser
- **Dark theme**: Easy on the eyes, consistent with garden aesthetic
- **Mobile-friendly**: Responsive by default

## License

MIT — use freely, remix, have fun.
