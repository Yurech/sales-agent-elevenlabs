# 🏃‍♂️ Runner — AI Sales Agent Integration (ElevenLabs + n8n + Google Sheets)

This project provides a practical demonstration of integrating a conversational **AI Sales Agent** powered by [ElevenLabs](https://elevenlabs.io/) into a landing page for the **"Runner"** sports club. Leads captured by the AI agent during customer interactions are automatically processed via **n8n** and saved directly into **Google Sheets**.

---

## 🌟 Features

- **🤖 AI Sales Agent (ElevenLabs):** An interactive conversational AI agent capable of answering questions regarding gym memberships, training programs, schedules, and collecting lead information.
- **⚡ Workflow Automation (n8n):** Receives webhooks triggered by ElevenLabs tools/actions and routes structured data seamlessly.
- **📊 Lead Management (Google Sheets):** Automatically stores captured lead details (Name, Phone Number, Selected Service/Membership, Date, Notes) into a centralized spreadsheet for sales follow-ups.
- **🎨 Demo Landing Page:** A responsive HTML/CSS/JS landing page for "Runner" Sports Club with the integrated ElevenLabs widget.

---

## 🏗 System Architecture

1. A visitor interacts with the **ElevenLabs AI Agent** on the Runner Sports Club landing page.
2. The agent collects lead details and executes a Server Tool pointing to an **n8n Webhook**.
3. **n8n** parses the incoming payload and appends a new row to the targeted **Google Sheet**.

---
