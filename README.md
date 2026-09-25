🌍 [English](README.md) | [Türkçe](README.tr.md)

# 🤖 Codex CLI — Community Guide

> A practical, independent guide to OpenAI Codex CLI for terminal-based software development.

<div align="center">

![Guide License](https://img.shields.io/badge/guide%20license-MIT-green)
![Codex](https://img.shields.io/badge/Codex-CLI-black)
![Platform](https://img.shields.io/badge/platform-Terminal-blue)

**Use Codex from your terminal to understand, edit, run, and verify code in a local workspace.**

</div>

---

## What is Codex CLI?

**Codex CLI** is OpenAI's open-source coding agent that runs locally on your computer. It can inspect a project, edit files, run commands, and help verify changes while you remain in control of the workspace.

This repository is an **independent community guide**. It is not the official Codex repository and is not affiliated with or endorsed by OpenAI.

## Installation

### macOS / Linux

```bash
curl -fsSL https://chatgpt.com/codex/install.sh | sh
```

### Windows PowerShell

```powershell
powershell -ExecutionPolicy ByPass -c "irm https://chatgpt.com/codex/install.ps1 | iex"
```

### npm

```bash
npm install -g @openai/codex
```

### Homebrew

```bash
brew install --cask codex
```

Then launch Codex:

```bash
codex
```

## Getting Started

Open a terminal in your project directory and run:

```bash
codex
```

Describe the result you want. For example:

```text
Explain the authentication flow in this project.
Add tests for the parser and run them.
Refactor this module without changing its public API.
Review the latest git diff and point out possible regressions.
```

Codex can read project context, propose or apply edits, execute local commands, and report the result.

## Useful Workflows

### Understand an unfamiliar codebase

```text
Explain the architecture of this repository and identify the main entry points.
```

### Make a focused change

```text
Add validation to the signup form. Keep the existing UI and run the relevant tests.
```

### Review changes

```text
Review my current git diff for bugs, security issues, and missing tests.
```

### One-shot prompt

```bash
codex "Explain the latest git commit"
```

## Authentication

Run `codex` and follow the sign-in flow. Codex supports signing in with ChatGPT, and API-key usage is also available with additional setup.

## Safety Tips

- Review commands before allowing changes you do not understand.
- Keep secrets and production credentials out of repositories.
- Use version control so changes can be inspected and reverted.
- Run tests and linters after edits.
- For unfamiliar projects, start with read-only analysis before asking for broad changes.

## Official Resources

- Official repository: https://github.com/openai/codex
- Official Codex documentation: https://developers.openai.com/codex
- Codex web experience: https://chatgpt.com/codex

## License

The **content of this guide** is licensed under the [MIT License](LICENSE).

Codex CLI itself is maintained by OpenAI and is distributed under its own license. See the official Codex repository for the current project license and terms.

---

If this guide is useful, starring the repository helps other developers discover it.
