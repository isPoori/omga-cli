# omga-cli

**omga-cli** is an advanced, AI-powered command-line assistant built for developers.  
It combines **local checks** (syntax, linting, project scaffolding) with the power of **OMGA**, giving you a smart, minimal, and developer-friendly workflow.

---

## ✨ Features

- ✅ Syntax & lint checks (`check file.py`)
- 🤖 AI explanations & Q&A (`explain`, `ask`)
- 🔧 Auto-fixes with diff previews (`fix --apply`)
- ⚡ Run shell commands safely (`run "ls -la"`)
- 🚀 Project scaffolding (e.g., FastAPI starter)
- 📚 Snippet management (`snippet add/list`)
- 💡 Interactive mode with **Tab-completion** (static + AI suggestions)

---

## 🚀 Quickstart

```bash
# 1. Install omga-cli
pip install omga-cli

# 2. Run in interactive mode
omga-cli

# Or run a one-shot command
omga-cli <command>
```

---

## 🖥️ Example Usage

```bash
# Check syntax
omga-cli check file.py
# → "Syntax OK" or error list

# Explain code
omga-cli explain file.py
# → "This code does X, but watch for Y pitfall."

# Ask general AI question
omga-cli ask "how to use pandas?"

# Fix code with AI suggestions
omga-cli fix file.py --apply

# Scaffold a FastAPI project
omga-cli generate project fastapi myapp

# Manage code snippets
omga-cli snippet add hello "print('Hello World')"
omga-cli snippet list
```

---

## 🔒 Security Note

The `run` command executes **local shell commands** directly.  
⚠️ Use it only with trusted commands. No sandboxing is provided.

---

## 👨‍💻 Author

Developed with ❤️ by **Pouria Hosseini**  
📧 Contact: [PouriaHosseini@Outlook.com](mailto:PouriaHosseini@Outlook.com)

---
