# 🛡️ SOC Monitoring & Incident Response Simulation

## Security Operations Center (SOC) Analyst Practice Project

This repository contains a hands-on project simulating the daily activities of a **Security Operations Center (SOC) analyst**: monitoring alerts, analyzing logs, and responding to potential incidents.

---

## 📌 Project Overview

In this project, I:

* Set up and explored **Splunk Free SIEM** for log ingestion and analysis.
* Analyzed simulated logs containing authentication events, network activity, and malware detections.
* Identified and prioritized suspicious activities (failed logins, unusual IPs, brute-force attempts, malware alerts).
* Built **Splunk dashboards** to visualize alerts and trends.
* Classified alerts by severity (High, Medium, Low).
* Drafted an **Incident Response Report** and a sample communication email to management.

---

## 📊 Deliverables

* **Incident Response Report** (PDF)
* **Screenshots** of Splunk dashboards and analyzed alerts
* **Alert Classification Log** (spreadsheet)
* **Communication Email Draft**

---

## 🛠️ Tools & Technologies Used

* **Splunk Free Trial** (SIEM tool)
* **Linux (Kali)** for setup and testing
* **Excel / Sheets** for alert classification
* **Markdown & PDF** for reporting

---

## 🎯 Skills Practiced

* Basic **SIEM log analysis**
* **Threat detection & classification**
* **Incident response documentation**
* **SOC analyst workflow simulation**
* Effective **reporting and communication** of security incidents

---

## 🚀 How to Replicate

1. Install **Splunk Free** or use Splunk Cloud Trial.
2. Ingest the provided sample logs (`SOC_Sample_Logs.txt`).
3. Use queries to detect anomalies, e.g.:
   ```spl
   source="SOC_Sample_Logs.txt" "login failed" | stats count by ip
   ```
4. Build dashboards to visualize the results.
5. Document your findings in a structured report.

---

## Author

**Abdelalim Saada** — Cybersecurity Engineer
[LinkedIn](https://www.linkedin.com/in/abdelalim-saada-5732a3350/) · [GitHub](https://github.com/abdelalim-saada)
