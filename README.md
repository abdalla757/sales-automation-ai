# AI Sales Automation Workflow

An AI-powered sales automation workflow built with **n8n** that automatically researches companies and generates personalized cold email drafts.

---

## 🚀 Features

- Monitor a Google Drive folder for new Excel files.
- Extract lead data from uploaded spreadsheets.
- Filter valid leads (Email + Website).
- Research each company using AI.
- Generate personalized cold email drafts.
- Save the final results to Google Sheets.

---

## 🛠️ Tech Stack

- n8n
- OpenAI
- Google Drive API
- Google Sheets API
- JavaScript
- Prompt Engineering

---

## 📂 Workflow

```
Google Drive
  │
  ▼
Download Excel
  │
  ▼
Extract Leads
  │
  ▼
Filter Valid Leads
  │
  ▼
AI Company Research
  │
  ▼
Generate Personalized Cold Email
  │
  ▼
Save Results to Google Sheets
```

---

## 📸 Workflow Screenshot

![Workflow](images/workflow.png)

---

## 📁 Project Structure

```
sales-automation-ai
├── workflow
│   └── Sales Automation update.json
├── images
│   └── workflow.png
├── prompts
│   ├── research-agent.md
│   └── cold-email.md
├── README.md
└── .gitignore
```

---

## ⚙️ Installation

1. Import the workflow into n8n.
2. Configure your credentials.
3. Update Google Drive and Google Sheets IDs.
4. Add your OpenAI credentials.
5. Activate the workflow.

---

## 📌 Future Improvements

- CRM Integration
- Automatic Email Sending
- Better Lead Scoring
- HubSpot Integration
- Retry Logic

---

## 👤 Author

**Abdalla Elsayed** ([GitHub](https://github.com/abdalla757))
