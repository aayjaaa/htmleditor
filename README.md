# ⚡ HTML Live Editor

A single-file, browser-based HTML editor with live preview and visual editing mode.
No server, no installation, no dependencies — just open and use.

![HTML Live Editor demo](html_editor-ezgif.com-video-to-gif-converter.gif)

---

## Features

- **Live Preview** — paste HTML on the left, click ▶ to render on the right
- **Visual Edit Mode** — click directly on preview text to edit it, then sync back to code
- **Multi-language UI** — English, 한국어, Español, 中文(简体)
- **HTML Formatter** — auto-indent cleanup with one click
- **File Drop** — drag & drop any `.html` file to load it instantly
- **Resizable panes** — drag the center divider to adjust editor/preview ratio
- **Line numbers** — synced scroll with the editor
- **Copy to clipboard** — grab the full HTML with one click

---

## Usage

### Basic (Code → Preview)

1. Open `html-live-editor.html` in any modern browser
2. Paste your HTML into the left pane
3. Click **▶ Apply Preview** (or press `F5`)

### Visual Editing (Preview → Code)

1. Click **✏️ Visual Edit** to enable edit mode
2. Click any text in the preview to edit it directly
3. Click **✅ Apply to Code** to sync changes back to the editor

---

## Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `F5` | Apply preview |
| `Ctrl + E` | Toggle visual edit mode |
| `Ctrl + Shift + C` | Copy all HTML to clipboard |
| `Tab` | Indent (2 spaces) |
| `Tab` on selection | Indent multiple lines |

---

## Language Support

Switch UI language from the dropdown in the top-right corner.
Changing language while in demo mode also swaps the demo content.

| Language | Code |
|----------|------|
| English | `en` |
| 한국어 | `ko` |
| Español | `es` |
| 中文(简体) | `zh` |

---

## Browser Compatibility

| Browser | Support |
|---------|---------|
| Chrome / Edge | ✅ Full |
| Firefox | ✅ Full |
| Safari | ⚠️ Visual Edit may vary |

> Visual Edit mode uses `iframe.contentDocument` to access the preview DOM directly.
> This works because `srcdoc` iframes are same-origin with the parent page.

---

## Installation

None required. Download and open:

```
html-live-editor.html
```

That's it.

---

## License

MIT
