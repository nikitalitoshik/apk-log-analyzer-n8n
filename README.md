# APK Log Analyzer (n8n)

Automation workflow built with **n8n** for collecting, processing and analyzing APK / application logs.
The project focuses on parsing log data, enriching it with external APIs, and preparing structured output
for monitoring, debugging, or analytics purposes.

---

## 🚀 Features

- 📄 Ingest application (APK) logs
- 🔍 Parse and structure raw log data
- 🌍 Enrich logs using Google APIs
- 📊 Prepare logs for further analysis or monitoring
- 🔄 Fully automated workflow using n8n
- 🧩 Easily extendable with additional nodes and services

---

## 🛠 Tech Stack

- **n8n** — workflow automation
- **Google APIs** — data enrichment (via API calls)
- **JSON-based workflows**
- **REST APIs**

---

## 🧠 How It Works

1. Logs are received as input (file or request)
2. n8n workflow parses raw log content
3. Relevant fields are extracted and normalized
4. External APIs (e.g. Google services) are used to enrich data
5. Processed logs are returned or forwarded to the next system

---

## 📂 Project Structure

- `Apkop logi main.json` — main n8n workflow
- Workflow logic stored in JSON format
- API integrations handled via n8n HTTP Request nodes

---


