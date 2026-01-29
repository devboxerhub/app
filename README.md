<p align="center">
  <a href="https://www.devboxer.com">
    <img src="https://cdn.devboxer.com/devboxer-logo-light.90e6b59e.png" alt="DevBoxer" width="48" />
  </a>
</p>

<h1 align="center">DevBoxer</h1>

<p align="center">
  <strong>Code while you sleep.</strong><br/>
  Delegate coding tasks to AI agents running in the cloud, and come back to pull requests ready to review.
</p>

<p align="center">
  <a href="https://www.npmjs.com/package/@devboxer/cli"><img src="https://img.shields.io/npm/v/@devboxer/cli?style=flat-square&label=CLI&color=CB3837" alt="npm" /></a>
  <a href="https://discord.gg/e8ZSUWks5M"><img src="https://img.shields.io/discord/1464413802157183219?style=flat-square&logo=discord&logoColor=white&label=Discord&color=5865F2" alt="Discord" /></a>
  <a href="https://www.devboxer.com"><img src="https://img.shields.io/badge/Website-devboxer.com-blue?style=flat-square" alt="Website" /></a>
  <a href="https://www.devboxer.com/docs"><img src="https://img.shields.io/badge/Docs-devboxer.com%2Fdocs-green?style=flat-square" alt="Docs" /></a>
</p>

---

## 🤖 What is DevBoxer?

DevBoxer is a developer platform that runs AI coding agents in isolated cloud sandboxes. Describe a task, pick your repo, and an agent clones it, does the work, and opens a PR — all while you focus on something else.

- 🧠 **Multiple agents** — Choose from Claude Code, OpenAI Codex, Gemini, Amp, and more
- ⚡ **Parallel tasks** — Run several agents at once, each in its own isolated environment, so nothing conflicts
- 🌍 **Works from anywhere** — Browser, CLI, phone, VS Code, desktop app, or Slack
- 🔁 **Automate recurring work** — Schedule tasks or trigger them from GitHub events

## 🚀 How it works

1. **Describe your task** — Select a GitHub repo and tell the agent what to do
2. **Agent works in the cloud** — Your repo is cloned into a sandbox and the agent starts coding
3. **Review & merge** — The agent opens a pull request for you to review

## 📦 Install the CLI

The DevBoxer CLI lets you create tasks, pull changes, and manage your workflow from the terminal.

```bash
npm install -g @devboxer/cli
devboxer auth
```

**Requirements:** Node.js 18+, macOS / Linux / WSL

### Quick examples

```bash
# Create a task
devboxer create "Fix the login bug"

# Create a task with a specific model
devboxer create "Refactor auth module" --model opus

# Pull a task's branch to your local machine
devboxer pull

# Use as an MCP server with Claude Code
claude mcp add devboxer -- devboxer mcp
```

See the full [CLI documentation](https://www.devboxer.com/docs/integrations/cli) for all commands and options.

## 🐛 Reporting Issues

Found a bug or have a feature request? Please [open an issue](https://github.com/devboxerhub/app/issues) — we read every one.

When filing a bug, including the following helps us fix it faster:

- What you expected to happen
- What actually happened
- Steps to reproduce
- Browser / OS / CLI version if relevant

## 💬 Community

[![Discord](https://img.shields.io/badge/Join_us_on_Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/e8ZSUWks5M)

Ask questions, share feedback, and connect with other DevBoxer users.

## 🔗 Links

- 🌐 [Website](https://www.devboxer.com)
- 📖 [Documentation](https://www.devboxer.com/docs)
- 💬 [Discord](https://discord.gg/e8ZSUWks5M)
