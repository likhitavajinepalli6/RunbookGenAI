# 🚀 RunbookGen AI

An AI-powered IT troubleshooting assistant that automatically generates structured runbooks from user-reported technical issues using semantic document retrieval and rule-based/AI-assisted generation.

## 📌 Overview

RunbookGen AI helps IT administrators, DevOps engineers, and support teams troubleshoot system issues quickly by generating professional troubleshooting runbooks.

Instead of manually searching documentation, users simply describe an issue (for example, *"Apache server not starting"*), and the system retrieves relevant technical information and generates a structured troubleshooting guide.

---

## ✨ Features

- 🔐 User Authentication
- 📝 AI-assisted Runbook Generation
- 🔍 Semantic Document Retrieval using FAISS
- 📚 Sentence Transformer Embeddings
- 📖 Runbook History Management
- 📤 Export Runbooks as Text Files
- 📋 Copy Runbook to Clipboard
- 💾 SQLite Database Integration
- ⚡ Rule-based Fallback Generation
- 🌐 Clean Flask Web Interface

---

## 🛠 Tech Stack

### Frontend
- HTML
- CSS
- JavaScript

### Backend
- Python
- Flask

### AI & Retrieval
- FAISS
- Sentence Transformers
- Ollama (Optional Local LLM)

### Database
- SQLite
- SQLAlchemy

---

## 📂 Project Structure

```
RunbookGenAI/
│── app.py
│── generator.py
│── retriever.py
│── models.py
│── llm_client.py
│── prompt_template.py
│── requirements.txt
│── templates/
│── data/
│── instance/
└── README.md
```

---


## 📖 Workflow

1. User logs into the system.
2. User enters an IT issue.
3. Flask backend processes the request.
4. FAISS retrieves relevant documentation.
5. The generator analyzes the issue.
6. A structured troubleshooting runbook is created.
7. Runbook is displayed to the user.
8. Generated runbook is saved to history.
9. Users can copy or export the runbook.

---

## 📋 Generated Runbook Includes

- Issue Title
- Problem Summary
- Environment / Assumptions
- Possible Causes
- Step-by-Step Troubleshooting
- Commands
- Risk Warnings
- Rollback Plan
- Validation Steps
- Escalation Notes

---

## 🎯 Use Cases

- IT Support Teams
- Linux System Administration
- DevOps Engineers
- Cloud Infrastructure Troubleshooting
- Learning Tool for Beginners
- Documentation Automation

---
