# MD Converter

> **Markdown → DOCX & PDF** — free, in-browser, zero server, zero tracking.

[![Live Demo](https://img.shields.io/badge/Live-Demo-01696f?style=flat-square)](https://sssskyds.github.io/md-converter/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE)

## Features

| Feature | DOCX | PDF |
|---|:---:|:---:|
| H1 – H6 headings (with inline bold/italic/links) | ✅ | ✅ |
| **Bold**, *italic*, ***bold-italic*** | ✅ | ✅ |
| `Inline code` spans | ✅ | ✅ |
| Fenced code blocks | ✅ | ✅ |
| Unordered lists | ✅ | ✅ |
| Ordered lists | ✅ | ✅ |
| Blockquotes (nested `>>` supported) | ✅ | ✅ |
| Tables | ✅ | ✅ |
| Horizontal rules | ✅ | ✅ |
| Hyperlinks (clickable) | ✅ | ✅ |
| 5 colour themes (Teal, Blue, Purple, Warm, Minimal) | ✅ | ✅ |
| Font & size selection | ✅ | — |
| A4 / Letter page size | ✅ | ✅ |
| Selectable text (no image snapshots) | — | ✅ |
| Live Markdown preview | ✅ | ✅ |
| Drag-and-drop file upload | ✅ | ✅ |
| Light / Dark mode | ✅ | ✅ |

## Usage

1. **Upload** a `.md`, `.markdown`, or `.txt` file — or switch to the **Paste / type** tab.
2. Choose your **font**, **page size**, and **colour theme**.
3. Click **Download DOCX** or **Download PDF**.

Everything runs locally in your browser. No files are ever sent to a server.

## Keyboard Shortcut

| Shortcut | Action |
|---|---|
| `Ctrl / ⌘` + `Enter` | Download DOCX from the editor tab |

## Tech Stack

- [marked.js](https://marked.js.org/) — Markdown parsing & live preview
- [jsPDF](https://rawgit.com/MrRio/jsPDF/master/docs/) — native-text PDF generation (no html2canvas)
- [docx.js](https://docx.js.org/) v8.5 — DOCX generation

## Development

This is a single static HTML file — no build step required.

```bash
# Clone and open directly in your browser
git clone https://github.com/sssskyds/md-converter.git
open md-converter/index.html
```

## License

MIT © [Ajeet Kumar Sharma](https://github.com/sssskyds)
