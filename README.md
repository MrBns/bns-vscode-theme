# BNS VSCode Theme

A modern, visually pleasing dark and light color theme for Visual Studio Code, built on up-to-date VSCode extension conventions.

## Themes Included

| Theme | Type | Description |
|-------|------|-------------|
| **BNS Dark** | Dark | Rich dark theme with vivid, accessible colors |
| **BNS Light** | Light | Clean light theme with clear, readable colors |

## Installation

1. Open **Extensions** in VS Code (`Ctrl+Shift+X` / `Cmd+Shift+X`)
2. Search for **BNS VSCode Theme**
3. Click **Install**
4. Open the Command Palette (`Ctrl+K Ctrl+T` / `Cmd+K Cmd+T`) and select your preferred variant

## Manual Installation (from source)

```bash
git clone https://github.com/MrBns/bns-vscode-theme
cd bns-vscode-theme
# Copy or symlink to your VS Code extensions directory
# Linux/macOS: ~/.vscode/extensions/
# Windows:     %USERPROFILE%\.vscode\extensions\
```

## Features

- ✅ Full **Semantic Highlighting** support (`semanticHighlighting: true`)
- ✅ Comprehensive **workbench color** customizations (editor, sidebar, status bar, terminal, …)
- ✅ **TextMate token colors** for syntax highlighting across all major languages
- ✅ **Semantic token colors** for context-aware highlighting (TypeScript, Python, Rust, Go, …)
- ✅ Covers HTML/JSX, CSS/SCSS, JSON, Markdown, Shell, and more
- ✅ Distinct colors for classes, interfaces, enums, decorators, and regex
- ✅ Carefully tuned terminal ANSI palette

## Supported Languages

JavaScript · TypeScript · Python · Rust · Go · Java · C/C++ · HTML · CSS/SCSS · JSON · YAML · Markdown · Shell · and more

## Color Palette

### BNS Dark (Catppuccin Mocha-inspired)

| Role | Color |
|------|-------|
| Background | `#1e1e2e` |
| Foreground | `#cdd6f4` |
| Keywords | `#cba6f7` |
| Strings | `#a6e3a1` |
| Functions | `#89b4fa` |
| Classes | `#f38ba8` |
| Numbers | `#fab387` |

### BNS Light (Catppuccin Latte-inspired)

| Role | Color |
|------|-------|
| Background | `#eff1f5` |
| Foreground | `#4c4f69` |
| Keywords | `#8839ef` |
| Strings | `#40a02b` |
| Functions | `#1e66f5` |
| Classes | `#d20f39` |
| Numbers | `#fe640b` |

## Contributing

Issues and pull requests are welcome at [github.com/MrBns/bns-vscode-theme](https://github.com/MrBns/bns-vscode-theme/issues).

> **Adding an icon:** Place a 256×256 PNG file at `images/icon.png` and add `"icon": "images/icon.png"` to `package.json` before publishing to the Marketplace.

## License

[MIT](LICENSE)
