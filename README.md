# FUTURE_CS_02
SOC Analysis using Splunk SIEM - log ingestion, threat detection, and security event analysis
# FUTURE_CS_02 – SIEM Log Analysis Using Splunk

## Overview
This task focuses on performing basic Security Operations Center (SOC) activities using
Splunk SIEM. The objective was to ingest logs, analyze security events, detect threats,
and understand how SIEM tools are used in real-world cybersecurity environments.

---

## Tools Used
- Splunk Enterprise (Local Installation)
- Sample Security Log File
- Windows OS

---

## Task Objectives
- Ingest security log data into Splunk
- Analyze logs for suspicious activity
- Detect failed login attempts
- Identify malware-related events
- Understand SIEM-based threat detection

---

## Analysis Performed

### 1. Log Ingestion
- Uploaded a sample security log file into Splunk
- Configured source type and index
- Verified successful indexing

### 2. Failed Login Detection
Search Query:
- Identified failed login attempts from IP address 192.168.1.10
- Indicates possible brute-force or unauthorized access attempt

### 3. Malware Detection
Search Query:
- Detected event: malware detected trojan.exe
- Confirms malware activity recorded in logs

---

## Security Findings
- Repeated failed login attempts may indicate an attack attempt
- Malware detection highlights endpoint compromise risk
- SIEM tools help correlate and detect threats early

---

## Conclusion
This task demonstrates practical use of Splunk SIEM for monitoring, detecting, and
analyzing security incidents. It provides hands-on experience in SOC operations and
threat detection.

---

## Screenshots
Screenshots of log ingestion, searches, and detected events are available in the
screenshots/ folder.
