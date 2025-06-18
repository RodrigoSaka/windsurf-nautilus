# Windsurf Nautilus Extension

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 🚀 Description

This extension adds Windsurf support to Nautilus file manager, allowing you to open files and folders directly from your file explorer.

This repository is based on the excellent work from [code-nautilus](https://github.com/harry-cpp/code-nautilus) by harry-cpp, adapted to work with Windsurf instead of VSCode.

## 🎯 Features

- Right-click to open files in Windsurf
- Open entire folders in Windsurf
- Clean and modern integration with Nautilus
- Compatible with latest Windsurf versions

## 🛠️ Installation

```bash
wget -qO- https://raw.githubusercontent.com/RodrigoSaka/windsurf-nautilus/main/install.sh | bash
```

## 🗑️ Uninstallation

```bash
rm -f ~/.local/share/nautilus-python/extensions/windsurf-nautilus.py
nautilus -q
```

## 📦 Requirements

- Python Nautilus
- Windsurf Editor
- Nautilus file manager

## 📝 Usage

1. Right-click on any file to open it in Windsurf
2. Right-click on a folder to open it in Windsurf
3. Or right-click on empty space in a folder to open that folder in Windsurf

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## 👥 Author

Created and maintained by Rodrigo Sakaguchi