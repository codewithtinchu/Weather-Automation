# 🌦️ Weather Automation with n8n + Python

This project fetches live weather data every day at 6 AM, saves it into an SQLite database, and sends the report via email using n8n automation.

## 🚀 Features
- Fetches real-time weather using [wttr.in](https://wttr.in)
- Stores results in SQLite database
- Daily 6:00 AM email with weather updates
- Fully automated via n8n

## 📂 Project Structure
- `api_to_sql.py` → Python script to fetch and save weather data
- `workflow.json` → n8n workflow to automate scheduling + email
- `requirements.txt` → Python dependencies
- `README.md` → Project documentation

## 🛠️ Setup
1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/weather-automation.git
   cd weather-automation
