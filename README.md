# 🚀 Recruitment Automation System (n8n)

An automated recruitment workflow built using **n8n** to streamline candidate outreach, tracking, and internal notifications.

---

## 🧩 Workflow Architecture

![Workflow Architecture](./workflow-architecture.png)

---

## 📌 Overview

This system automates the entire recruitment outreach process — from candidate data ingestion to communication and status tracking.

---

## ⚙️ Key Features

✅ Automated candidate outreach via Gmail  
✅ Sequential processing to avoid rate limits  
✅ Recruitment status sync with Google Sheets  
✅ Rate limit protection layer  
✅ Internal team notifications (Discord)  
✅ Structured reporting system  

---

## 🧠 How It Works

1. New candidate data is added to Google Sheets  
2. Workflow processes candidates sequentially  
3. Outreach emails are sent automatically  
4. Status is updated in Google Sheets  
5. Rate limiting ensures safe execution  
6. Internal team is notified via Discord  

---

## 🛠 Requirements

- n8n
- Google Sheets API
- Gmail API
- Discord Webhook / Bot

---

## 🚀 Setup

1. Import the `.json` file into n8n  
2. Configure credentials  
3. Update sheet IDs and email settings  
4. Activate workflow  

---

## 👨‍💻 Author

Shahrear Bin Satter  
AI Automation Engineer | n8n Specialist
