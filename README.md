# phishing_email
# Phishing Email Analysis (Kali Linux)

## 📌 Project Overview
This project demonstrates the analysis of a suspicious phishing email using Kali Linux tools.  
The objective is to identify phishing indicators such as spoofed domains, malicious URLs, and social engineering tactics.

---

## 🎯 Objective
To examine a phishing email sample and identify characteristics that indicate it is a phishing attempt.

---

## 🛠 Tools Used
- Kali Linux
- Nano (Text Editor)
- grep
- whois
- nslookup
- nmap
- Git & GitHub

Online Tools:
- MXToolbox (Header Analyzer)
- VirusTotal (URL/Domain Scan)

---

## 🔎 Steps Performed

### 1️⃣ Created Project Folder
A dedicated folder `phishing_analysis` was created to store files.

### 2️⃣ Created Phishing Email Sample
A sample phishing email was saved as:
- phishing_email.txt

### 3️⃣ Sender Email Analysis
The sender domain used spoofing:
- amaz0n-security.com (0 instead of "o")

This indicates domain impersonation.

### 4️⃣ Suspicious URL Detection
Extracted suspicious URL using grep command:


Detected:
http://amaz0n-login-security.com

This is not an official Amazon domain.

### 5️⃣ Domain Analysis
Used:
- whois
- nslookup

To check:
- Domain registration details
- IP address information

### 6️⃣ Social Engineering Indicators
The email contains:
- Urgent language
- Threat of account suspension
- Generic greeting ("Dear Customer")

These are common phishing tactics.

---

## 🚩 Phishing Indicators Identified

| Indicator | Found |
|------------|--------|
| Spoofed Sender Domain | ✅ |
| Suspicious URL | ✅ |
| Urgent Language | ✅ |
| Threatening Tone | ✅ |
| Generic Greeting | ✅ |

---

## 📄 Files Included
- phishing_email.txt
- report.txt
- README.md

---

## ✅ Conclusion
Based on sender spoofing, suspicious links, urgent language, and domain analysis, the email was identified as a phishing attempt.

This project demonstrates basic phishing analysis techniques using Kali Linux.

---

