# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Environment

- **IDE:** JetBrains PyCharm Professional
- **Languages configured:** Python, JavaScript/TypeScript, Vue.js
- **Python interpreter:** `D:\file\Audio-Classification\audio` (virtual environment)
- **Package manager:** npm (Node.js projects)

## Repository

- **Remote:** https://github.com/xiao-chen-liang/test_claude
- **Branch:** master

## Project Structure

```
test_claude/
├── CLAUDE.md         # Project configuration
├── .gitignore        # Python, Node.js, JetBrains, OS, .env rules
├── .claudeignore     # Claude-specific ignore rules
└── game.html         # Tic Tac Toe web game (single HTML file)
```

## Files

### game.html
A browser-based Tic Tac Toe game. Open directly in any browser — no server needed.
- Dark theme UI
- Score tracking (X / O / Draw)
- Win highlight on winning cells
- Restart button

## Notes

No build, lint, or test commands defined yet. Update this file as the project grows.
