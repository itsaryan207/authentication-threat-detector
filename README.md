# authentication-threat-detector
Python-based authentication log monitoring and threat detection system for identifying suspicious login activity and brute-force attacks in IAM environments.

# Enterprise Authentication Log Analyzer

## Overview

This project is a Python-based mini SIEM (Security Information and Event Management) system designed to analyze authentication logs and detect suspicious login activity.

The system simulates real-world cybersecurity monitoring workflows used in Identity and Access Management (IAM) and Security Operations Center (SOC) environments.

It identifies:
- Failed login attempts
- Suspicious IP activity
- Potential brute-force attacks
- Authentication anomalies

---

## Features

- Authentication log parsing
- Failed login detection
- Suspicious IP monitoring
- Brute-force attack detection
- Security alert generation
- CSV report generation
- Data visualization using Matplotlib

---

## Technologies Used

- Python
- Pandas
- Matplotlib
- Regex
- CSV Processing

---

## Project Structure

```bash
enterprise-authentication-log-analyzer/
│
├── analyzer.py
├── logs.txt
├── suspicious_activity_report.csv
├── failed_login_chart.png
├── README.md
└── requirements.txt
```

---

## Installation

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Run the Project

```bash
python analyzer.py
```

---

## Sample Output

The system:
- Parses authentication logs
- Detects suspicious login attempts
- Identifies brute-force behavior
- Generates security reports
- Creates authentication activity visualizations

---

## Cybersecurity Concepts Demonstrated

- SIEM Fundamentals
- Authentication Monitoring
- Threat Detection
- Security Log Analysis
- Incident Investigation
- Identity and Access Management (IAM)

---

## Future Improvements

- Real-time log monitoring
- Email alert integration
- Dashboard UI
- Machine learning-based anomaly detection
- Integration with cloud logging systems

---

## Author

Aryan Dumbhare
