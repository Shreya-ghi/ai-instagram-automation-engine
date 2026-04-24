 🤖 AI Instagram Automation Engine

[![n8n](https://img.shields.io/badge/Automation-n8n-FF6C37?style=flat&logo=n8n)](https://n8n.io/)
[![Groq](https://img.shields.io/badge/AI-Groq-orange?style=flat)](https://groq.com/)
[![Instagram](https://img.shields.io/badge/Platform-Instagram-E4405F?style=flat&logo=instagram)](https://www.instagram.com/)

An intelligent automation pipeline that generates AI-powered captions using **Groq (LLaMA 3)** and automatically publishes posts to **Instagram Business** via **n8n**.

---

🚀 Overview

This project automates the entire content creation workflow:
1. **Trigger:** Picks up a new image/topic from a **Google Sheet**.
2. **AI Processing:** Groq generates engaging, SEO-friendly captions and hashtags.
3. **Deployment:** n8n pushes the final content directly to your Instagram feed.

---

 🛠️ Tech Stack

* **Workflow Engine:** [n8n](https://n8n.io/)
* **AI Model:** Groq (LLaMA 3)
* **Database:** Google Sheets
* **Social API:** Instagram Graph API

---

 📁 Project Structure

* `workflow/` - Contains the `.json` export of the n8n workflow.
* `assets/` - Screenshots and architectural diagrams.
* `README.md` - Documentation.

---

 ⚙️ Setup Instructions

 1. Prerequisites
* An [n8n](https://n8n.io/) instance (Desktop or Cloud).
* A [Groq API Key](https://console.groq.com/).
* A Facebook Developer account with **Instagram Graph API** access.

 2. Configuration
Replace the following placeholders in the n8n workflow:
* `YOUR_GOOGLE_SHEET_ID`
* `YOUR_INSTAGRAM_BUSINESS_ACCOUNT_ID`
* `YOUR_GROQ_API_KEY`

---

## 🖼️ Workflow Preview
![Workflow Screenshot](assets/workflow.png)

---

> [!IMPORTANT]  
> Ensure your Google Sheet has headers for `Image URL`, `Topic`, and `Status` for the workflow to trigger correctly.
