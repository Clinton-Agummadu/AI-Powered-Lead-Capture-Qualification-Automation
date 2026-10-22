#  AI-Powered Lead Capture & Qualification Automation

An end-to-end autonomous pipeline that captures incoming inbound leads, evaluates and qualifies them using an AI agent, logs structured data to a CRM, and triggers instant multi-channel notifications.

---

## 📽️ System Architecture

1. **Trigger:** Captures raw webhook payloads from landing page forms.
2. **Intelligent Brain (AI Agent):** Analyzes prospect details against pre-set qualification criteria using LLM prompts.
3. **Data Parsing Layer (Edit Fields):** Normalizes AI outputs into structured parameters.
4. **CRM Logging:** Automatically appends qualified records to Google Sheets.
5. **Multi-Channel Dispatch:** Dispatches customized emails to the business owner and lead, while firing a real-time alert to Telegram.

---

## 🛠️ Tech Stack & Tools

* **Automation Engine:** n8n
* **AI/LLM:** Groq / OpenAI API
* **Database/CRM:** Google Sheets API
* **Communication:** Gmail API, Telegram Bot API
* **Webhooks:** Custom HTTP JSON endpoints

---

## 📦 How to Import & Use

1. Download the `workflow.json` file from this repository.
2. Open your **n8n** instance.
3. Click **Workflows** -> **Import from File** and select the `.json` file.
4. Configure your API credentials for Gmail, Google Sheets, Telegram, and your LLM provider.
