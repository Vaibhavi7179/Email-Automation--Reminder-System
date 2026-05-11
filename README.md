# 📧 Email Automation & Reminder System

## 📌 Project Overview
The **Email Automation & Reminder System** is a Python-based automation project that schedules and sends personalized reminder emails automatically using CSV data and email templates.

This project helps automate repetitive communication tasks such as:
- Meeting reminders
- Assignment notifications
- Webinar alerts
- Task reminders
- Payment follow-ups

The system reads contact and reminder details from CSV files, personalizes email templates, schedules emails, sends them using SMTP, and generates logs/reports for tracking successful and failed emails.

---

# 🚀 Features

✅ Automated email scheduling  
✅ Personalized email templates  
✅ CSV-based contact management  
✅ Reminder scheduling system  
✅ SMTP email integration  
✅ Logging for sent/failed emails  
✅ CSV report generation  
✅ Dry-run testing mode  
✅ Beginner-friendly project structure  

---

# 🛠️ Tech Stack

- Python
- Pandas
- smtplib
- email.message
- schedule
- datetime
- logging
- python-dotenv
- CSV files

---

# 📂 Project Structure

```bash
Email-Automation-Reminder-System/
│
├── data/
│   ├── contacts.csv
│   ├── reminders.csv
│
├── templates/
│   ├── email_template.txt
│
├── outputs/
│   └── report.csv
│
├── logs/
│   └── email.log
│
├── main.py
├── requirements.txt
├── .env.example
├── .gitignore
└── README.md
