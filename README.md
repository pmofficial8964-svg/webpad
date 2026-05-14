# 🖊️ Webpad

A browser-based code editor inspired, with syntax highlighting, multiple tabs, find & replace, and file open/save — all in a single HTML file.

**[▶ Live Demo](https://YOUR_USERNAME.github.io/YOUR_REPO_NAME)**

---

## ✨ Features

- 🎨 **Syntax Highlighting** — JavaScript, Python, HTML, CSS, JSON
- 🗂️ **Multiple Tabs** — open, close, and switch between files
- 🔢 **Line Numbers** with minimap
- 🔍 **Find & Replace** — with regex and case-sensitive support
- 📂 **File Open / Save** — read local files, download your work
- ↩️ **Undo / Redo** — full history per tab
- 🌯 **Word Wrap** toggle
- 🔠 **Font Size** controls
- 🖱️ **Right-click Context Menu**
- 📊 **Status Bar** — line, column, word count, character count
- 🖥️ **OS Detection** — auto-detects Windows, macOS, Linux, Android, iOS and adapts shortcuts accordingly
- 📱 **Mobile Toolbar** — quick-action buttons on Android & iOS

---

## ⌨️ Keyboard Shortcuts

Webpad automatically detects your operating system and displays the correct shortcuts in all menus and tooltips.

### 🪟 Windows & 🐧 Linux

| Action | Shortcut |
|---|---|
| New File | `Ctrl + N` |
| Open File | `Ctrl + O` |
| Save File | `Ctrl + S` |
| Find / Replace | `Ctrl + F` |
| Find Next | `F3` |
| Find Previous | `Shift + F3` |
| Undo | `Ctrl + Z` |
| Redo | `Ctrl + Y` |
| Cut | `Ctrl + X` |
| Copy | `Ctrl + C` |
| Paste | `Ctrl + V` |
| Select All | `Ctrl + A` |
| Duplicate Line | `Ctrl + D` |
| Zoom In | `Ctrl + =` |
| Zoom Out | `Ctrl + -` |
| Indent (Tab) | `Tab` |
| Close Find Bar | `Escape` |

---

### 🍎 macOS & 📱 iOS

| Action | Shortcut |
|---|---|
| New File | `⌘ + N` |
| Open File | `⌘ + O` |
| Save File | `⌘ + S` |
| Find / Replace | `⌘ + F` |
| Find Next | `F3` |
| Find Previous | `⇧ + F3` |
| Undo | `⌘ + Z` |
| Redo | `⌘ + ⇧ + Z` |
| Cut | `⌘ + X` |
| Copy | `⌘ + C` |
| Paste | `⌘ + V` |
| Select All | `⌘ + A` |
| Duplicate Line | `⌘ + D` |
| Zoom In | `⌘ + =` |
| Zoom Out | `⌘ + -` |
| Indent (Tab) | `Tab` |
| Close Find Bar | `Escape` |

---

### 🤖 Android & 📱 iOS (Mobile)

Physical keyboard shortcuts are limited on mobile, so Webpad shows a **quick-action toolbar** above the keyboard with one-tap access to:

| Button | Action |
|---|---|
| ↩ Undo | Undo last change |
| ↪ Redo | Redo last change |
| ⧉ Dup | Duplicate current line |
| 🗑 Del Line | Delete current line |
| // Comment | Toggle line comment |
| AA | Convert selection to UPPERCASE |
| aa | Convert selection to lowercase |
| 🔍 Find | Open Find & Replace bar |
| ⇥ Tab | Insert indentation |
| 💾 Save | Download file |

> On Android/iOS with a physical keyboard connected, the `⌘` or `Ctrl` shortcuts above also work.

---

## 🛠️ Edit Menu Actions

These are available via the **Edit** menu or right-click context menu on all platforms:

| Action | Description |
|---|---|
| Duplicate Line | Copies the current line below itself |
| Delete Line | Removes the current line entirely |
| Toggle Comment | Adds or removes `//` (JS) or `#` (Python) comment |
| UPPERCASE | Converts selected text to uppercase |
| lowercase | Converts selected text to lowercase |
| Trim Whitespace | Strips trailing spaces from all lines |

---

## 🔧 Tools Menu

| Tool | Description |
|---|---|
| Sort Lines A→Z | Sorts all lines alphabetically |
| Remove Duplicate Lines | Removes repeated lines |
| Word Count | Shows word, line, and character count |

---

## 🌐 Supported Languages

| Language | Highlighting |
|---|---|
| JavaScript / TypeScript | ✅ Keywords, strings, comments, numbers, functions, types |
| Python | ✅ Keywords, strings, comments, numbers, functions, built-ins |
| HTML | ✅ Tags, attributes, strings, comments |
| CSS | ✅ Properties, values, at-rules, numbers with units |
| JSON | ✅ Keys, strings, numbers, booleans, null |
| Plain Text | — No highlighting |

---

## 🚀 Getting Started

No installation needed. Just open `index.html` in any modern browser.

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME
open index.html   # macOS
start index.html  # Windows
xdg-open index.html  # Linux
```

---

## 📦 Tech Stack

- Pure HTML, CSS, and vanilla JavaScript
- Zero dependencies — no frameworks, no build step
- Single file (`index.html`)

---

## 📄 License

MIT — free to use, modify, and distribute.
