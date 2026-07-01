🛡️ WebShield Scanner

A Python-based Website Security Assessment Tool that analyzes website security headers, checks common network ports, inspects SSL certificates, and generates automated security reports.

---

🚀 Features

✅ Security Header Analysis
✅ Common Port Scanning
✅ SSL Certificate Inspection
✅ Security Score Calculation
✅ Automated Report Generation
✅ Individual Reports for Each Website
✅ Report Management System
✅ Interactive Command-Line Interface (CLI)

---

🛠️ Technologies Used

- Python 3
- Requests Library
- Socket Programming
- SSL Module
- File Handling
- OS Module

---

📂 Project Structure

WebShield-Scanner/
│
├── web_vulnerability_scanner.py
├── requirements.txt
├── README.md
└── reports/
    ├── google_com_report.txt
    ├── github_com_report.txt
    └── openai_com_report.txt

---

⚙️ Installation

Clone the Repository

git clone https://github.com/yourusername/WebShield-Scanner.git
cd WebShield-Scanner

Install Dependencies

pip install -r requirements.txt

Or install manually:

pip install requests

---

▶️ Running the Project

python web_vulnerability_scanner.py

---

📋 Menu Options

1. Scan Website
2. Clear All Reports
3. Exit

---

🔍 Security Checks Performed

1. Security Headers

- Content-Security-Policy
- Strict-Transport-Security
- X-Frame-Options
- X-Content-Type-Options
- Referrer-Policy

2. Common Ports

- FTP (21)
- SSH (22)
- SMTP (25)
- HTTP (80)
- HTTPS (443)
- MySQL (3306)

3. SSL Certificate Analysis

- Certificate Availability
- Expiry Date

---

📄 Sample Report

============================================================
WEBSITE SECURITY SCAN REPORT
============================================================
Website: https://github.com
Host: github.com
Scan Time: 2026-07-01 08:30:15
Security Score: 4/5
------------------------------------------------------------
Content-Security-Policy: FOUND
Strict-Transport-Security: FOUND
X-Frame-Options: FOUND
X-Content-Type-Options: FOUND
Referrer-Policy: MISSING
Port 80 (HTTP): OPEN
Port 443 (HTTPS): OPEN
SSL Certificate: FOUND
Certificate Expiry: Aug 15 12:00:00 2026 GMT
============================================================

---

🎯 Learning Outcomes

- HTTP Security Headers
- Network Programming
- Socket Programming
- SSL Certificate Inspection
- Cybersecurity Automation
- File Handling in Python
- Report Generation

---

🔮 Future Improvements

- Multi-threaded Port Scanning
- Export Reports to PDF and CSV
- GUI Version
- Subdomain Enumeration
- Vulnerability Database Integration
- Docker Support

---

📌 Use Cases

- Cybersecurity Learning
- Academic Projects
- Security Awareness
- Portfolio and Resume Project
- Internship Demonstration Project

---

👩‍💻 Author

Shravani Dhaybar

Cybersecurity & Digital Science Student | Python Developer | Aspiring Security Engineer

