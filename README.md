# 🤖 AI-Powered Morning Briefing Bot (n8n + Llama AI + Notion + Telegram)

An automated personal assistant pipeline built to synthesize daily Google Calendar events and Notion academic modules into personalized, aesthetic Telegram briefings every morning at 6:00 AM WITA.

## 🚀 Key Features
- **Automated Workflow:** Triggered automatically every day using n8n's Schedule Trigger.
- **Smart Data Sourcing:** Multi-source integration fetching raw data from Google Calendar and Notion databases simultaneously.
- **AI Synthesis:** Leverages Llama AI to process, structure, and transform dense scheduling data into an engaging, clean morning notification.
- **Robust Messaging:** Dispatches beautifully formatted daily micro-briefings directly to a personal Telegram chat via HTML parsing.

## 🛠️ Tech Stack
- **Automation Core:** n8n
- **LLM Engine:** Llama AI
- **APIs Connected:** Notion API, Google Calendar API, Telegram Bot API

## 📋 How to Use This Workflow
1. Download the `Intelligent-Daily-Briefing-Agent.json` file from this repository.
2. Open your n8n canvas and select **Import from File** to load the diagram.
3. Configure your credentials for Google Calendar, Notion, your AI model provider, and Telegram.
4. Activate the workflow and enjoy your automated smart assistant!
