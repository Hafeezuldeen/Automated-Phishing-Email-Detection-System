# Automated-Phishing-Email-Detection-System
A lightweight, scalable, and real-time email security automation built with UiPath, Google Sheets, and IMAP.
Designed to help SMEs detect phishing emails at near-zero cost.
Created by Hafeezul Deen S — © 2025 All Rights Reserved.

<img width="908" height="775" alt="Screenshot 2025-11-22 140109" src="https://github.com/user-attachments/assets/2e65a288-8d72-4a8b-99ea-9361865b0792" />


## 🔥 Project Overview
This project is a fully automated phishing email detection system, developed using UiPath, Google Sheets, and Gmail IMAP.
It scans incoming emails in real time, detects suspicious patterns using keyword-based rules, saves the results to Google Sheets, and displays instant alert popups.

This prototype demonstrates how low-cost automation can replace expensive SOC systems for small and medium enterprises.


## 🎯 Key Features
🔍 Automated IMAP Email Scanning (Inbox + Spam)

⚠️ Real-Time Phishing Alerts (Popup notifications)

📄 Attachment Capture (Save suspicious attachments locally)

🗂️ Google Sheets Logging (Subject, From, Date, Status, Risk Score)

🎯 Keyword-Based Phishing Detection

🚀 24/7 Background Email Security Automation

💰 Zero-Cost Prototype (UiPath Community + Free Google APIs)


## 📸 Demo Screenshot

### Compose Threat email to the Testing Account
<img width="1811" height="859" alt="Screenshot 2025-11-22 225910" src="https://github.com/user-attachments/assets/6da2dfa3-fbe1-43c9-9e37-0edde334e841" />

### Overview Of uipath connection work
<img width="1920" height="1080" alt="Screenshot 2025-11-22 231842" src="https://github.com/user-attachments/assets/385bb11c-0de9-43fa-9a4f-4a0580dd6b60" />

### Alert❗❗❗❗ 
<img width="422" height="207" alt="Screenshot 2025-11-22 140337" src="https://github.com/user-attachments/assets/055ceac9-a977-4cf9-ae48-7fa4063a4088" />

### Automatically Saving in Google Sheets - "Logs"
<img width="592" height="292" alt="Screenshot 2025-11-22 140447" src="https://github.com/user-attachments/assets/2be6fec9-9ba7-4a5d-8de8-84977d899854" />


## 🧠 Future AI Upgrade Plan
This project includes a roadmap to transform the rule-based prototype into a fully AI-powered email threat detection system using free tools and APIs:

🔹 AI Content Analysis
Using OpenAI free tier or HuggingFace models
Detect tone, impersonation, grammar anomalies

🔹 Sender Reputation Check
AbuseIPDB API
IPQualityScore (IPQS) API

🔹 Link & Attachment Scanning
VirusTotal Public API

🔹 ML-Based Risk Scoring
Google Colab
Python + scikit-learn

🔹 Auto-Quarantine + Alerts
Gmail API automation
Slack or Telegram bot alerts


## 🏗️ System Architecture
<img width="970" height="747" alt="Screenshot 2025-11-22 151055" src="https://github.com/user-attachments/assets/36357daa-fd1e-4541-a3f9-5a44f8869420" />


## 🔧 Tech Stack

UiPath Community Edition

Gmail IMAP

Google Workspace Sheet API

VB.NET Expressions (UiPath)

Message Box Alert System

Google App Password Authentication


## 🚀 How It Works
1. Email Fetching
UiPath fetches emails from Gmail using IMAP (Inbox + Spam).

2. Keyword-Based Detection
Checks Subject + Body for over 40 common phishing phrases.

3. Alert Generation
Shows real-time popup with:
Sender
Subject
Message Body
Risk Level

4. Logging
Appends results to Google Sheets:
Subject
From
Date
Status
Risk Score

5. Attachment Storage
Saves suspicious attachments for further analysis.


## 📥 Setup Instructions

1. Enable IMAP in Gmail
→ Settings → See All Settings → Forwarding & POP/IMAP → Enable IMAP

2. Create Google App Password
→ Google Account → Security → App Password → Create

3. Configure UiPath
Add Get IMAP Mail Messages
Server: imap.gmail.com
Port: 993
Email: your Gmail
Password: App password

4. Connect Google Sheets Scope
Add service account JSON
Share sheet with Service Account email


## 🧾 License & Copyright

© 2025 Hafeezul Deen S  
All Rights Reserved.  
Unauthorized copying, reproduction, or redistribution of this project,  
in full or in part, is strictly prohibited.
