# SQR-AI — Smart Query Routing & Resolution System

AI-powered student support automation workflow built using n8n + GROQ LLM.

##  Project Overview

SQR-AI is an intelligent automation system that analyzes student queries, detects urgency, classifies departments using LLMs, routes tickets automatically, and sends resolution confirmation emails.

The workflow simulates a real-world AI-powered service desk automation platform similar to Zendesk or Freshdesk.

---

##  Features

* AI-based urgency detection
* LLM-powered department classification
* Smart query routing
* Automated Gmail notifications
* Resolution lifecycle management
* Automated query closure confirmation
* Multi-department support
* Real-time workflow automation

---

## 🧠 AI Components

### 1. Urgency Detection LLM

Detects whether a query is:

* Urgent
* Normal

### 2. Department Classification LLM

Classifies queries into:

* LMS Access
* Payment Issue
* Placement
* Certification
* Recording Access
* Technical Doubts

---

## ⚙️ Workflow Architecture

Google Form
→ Google Sheets Trigger
→ Urgency Detection LLM
→ Department Classification LLM
→ Switch Routing Logic
→ Department Gmail Nodes
→ Resolution Tracking
→ Resolution Confirmation Email

---

## 🛠️ Tech Stack

* n8n
* GROQ API
* LLM Workflow Automation
* Gmail API
* Google Sheets API
* AI Prompt Engineering

---

## 📩 Example Workflow

Student Query:
"I cannot access my LMS recordings."

Workflow Output:

* Priority detected: Urgent
* Department classified: LMS Access
* Email routed automatically
* Resolution confirmation generated

---


---

## 🚀 Future Improvements

* Ticket ID generation
* AI escalation engine
* Telegram/Slack notifications
* Power BI dashboard
* Query analytics
* Response SLA tracking

---

## 👨‍💻 Author

Mohammed Faizan Sayeed

AI/ML Engineer | GenAI & Automation Enthusiast
