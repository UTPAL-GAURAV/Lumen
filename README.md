# Lumen

  Your personal AI tutor that illuminates gaps, sharpens interview skills, and tracks how far you've come.

  Lumen is a Claude-powered learning agent. It runs entirely in your terminal or VS Code — no app to install, no UI to navigate. Just open it and start
  learning.

  ## What it does

  - Teaches topics at your level using scenario-based questions, not lectures
  - Tracks your progress, notes, and Q&A cards across sessions
  - Flags weak areas and revisits them automatically
  - Runs mock interviews and scores your readiness honestly

  ## Requirements
  
  - [Claude Code](https://claude.ai/code) (CLI or VS Code extension)
  - A Lumen account — sign up at [learning-ui-peach.vercel.app](https://learning-ui-peach.vercel.app)

  ## Setup

  1. Clone this repo
     ```bash
     git clone https://github.com/UTPAL-GAURAV/lumen.git
     cd lumen
     ```

  2. Add your token to .env
    - Open the dashboard, log in with Google, and click Copy token in the top-right
    - Paste it into .env:
  LEARNING_TOKEN=<your token here>
  3. Open in Claude
  claude   # in terminal
  3. Or open the folder in VS Code with the Claude extension active.
  4. Start a session — just tell Claude what you want to learn:
  "Let's work on system design",
  "Test me on Java",
  "Pick up where we left off"

  Keeping up to date

  git pull

  That's it. Pulling latest always gives you the most current instructions.