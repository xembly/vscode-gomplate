# Visual Studio Code - Go Template Syntax

[![Visual Studio Marketplace](https://img.shields.io/visual-studio-marketplace/v/xembly.gomplate?label=VS%20Marketplace)](https://marketplace.visualstudio.com/items?itemName=xembly.gomplate)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Syntax highlighting and language support for Go's [`text/template`](https://pkg.go.dev/text/template) and [`html/template`](https://pkg.go.dev/html/template) packages in Visual Studio Code.

## Features

Supports Go template syntax embedded within many host languages, each registered as a distinct language ID:

| Language ID    | File Extensions / Patterns                                  |
|----------------|-------------------------------------------------------------|
| `gomplate`   | `.gotmpl`, `.tmpl`, `.tpl`                                  |
| `gohtml`       | `.gohtml`, `.html.tmpl`, `.html.tpl`, `.html.gotmpl`        |
| `goyaml`       | `.yml.tmpl`, `.yaml.tmpl`, `.yaml.tpl`, `.yaml.gotmpl`      |
| `gojs`         | `.gojs`, `.js.tmpl`, `.js.tpl`, `.js.gotmpl`                |
| `gots`         | `.gots`, `.ts.tmpl`, `.ts.tpl`, `.ts.gotmpl`                |
| `gojson`       | `.json.tmpl`, `.json.tpl`, `.json.gotmpl`                   |
| `gocss`        | `.gocss`, `.css.tmpl`, `.css.tpl`                           |
| `goshell`      | `.gosh`, `*.sh.tmpl`, `*.bash.tmpl`, `*.zsh.tmpl`, etc.     |
| `gophp`        | `.gophp`, `.php.tmpl`, `.php.tpl`, `.php.gotmpl`            |
| `gojava`       | `.gojava`, `.java.tmpl`, `.java.tpl`, `.java.gotmpl`        |
| `gogo`         | `.gogo`, `.go.tmpl`, `.go.tpl`                              |
| `godockerfile` | `.godockerfile`, `.Dockerfile.tmpl`, `.Dockerfile.gotmpl`   |
| `goR`          | `.goR`, `.R.tmpl`, `.R.tpl`, `.R.gotmpl`                    |

Go template delimiters (`{{`, `}}`) are highlighted inside all supported host languages via a TextMate grammar injection.

## Installation

Search for **gomplate template renderer** in the VS Code Extensions panel, or install via the command line:

```bash
code --install-extension xembly.gomplate
```

## Source

Source code: <https://github.com/xembly/vscode-gomplate>

Originally developed by [casualjim](https://github.com/casualjim/vscode-gotemplate). Imported from GoSublime.

## License

[MIT](LICENSE)
