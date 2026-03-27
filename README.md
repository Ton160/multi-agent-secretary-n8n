# 🤖 AI Secretary (n8n Workflow)

🚀 AI-powered personal assistant built with n8n and multi-agent architecture.

## ✨ Features

* Accepts **Text, Voice, and Image**
* Transcribes and analyzes inputs
* Routes requests using an AI Orchestrator
* Handles:

  * 📧 Emails
  * 📅 Calendar
  * 🌐 Web Search

## 🧠 How It Works

1. User sends a message via Telegram
2. Input is normalized into text
3. AI Orchestrator decides the intent
4. Task is routed to the correct agent
5. Response is returned as text or audio

## 🖼️ Workflow

![Workflow](assets/workflow.png)

## ⚙️ Tech Stack

* n8n
* OpenAI
* Telegram Bot
* Gmail API
* Google Calendar API
* MCP (Model Context Protocol)

## 🚀 Setup

1. Import `workflow.json` into n8n
2. Add your credentials:

   * OpenAI
   * Telegram
   * Gmail
   * Google Calendar
3. Activate the workflow

## 📌 Notes

* Built with modular agent architecture
* Easy to extend with more tools

---

Made with n8n ⚡
