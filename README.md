# Lumen

Your personal AI tutor that illuminates gaps, sharpens interview skills, and tracks how far you've come.

## What it does

- Teaches topics at your level using scenario-based questions, not lectures
- Tracks your progress, notes, and Q&A cards across sessions
- Flags weak areas and revisits them automatically
- Runs mock interviews and scores your readiness honestly

---

## Before you start

You need two things:

1. **A Lumen account** — sign up at [Lumen-Prep](https://lumen-prep.vercel.app)
2. **An AI tool** — Claude Code, Cursor, or Windsurf (pick one)

---

## Setup

### Step 1 — Clone the repo

```bash
git clone https://github.com/UTPAL-GAURAV/lumen.git
cd lumen
```

### Step 2 — Add your tokens to `.env`

Open the `.env` file and fill in the values:

```
LEARNING_TOKEN=       ← paste from Lumen-Prep (log in → Copy token from header)
ANTHROPIC_API_KEY=    ← only if using Claude Code on a personal machine
```

> On an office/enterprise laptop with Claude Code already set up? You only need `LEARNING_TOKEN`.

### Step 3 — Open this Repo in VS Code

**Claude** — Start learning using Claude Code IDE extension or from terminal.

**Cursor or Windsurf** — open the folder, switch to Agent mode, and start chatting.

### Step 4 — Start learning

Just say what you want:

```
Let's work on system design
Test me on Java
Pick up where we left off in Angular
```

---

## View your progress

Visit [Lumen-Prep](https://lumen-prep.vercel.app) to see your dashboard — scores, notes, Q&A cards, and weak areas for every topic you've studied.

---

## Keeping up to date

```bash
git pull
```
