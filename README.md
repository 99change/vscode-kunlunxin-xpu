# KunlunXin XPU Syntax Highlighting

<p align="center">
  <img src="assets/icon.png" alt="XPU Syntax Highlighting logo" width="160">
</p>

`.xpu` files looking a little gray? This tiny extension tells VS Code, "Just treat them like CUDA C++." Colors are back. That's it.

## What It Does

It makes VS Code treat `.xpu` files like CUDA C++ for syntax highlighting.

## Installation

Download the `.vsix` file from the latest GitHub release. In Visual Studio Code, open the Command Palette and run **Extensions: Install from VSIX...**.

To package the extension from source:

```bash
npx @vscode/vsce package
```

After installation, open any `.xpu` file. The language mode should be **XPU**.

The extension is an independent community project and is not affiliated with or endorsed by KunlunXin.

## License

[MIT](LICENSE)
