# 🚀 omga-cli

**omga-cli** is an AI-powered command-line assistant for developers. It provides intelligent code analysis, explanations, fixes, and more with a beautiful interface.

---
<div align="center">
<a href="https://pepy.tech/projects/omga-cli"><img src="https://static.pepy.tech/personalized-badge/omga-cli?period=total&units=INTERNATIONAL_SYSTEM&left_color=BLACK&right_color=GREEN&left_text=downloads" alt="PyPI Downloads"></a>
</div>
---

## ✨ Features

- 🔍 **Code Analysis** - Syntax checking, linting, error detection
- 🤖 **AI Assistant** - Code explanations, fixes, improvements, documentation
- 🎨 **Beautiful UI** - Rich, colorful terminal interface
- ⚡ **Fast & Smart** - Cached responses, progress indicators, tab completion
- 🚀 **Project Tools** - Scaffolding, snippets, shell commands

---

## 🚀 Quick Start

### Installation
```bash
pip install omga-cli
```

### Usage
```bash
# Interactive mode
omga-cli

# Direct commands
omga-cli check file.py
omga-cli explain file.py
omga-cli ask "How to optimize Python code?"
```

---

## 📋 Commands

| Command | Description |
|---------|-------------|
| `check <file>` | Check syntax and linting |
| `explain <file>` | Get AI code explanation |
| `ask <question>` | Ask AI questions |
| `fix <file>` | Fix code issues |
| `improve <file>` | Get improvement suggestions |
| `docs <file>` | Generate documentation |
| `run <command>` | Run shell commands |
| `generate project <template> <name>` | Create new project |
| `snippet add/list/remove` | Manage code snippets |
| `config` | Show configuration |
| `status` | Show system status |
| `help` | Show help |

---

## 🎯 Examples

```bash
# Check your code
omga-cli check main.py

# Get detailed explanation
omga-cli explain main.py

# Ask for help
omga-cli ask "What's the best way to handle errors in Python?"

# Fix issues automatically
omga-cli fix main.py

# Generate FastAPI project
omga-cli generate project fastapi myapp

# Interactive mode
omga-cli
> check file.py
> explain file.py
> ask "How can I improve this?"
> exit
```

---

## ⚙️ Configuration

Configuration is stored in `~/.omga_cli/config.json`. You can customize:

- **UI Settings**: Themes, colors, progress indicators
- **AI Settings**: Model, temperature, response length
- **Features**: Auto-fix, caching, smart completion
- **Security**: Confirmation prompts, safe mode

---

## 🛡️ Security

- ✅ **Built-in API Key** - No setup required
- 🔒 **Safe Execution** - Confirmation for destructive operations
- ⏱️ **Timeouts** - Prevents hanging commands
- 🚫 **No Data Collection** - All processing via your API

---

## 🐛 Troubleshooting

**Permission Errors**
```bash
chmod 755 ~/.omga_cli
```

**Import Errors**
```bash
pip install --upgrade omga-cli
```

**Debug Mode**
```bash
export OMGA_DEBUG=1
omga-cli check file.py
```

---

## 👨‍💻 Author

**Pouria Hosseini**  
📧 [PouriaHosseini@Outlook.com](mailto:PouriaHosseini@Outlook.com)

---

**Happy coding! 🎉**
