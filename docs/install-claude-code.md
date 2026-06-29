# Installing Claude Code

Claude Code is a command-line tool that runs on your computer. You do not need to write code to use it.

## Requirements

- A computer running macOS, Windows, or Linux
- A Claude account (free or paid) with Claude Code access
- An internet connection (Claude Code connects to Claude's servers, but your files stay local)

## Installation

### Mac

Open Terminal (search "Terminal" in Spotlight) and run:

```bash
npm install -g @anthropic-ai/claude-code
```

If you do not have npm, install Node.js first from [nodejs.org](https://nodejs.org).

### Windows

Open PowerShell and run:

```bash
npm install -g @anthropic-ai/claude-code
```

If you do not have npm, install Node.js first from [nodejs.org](https://nodejs.org).

### Linux

Open your terminal and run:

```bash
npm install -g @anthropic-ai/claude-code
```

## First-time setup

After installation, run:

```bash
claude
```

It will ask you to sign in with your Claude account. Follow the prompts.

## Opening this project

Download or clone this project, then:

```bash
cd self-advocacy-os
claude
```

Claude Code will automatically read the CLAUDE.md file and know how to help you.

## Troubleshooting

**"command not found: claude"**
Make sure Node.js is installed: `node --version`. If that works, try: `npx @anthropic-ai/claude-code`

**"npm not found"**
Install Node.js from [nodejs.org](https://nodejs.org). The installer includes npm.

**Sign-in issues**
Visit [claude.ai](https://claude.ai) in your browser first to confirm your account works, then try `claude` in the terminal again.

## Alternative: Claude Desktop

If you prefer a desktop app over the terminal, Claude Code is also available through the Claude desktop app. Download it from [claude.ai/download](https://claude.ai/download).
