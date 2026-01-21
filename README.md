# 🤖 AI Sales Agent (VIP Lead Scorer)

An automated CRM workflow built with **n8n**, **OpenAI (GPT-4o)**, and **WhatsApp Cloud API**. It processes leads from Google Sheets, identifies VIP clients, and drafts personalized emails instantly.

## 📺 Project Demo Video
Click the link below to watch the full automation and workflow in action:
▶️ **[Watch the Demo Video on Google Drive](https://drive.google.com/file/d/1qH8giB4HFBajuqjOa-6OywNumQ9sAwnX/view?usp=drivesdk)**

---

## ✨ Features
* **Data Ingestion:** Automatically fetches new leads from Google Sheets daily.
* **AI Analysis:** Uses GPT-4o to analyze job titles and score leads (1-10).
* **Smart Routing:**
    * **VIP Leads (Score 8+):** Sends an instant WhatsApp alert to the admin & updates the CRM.
    * **Normal Leads:** Updates the CRM silently without disturbing the admin.
* **Auto-Drafting:** Writes a personalized, context-aware cold email for each lead.

## 🛠️ Tech Stack
* **Workflow Automation:** n8n (Self-Hosted)
* **AI Model:** OpenAI GPT-4o Mini
* **Database:** Google Sheets
* **Notifications:** WhatsApp Cloud API

## 🚀 How to Use
1. Import the `workflow.json` file into your n8n instance.
2. Set up your Google Sheets and OpenAI credentials.
3. Configure the "Schedule Trigger" to your preferred time.
4. Activate the workflow!

---
*Created by **Abdullah Zahid** - AI Automation Expert*
