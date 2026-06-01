# 📬 Automated Receipt Manager
Week 4 Class 1 — TechCrush AI Automation Specialist Bootcamp

## 📌 Project Overview
A fully automated receipt management system built with n8n that runs every 5 minutes, reads receipt emails from Gmail, extracts key financial data, and logs everything automatically to Google Sheets — replacing manual tracking completely.

## ⚙️ How It Works
- ✅ Step 1 — Schedule Trigger fires every 5 minutes automatically
- ✅ Step 2 — Gmail node searches inbox for emails containing "receipt"
- ✅ Step 3 — Code node extracts: date, subject, sender, amount, email ID
- ✅ Step 4 — Google Sheets logs every receipt as a new row automatically

## 🛠️ Tools Used
n8n, Gmail API, Google Sheets API, JavaScript, Schedule Trigger, OAuth2, Google Cloud Console

## 🧠 Concepts Learned
- Schedule Trigger (Cron) — time-based automation
- Inter-app connectivity — Gmail → n8n → Google Sheets
- Gmail API setup via Google Cloud Console
- OAuth2 authentication for Google services
- JavaScript regex for extracting amounts from email snippets
- Real business automation — replacing manual receipt tracking

## 💡 Real Business Value
- Automatically tracks all payment receipts without manual work
- Runs 24/7 every 5 minutes — never misses a receipt
- Applicable to SoftWear Abuja — track all customer payments automatically

## 👤 Author
Built by Rainat — TechCrush AI Automation Bootcamp, Week 4 Class 1 (2026)
