# Holmium File Explorer

![Holmium Logo](assets/holmium-logo.png)
![Screenshot 1: Settings](screenshots/holmium-settings.png)
![Screenshot 2: Search](screenshots/holmium-search.png)
![Screenshot 3: WinSxS](screenshots/holmium-winsxs.png)

**Holmium** is a fast, minimalist, and cross-platform propietary (commercial) file manager written in Python using PySide2 (Qt).

Inspired by the aesthetics of VSCode Dark+ and the functionality of Total Commander, Holmium is designed for those who lack the speed and convenience of standard Windows Explorer.

## ✨ Key Features

*   **Speed**: Instant opening of folders with tens of thousands of files (thanks to `QListView` and background threads).
*   **Tabs**: Support for multiple tabs with navigation history preserved in each.
*   **Built-in Search**: Recursive file search by mask (`r_*.ext` or `r_**.ext`) and simple format: `search .ext/search .ext --recursive` without using the heavy Windows indexer (as Explorer).
*   **Command Palette**: Invoke system windows and commands via the command line (`holmium://settings`).
*   **Archive Handling**: Built-in packing and unpacking of ZIP archives with a progress bar (without RAR).
*   **Text Editor**: Built-in editor with syntax highlighting (Python, JSON) other languages will be support later.
*   **Advanced Drag & Drop**: File dragging with a custom "ghost" and `Ctrl` support for copying.
*   **Dark Theme**: Unified interface in the VSCode style (light theme is comming soon).
*   **FTP Client**: Connection with smartphone.

## 🚀 Installation and Launch

1. Clone the repository:
   ```bash
   git clone https://github.com/TermoRadioactiveCat/Holmium-File-Explorer.git
   cd Holmium