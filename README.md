# KunlunXin XPU Syntax Highlighting

A minimal Visual Studio Code extension for KunlunXin XTDK `.xpu` kernel source files.

## Features

- Recognizes `.xpu` files automatically.
- Reuses VS Code's built-in CUDA C++ grammar for C++, CUDA-style qualifiers, templates, comments, strings, and preprocessor directives.
- Adds highlighting for common XTDK constructs such as `__simd__`, `__local__`, `GM2LM`, `LM2GM`, `mfence`, and XPU topology functions.
- Contains no runtime code, network access, telemetry, compiler integration, or settings.

## Installation

Download the `.vsix` file from the latest GitHub release. In Visual Studio Code, open the Command Palette and run **Extensions: Install from VSIX...**.

To package the extension from source:

```bash
npx @vscode/vsce package
```

After installation, open any `.xpu` file. The language mode should be **XPU**.

## Scope

This extension provides syntax highlighting and basic editor behavior only. It does not provide code completion, diagnostics, formatting, compilation, or debugging.

The extension is an independent community project and is not affiliated with or endorsed by KunlunXin.

## License

[MIT](LICENSE)
