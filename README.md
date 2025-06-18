# whatsapp-pm-reminder
This project sends daily WhatsApp messages to help track Product Management and AI/ML learning progress using Twilio, Python, and Windows Task Scheduler.

## 📦 Files Included
- `final_merged_file.py`: Main Python script
- `.env`: Stores Twilio credentials (excluded from Git via .gitignore)
- `run_reminder.bat`: Double-click to send reminder manually

## 🔧 Setup Instructions
1. Install dependencies: `pip install twilio python-dotenv`
2. Create a `.env` file with your Twilio credentials:
   ```
   TWILIO_ACCOUNT_SID=your_sid_here
   TWILIO_AUTH_TOKEN=your_token_here
   ```
3. Use `run_reminder.bat` or Task Scheduler for automation.

## 🚀 Automation
Use Windows Task Scheduler to run this script daily and stay on track with your PM prep.

## ✨ Credits
Crafted by Soumyendu Dey for hIS 60-day Product Management journey.
""" > README.md

git add README.md
git commit -m "Add README.md"
git push
