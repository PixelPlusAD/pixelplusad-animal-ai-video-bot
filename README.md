# pixelplusad-animal-ai-video-bot
n8n workflow for generating animal-themed AI short videos and uploading to YouTube automatically.
# pixelplusad-animal-ai-video-bot

This repository contains the workflow and automation scripts for generating short videos about animals using AI tools and uploading them to YouTube on a daily schedule at 8 PM.

## Features

- Auto-generate animal-themed content using AI (ChatGPT, DALL·E, etc.)
- Automatically create short videos with text-to-speech and images
- Upload to YouTube automatically
- Scheduled to run daily at 20:00
- Fully integrated with n8n workflow automation

## Components

- **n8n**: no-code workflow orchestrator
- **AI Content Generator**: (e.g. ChatGPT / free LLMs)
- **Image Generator**: DALL·E or Stable Diffusion
- **TTS**: TTS services like Piper or Coqui (self-hosted)
- **YouTube Uploader**: via n8n YouTube node
- **Scheduler**: built-in n8n cron

## How to use

1. Clone this repository:
   ```bash
   git clone https://github.com/PixelPlusAD/pixelplusad-animal-ai-video-bot.git
npm install -g n8n
n8n start

---

## ✅ .gitignore (suitable for n8n + Node)

```gitignore
# dependencies
node_modules
.env

# macOS
.DS_Store

# logs
logs
*.log

# n8n files
.n8n

# OS
Thumbs.db
ehthumbs.db

# dotenv
.env.local
.env.development.local
.env.test.local
.env.production.local

# Replit
.replit
