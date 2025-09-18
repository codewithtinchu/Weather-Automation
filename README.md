🌦️ Weather Automation with n8n + Python

Automated workflow that fetches live weather data daily at 6:00 AM, stores it in an SQLite database, and sends a weather report via email — powered by **Python** and **n8n**.

---

## 📖 Table of Contents
1. [Features](#-features)  
2. [Tech Stack](#-tech-stack)  
3. [Project Structure](#-project-structure)  
4. [Setup & Installation](#-setup--installation)  
5. [Future Improvements](#-future-improvements)  


---

## 🚀 Features
- 🌍 Fetches **real-time weather data** from [wttr.in](https://wttr.in)  
- 💾 Stores weather results in **SQLite database**  
- 📧 Sends **daily 6:00 AM weather update emails**  
- ⚡ Fully automated with **n8n (cron jobs + email integration)**  

---

## 🛠️ Tech Stack
- **Python** → `requests`, `sqlite3`  
- **n8n** → Workflow automation (cron + email)  
- **wttr.in API** → Free weather data source  

---

## 📂 Project Structure
weather-automation/
│
├── api_to_sql.py # Python script to fetch & save weather data
├── weather_email_workflow.json # n8n workflow for scheduling & email
├── requirements.txt # Python dependencies
└── README.md # Project documentation




---

## ⚙️ Setup & Installation

1. **Clone this repo**
   ```bash
   git clone https://github.com/codewithtinchu/weather-automation.git
   cd weather-automation
Install dependencies


pip install -r requirements.txt
Run script manually (for testing)


python api_to_sql.py
Import workflow into n8n

Open your n8n dashboard

Import weather_email_workflow.json

Set up your SMTP credentials (for email sending)

Schedule to run daily at 6:00 AM

✨ Future Improvements
🌆 Support for multiple cities

📱 SMS/WhatsApp alerts instead of just email

🐳 Deploy on Docker for 24/7 automation

☁️ Integration with cloud DBs (PostgreSQL, MySQL)



