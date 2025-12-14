# Security Incident Analysis Report – Ransomware Attack

## Incident Summary
This report documents the analysis of a simulated ransomware incident detected within an enterprise Windows environment. The objective is to demonstrate SOC analyst incident handling, triage, investigation, and response methodology aligned with NIST 800-61.

## Incident Type
- Malware / Ransomware
- Initial Access: Phishing Attachment
- Impacted Systems: Windows 10 Workstations

## Detection Source
- Endpoint Detection and Response (EDR)
- SIEM Correlation Alerts
- Suspicious PowerShell execution

## Timeline (UTC)
| Time | Event |
|----|----|
| 09:12 | User opened phishing email attachment |
| 09:14 | PowerShell spawned from Word |
| 09:16 | Suspicious outbound connection detected |
| 09:18 | File encryption activity observed |
| 09:21 | Host isolated |

## Severity
**High** – Active ransomware execution with lateral movement potential.

