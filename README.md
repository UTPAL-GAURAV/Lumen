# Lumen

Your personal AI tutor that illuminates gaps, sharpens interview skills, and tracks how far you've come.

Lumen is an AI-powered learning agent. It runs entirely in your terminal or IDE — no app to install, no UI to navigate. Just open it and start learning.

## What it does

- Teaches topics at your level using scenario-based questions, not lectures
- Tracks your progress, notes, and Q&A cards across sessions
- Flags weak areas and revisits them automatically
- Runs mock interviews and scores your readiness honestly

## Requirements

- A Lumen account — sign up at [lumen-prep.vercel.app](https://lumen-prep.vercel.app)
- One of the supported AI tools (see below)

## Supported AI tools

| Tool | Setup file | Notes |
|------|-----------|-------|
| [Claude Code](https://claude.ai/code) | `CLAUDE.md` | Best experience. CLI or VS Code extension. |
| [Cursor](https://cursor.sh) | `.cursor/rules/lumen.mdc` | Agentic mode required. |
| [Windsurf](https://codeium.com/windsurf) | `.windsurfrules` | Agentic mode required. |

The instruction file for your tool is already in the repo — it loads automatically when you open the folder.

## Setup

### 1. Clone the repo

```bash
git clone https://github.com/UTPAL-GAURAV/lumen.git
cd lumen
```

### 2. Set your `.env`

Open `.env` and set:

```
# Required — your Lumen session token
# Get it from https://lumen-prep.vercel.app → log in → Copy token (top-right header)
LEARNING_TOKEN=<your token here>

# Required only on a personal machine (not needed on enterprise/office setups)
# Claude Code → get from https://console.anthropic.com
ANTHROPIC_API_KEY=<your key here>
# Cursor / Windsurf → uses OPENAI_API_KEY or your provider key per their docs
```

> **Office / enterprise laptop?** Your Claude Code (or Cursor/Windsurf) subscription is already configured — you only need `LEARNING_TOKEN`.

> **Personal laptop?** You need both `LEARNING_TOKEN` and your AI provider's API key.

### 3. Open in your AI tool

**Claude Code**
```bash
claude   # in terminal, inside the repo folder
```
Or open the folder in VS Code with the Claude extension active.

**Cursor / Windsurf**

Open the repo folder. Switch to Agent mode. Then start a session.

### 4. Start learning

Just tell the AI what you want:

```
Let's work on system design
Test me on Java
Pick up where we left off
```

## Keeping up to date

```bash
git pull
```

Pulling latest always gives you the most current instructions.
