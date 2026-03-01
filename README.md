# Nikki-studio (joenikkai)
<div align="center">

  ![Static Badge](https://img.shields.io/badge/Nikki--studio-000000?style=for-the-badge&logo=starship&logoColor=white)
  ![Visitor Count](https://komarev.com/ghpvc/?joenikkai=joenikkai&color=blue&style=for-the-badge&label=PROFILE+VIEWS)

  <hr>
</div>

## 🚀 High-Performance Systems & TUI Engineering

I specialize in low-level systems programming, focusing on performance, memory efficiency, and robust user interfaces within the terminal.

### 🛠️ Featured Project: [pjdev](https://github.com/joenikkai/pjdev)
*A high-performance C++ IDE/Editor built from the ground up using Ncurses.*

This project showcases several advanced software engineering principles:

- **Complex State Machines:** Implemented a multi-mode architectural pattern (INSERT, REPLACE, EXECUTE) similar to Vim, managing independent logic loops and input handlers.
- **Custom Software Cursor & UI Rendering:** Engineered a software-driven cursor system using `A_REVERSE` and `A_UNDERLINE` with fallback crosshair logic for non-compatible terminals.
- **Intelligent Visual Wrapping:** Developed an algorithm to map logical file coordinates to visual terminal segments, allowing for fluent navigation through wrapped lines.
- **Lexing & Syntax Highlighting:** Built a custom keyword-based lexer for Rust, C++, Python, PHP, Bash, and ASM (GNU/Intel) without external libraries.
- **Robust Data Integrity:** Designed a journaling system with auto-save functionality and atomic-like file operations (`<N>.<file>.pjdev.part`) to prevent data loss.
- **Systems Integration:** Features deep shell integration allowing direct execution of bash commands from within the TUI environment.
- **Resource Management:** Optimized for memory and stability, including custom signal handling (`SIGINT`, `SIGTERM`) for graceful terminal restoration and automatic journal cleanup.

## 🧰 Tech Stack
- **Languages:** C++, C, Rust, Bash, Python
- **Specialties:** Systems Programming, Terminal UI (TUI) Development, Unix/Linux Tooling, Regex & Lexing
- **Tools:** Makefile, GCC/G++, Ncurses, Git

---
<div align="center">
  Exploring the intersection of terminal efficiency and modern IDE features.
</div>
