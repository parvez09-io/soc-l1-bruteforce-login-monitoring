# SOC L1 – Brute Force Login Attack Monitoring

## 📌 Project Overview
This project demonstrates a real-world SOC Level 1 investigation of a brute force
login attack using Linux authentication logs and SIEM monitoring.

## 🎯 Objective
- Detect brute force login attempts
- Analyze Linux authentication logs
- Identify Indicators of Compromise (IOC)
- Escalate confirmed incidents

## 🛠 Tools Used
- Linux (Ubuntu)
- SIEM (Splunk / Wazuh)
- auth.log
- Firewall (UFW / iptables)

## 🔍 Investigation Steps
1. Alert received from SIEM
2. Analyzed `/var/log/auth.log`
3. Identified repeated failed login attempts
4. Extracted attacker IP
5. Confirmed true positive
6. Escalated incident to SOC L2

## 📄 Outcome
- Brute force attack confirmed
- Malicious IP blocked
- Incident documented

## 📌 Skills Demonstrated
- SOC Monitoring
- Log Analysis
- Incident Response (L1)
- SIEM Alert Triage
