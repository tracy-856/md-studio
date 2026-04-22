# ✏️ MD Studio

**Tired of editing Markdown blindly in a text editor, then switching to a preview just to check formatting?**

MD Studio lets you edit Markdown directly on the rendered output — like editing a Google Doc, but for Markdown. Upload your `.md` file, see it beautifully rendered, then click anywhere to start editing. What you see is what you get.

![Dark Theme](https://img.shields.io/badge/theme-dark%20%2F%20light-blueviolet)
![No Build](https://img.shields.io/badge/build-none%20required-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)

## 💡 Why MD Studio?

- **No more context switching** — stop jumping between editor and preview. Edit headings, tables, lists, and bold text right on the rendered page.
- **See your diagrams instantly** — Mermaid flowcharts, sequence diagrams, and more render in real-time as you write.
- **Never lose your work** — built-in version snapshots with full diff comparison. See exactly what changed between any two versions.
- **Works anywhere** — no install, no sign-up, no server. Open it in a browser and start editing.

## ✨ Features

| Feature | Description |
|---------|-------------|
| 📝 **WYSIWYG Editing** | Click on the rendered Markdown and start typing — headings, lists, tables, all editable in place |
| 🔀 **Mermaid Diagrams** | Auto-renders `flowchart`, `sequenceDiagram`, `classDiagram`, and more |
| 📋 **Version Snapshots** | Save snapshots, restore any version, download specific versions |
| 🔍 **Diff Comparison** | Compare any two versions with line-by-line red/green highlighting |
| 🌙 **Dark / Light Theme** | One-click toggle with auto-saved preference |
| 💾 **Persistent Storage** | All versions and edits saved to IndexedDB — survives page refresh and browser restart |
| 🖥️ **Split View** | Side-by-side rendered + source with synchronized scrolling |
| ⬇️ **Import / Export** | Drag-and-drop upload, download current or any historical version as `.md` |

## 🚀 Getting Started

**No installation needed.** Just open `index.html` in any modern browser.

```bash
git clone https://github.com/tracy-856/md-studio.git
open md-studio/index.html
```

Or use the hosted version: **https://tracy-856.github.io/md-studio/**

### Optional: Serve locally

```bash
cd md-studio
python3 -m http.server 8080
# Visit http://localhost:8080
```

## 🏗️ Tech Stack

All dependencies loaded from CDN — zero build step:

- [marked](https://github.com/markedjs/marked) — Markdown → HTML parsing
- [turndown](https://github.com/mixmark-io/turndown) — HTML → Markdown conversion (WYSIWYG sync)
- [mermaid](https://github.com/mermaid-js/mermaid) — Diagram rendering
- [jsdiff](https://github.com/kpdecker/jsdiff) — Diff computation
- [github-markdown-css](https://github.com/sindresorhus/github-markdown-css) — GitHub-flavored styling

## 🤝 Contributing

Contributions welcome! Feel free to open issues or submit PRs.

## 📄 License

[MIT](LICENSE)
