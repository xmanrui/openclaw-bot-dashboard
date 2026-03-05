# OpenClaw Dashboard Skill

Launch and manage the OpenClaw Dashboard web UI.

## Quick Start

Just say:
- "打开机器人大盘"
- "打开 openclaw dashboard"
- "launch bot review"

The skill will automatically:
1. Detect your OS (macOS/Windows)
2. Check if git is available
3. Download the project (with or without git)
4. Install dependencies
5. Start the server
6. Give you the access URL

## What You Get

A web dashboard showing:
- All your bots/agents status
- Model configurations
- Session management
- Token usage statistics
- Skill inventory
- Alert center
- Pixel-art office animation

## Access

- Local: http://localhost:3000
- Network: http://YOUR_IP:3000

## Stop Server

Say "stop openclaw dashboard" or "关闭机器人大盘"

## Requirements

- Node.js 18+
- OpenClaw installed with config at `~/.openclaw/openclaw.json`

## Project Location

- macOS/Linux: `~/projects/OpenClaw-bot-review/`
- Windows: `%USERPROFILE%\projects\OpenClaw-bot-review\`
