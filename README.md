# 🚀 omga-cli

**omga-cli** is an AI-powered command-line assistant for developers.  
It connects to [Omga Ai](https://OmgaAi.ir) and provides intelligent code analysis, explanations, fixes, documentation, and project scaffolding — all inside your terminal.

---

<div align="center">
<a href="https://pepy.tech/projects/omga-cli"><img src="https://static.pepy.tech/personalized-badge/omga-cli?period=total&units=INTERNATIONAL_SYSTEM&left_color=BLACK&right_color=GREEN&left_text=downloads" alt="PyPI Downloads"></a>
</div>

---

## ✨ Features

| Feature | Description |
|---|---|
| 🔍 **Code Analysis** | Multi-language syntax checking and linting |
| 🤖 **AI Assistant** | Explanations, fixes, improvements, documentation |
| ⚡ **Streaming Responses** | Word-by-word AI output via SSE |
| 🎨 **Rich UI** | Syntax highlighting, diff views, styled panels |
| 🗂 **Project Scaffolding** | Generate FastAPI projects or AI-designed structures |
| 📦 **Snippets Manager** | Save, list, and remove reusable code snippets |
| 💾 **Response Cache** | SQLite-backed cache to avoid redundant API calls |
| 🔑 **Configurable** | Config file + env-variable API key override |

---

## 🚀 Quick Start

### Install from PyPI

```bash
pip install omga-cli
```

### Run

```bash
# Interactive shell
omga-cli

# One-shot commands
omga-cli check main.py
omga-cli explain main.py
omga-cli ask "What is the GIL in Python?"
omga-cli fix buggy.py
omga-cli improve legacy.py
omga-cli docs utils.py
omga-cli run "pytest -v"
omga-cli generate project fastapi myapp
```

---

## 📋 All Commands

```
check <file>                       Syntax & lint analysis
explain <file>                     AI code explanation
ask <question>                     Ask the AI anything
fix <file>                         AI-assisted bug fixing
improve <file>                     Refactoring suggestions
docs <file>                        Generate documentation
run <shell command>                Execute a shell command safely
generate project <template> <n>    Scaffold a new project
snippet add|list|remove [name]     Manage code snippets
help                               Show help
exit / quit                        Exit the shell
```

---

## 🌍 Supported Languages

omga-cli detects the language from the file extension and passes it to the AI and syntax highlighter:

Python · JavaScript · TypeScript · Java · C · C++ · C# · Go · Rust · Ruby · PHP · Swift · Kotlin · Bash · HTML · CSS · SQL · JSON · YAML · TOML · Markdown · Dart · Lua · R — and more.

---

## 👨‍💻 Author

**Pouria Hosseini** — [PouriaHosseini@Outlook.com](mailto:PouriaHosseini@Outlook.com)  
Website: [PouriaHosseini.ir](https://PouriaHosseini.ir)

---

**Happy coding! 🎉**
