# DevBoxer

**Code while you sleep.** Delegate coding tasks to AI agents running in the cloud, and come back to pull requests ready to review.

[Get Started](https://www.devboxer.com) &nbsp;&middot;&nbsp; [Documentation](https://www.devboxer.com/docs) &nbsp;&middot;&nbsp; [Discord](https://discord.gg/e8ZSUWks5M)

---

## What is DevBoxer?

DevBoxer is a developer platform that runs AI coding agents in isolated cloud sandboxes. Describe a task, pick your repo, and an agent clones it, does the work, and opens a PR — all while you focus on something else.

- **Multiple agents** — Choose from Claude Code, OpenAI Codex, Gemini, Amp, and more
- **Parallel tasks** — Run several agents at once, each in its own isolated environment, so nothing conflicts
- **Works from anywhere** — Browser, CLI, phone, VS Code, desktop app, or Slack
- **Automate recurring work** — Schedule tasks or trigger them from GitHub events

## How it works

1. **Describe your task** — Select a GitHub repo and tell the agent what to do
2. **Agent works in the cloud** — Your repo is cloned into a sandbox and the agent starts coding
3. **Review & merge** — The agent opens a pull request for you to review

## Install the CLI

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

## Reporting Issues

Found a bug or have a feature request? Please [open an issue](https://github.com/devboxerhub/app/issues) — we read every one.

When filing a bug, including the following helps us fix it faster:

- What you expected to happen
- What actually happened
- Steps to reproduce
- Browser / OS / CLI version if relevant

## Community

Join our [Discord](https://discord.gg/e8ZSUWks5M) to ask questions, share feedback, and connect with other DevBoxer users.

## Links

- [Website](https://www.devboxer.com)
- [Documentation](https://www.devboxer.com/docs)
- [Discord](https://discord.gg/e8ZSUWks5M)
