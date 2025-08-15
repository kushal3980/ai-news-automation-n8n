# AI News Automation Workflow

Automated pipeline to fetch trending AI topics, generate human-readable content using Groq, and publish it to Gmail, Google Docs, and social media platforms.  
The workflow is built entirely in **n8n**, with dynamic topic configuration and fully automated scheduling.

---

## 📌 Features
- **Trending Topics Fetching** – Pulls top AI-related news from Serp API.
- **AI-Powered Content Generation** – Uses Groq model for summarization and post creation.
- **Multi-Channel Publishing** – Sends formatted content to:
  - Gmail (HTML formatted email)
  - Google Docs (auto-saved summaries)
- **Customizable Topics** – Easily change keywords without editing logic.
- **Scheduled Automation** – Runs daily using Cron in n8n.

---

## 🛠️ Technologies Used
- **n8n** – Workflow automation engine
- **Groq API** – Content generation
- **Serp API** – Trending topic discovery
- **Google APIs** – Gmail + Google Docs integration
- **JavaScript** (n8n Function Nodes) – Formatting & data transformation

---
