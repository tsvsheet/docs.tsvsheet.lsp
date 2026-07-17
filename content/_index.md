---
title: Home
---

**tsvsheet.lsp** is the language server for [tsvsheet](https://github.com/tsvsheet/tsvsheet): the `tsvsheet-lsp` binary speaks the Language Server Protocol over stdio, computing a `.tsvt` spreadsheet with the [go-tsvsheet](https://github.com/tsvsheet/go-tsvsheet) engine to surface diagnostics (bad references, cycles, error values) and hover information (a cell's formula, inputs, and computed value) in any LSP-capable editor.

- Source: [tsvsheet/tsvsheet.lsp](https://github.com/tsvsheet/tsvsheet.lsp)
- Engine: [tsvsheet/go-tsvsheet](https://github.com/tsvsheet/go-tsvsheet)
- Language: [tsvsheet/tsvsheet](https://github.com/tsvsheet/tsvsheet)
