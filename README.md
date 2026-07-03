# 🤖 Codex CLI — General User Guide

> **The terminal-based AI coding agent developed by OpenAI that runs in your local shell.**

<div align="center">

![Version](https://img.shields.io/badge/version-latest-blue)
![License](https://img.shields.io/badge/license-Proprietary-red)
![Platform](https://img.shields.io/badge/platform-OpenAI%20Codex-darkgreen)

**⭐ Write, edit, and verify code directly from your terminal workspace.**

</div>

---

## 📚 Table of Contents

- [What is Codex CLI?](#what-is-codex-cli)
- [Installation](#installation)
- [Getting Started](#getting-started)
- [Interactive Mode (TUI)](#interactive-mode-tui)
- [Configuration](#configuration)
- [Slash Commands](#slash-commands)
- [Essential Keyboard Shortcuts](#essential-keyboard-shortcuts)
- [Tips & Tricks](#tips--tricks)
- [Resources](#resources)
- [Quick Reference Card](#quick-reference-card)

---

## What is Codex CLI?

**Codex CLI** is an open-source, terminal-based AI coding agent developed by OpenAI. It is designed to assist developers by reading, editing, and running code directly from the command line.

Unlike a simple chat assistant, Codex CLI operates as an autonomous agent that can propose modifications, run shell scripts, and verify results locally inside your project workspace.

---

## Installation

Install the Codex CLI globally depending on your operating system or environment:

### 🪟 Windows (WinGet)
```powershell
winget install OpenAI.Codex
```

### Global Installation (npm)
```bash
npm install -g @openai/codex
```

### 🍎 macOS / 🐧 Linux (Install Script)
```bash
curl -fsSL https://chatgpt.com/codex/install.sh | sh
```

### 🪟 Windows (PowerShell)
```powershell
powershell -ExecutionPolicy ByPass -c "irm https://chatgpt.com/codex/install.ps1 | iex"
```

---

## Getting Started

### 1. Launch the CLI

To start an interactive terminal session, navigate to your project directory and run:

```bash
codex
```

### 2. Enter Your Prompts

Describe what coding task you want Codex to complete:

```
> Create a Python function to compute Fibonacci numbers
> Refactor server.js to use Express routing middleware
> Verify tests and write a summary of failures
```

### 3. Exit the Session

To exit the interactive session:
* Type `/quit` or `/exit` in the prompt box.
* Or press **Ctrl+D** in the terminal.

---

## Interactive Mode (TUI)

### prompt box features

- **Reference Files:** Type `@` followed by a file name to search and inject the file contents into the agent's context.
- **Run Terminal Commands:** Start a prompt with `!your-command` to run a shell command directly and send its output to the agent.
- **Multi-line Input:** Press `Shift+Enter` to add a new line inside the prompt box.

---

## Configuration

Codex CLI allows you to configure models and permissions to tailor agent behavior.

- **Configure Settings:** Type `/config` inside the TUI to open the settings interface.
- **Change Settings Directly:** Run `/config key=value` (e.g. `/config theme=dark`) to modify settings instantly.

---

## Slash Commands

Type `/` in the prompt box to open the command menu, or `/help` to see the full list of options.

| Command | Description |
|---------|-------------|
| `/new` | Clear the prompt area and start a new session |
| `/clear` | Wipe current conversation history and start fresh |
| `/model <name>`| Switch active model mid-session |
| `/permissions` | Configure what the agent can do without manual approval |
| `/approve` | Manage approval requirements for agent actions |
| `/status` | View the current state of the agent or session |
| `/ide` | Pull context from your active IDE into the session |
| `/agent` | Switch or inspect active agent threads |
| `/vim` | Toggle Vim mode for the composer |
| `/quit` | Exit Codex CLI |

---

## Essential Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| **Ctrl + C** | Interrupt current operation / clear input |
| **Ctrl + D** | Exit the active session |
| **Ctrl + L** | Redraw the terminal screen |
| **Ctrl + O** | Toggle the transcript viewer (shows tool usage details) |

---

## Tips & Tricks

- **One-Shot Mode:** Run a prompt directly from your terminal shell and exit immediately after execution:
  ```bash
  codex "Explain the latest git commit changes"
  ```
- **Vim Mode:** If you prefer keyboard-centric modal editing, toggle the editor interface using the `/vim` slash command.
- **IDE Context Fetching:** Pull open files or current selections directly from your IDE workspace using the `/ide` command.

---

## Resources

- **GitHub Repository:** [github.com/openai/codex](https://github.com/openai/codex)
- **Official Documentation:** [openai.com](https://openai.com)

---

## Quick Reference Card

```
┌──────────────────────────────────────────────────────────┐
│                 🤖 Codex Quick Reference                  │
├──────────────────────────────────────────────────────────┤
│                                                          │
│  START                     MANAGE                        │
│  codex           .......  Launch TUI      /new           │
│  codex "prompt"  .......  With prompt     /clear         │
│                                           /quit          │
│                                                          │
│  EDITOR                    KEYBINDINGS                   │
│  @file           .......  Reference file  Ctrl+C         │
│  !command        .......  Run shell       Ctrl+D         │
│  Shift+Enter     .......  New line        Ctrl+O         │
│                                           Ctrl+L         │
│                                                          │
│  CONFIG                    CONTEXT                       │
│  /config         .......  Settings Panel  /ide           │
│  /model          .......  Change model    /status        │
│  /permissions    .......  Security setup  /agent         │
│  /approve        .......  Auto actions    /vim           │
│                                                          │
└──────────────────────────────────────────────────────────┘
```

---

> **Codex CLI** — Proprietary — Developed with ❤️ by OpenAI
