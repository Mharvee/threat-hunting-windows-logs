# threat-hunting-windows-logs
# Threat Hunting Project: Windows Event Log Analysis

This project simulates a real-world scenario where a SOC analyst investigates suspicious activities through Windows Event Logs.

Tools Used
- Windows 10 VM
- Event Viewer
- Sigma Rules (for log analysis)
- Notepad/VS Code
- PowerShell (to simulate activity)

Project Structure
- `/logs/` — Sample `.evtx` logs
- `/screenshots/` — Screenshots from analysis
- `/report/` — Final incident report

What I Did
- Simulated user and attacker behavior
- Collected and analyzed Event Logs
- Identified suspicious activity such as:
  - Multiple failed logins
  - Use of PowerShell
  - Account privilege changes
- Documented findings in an analyst-style report

Key Findings
See `report/threat-hunting-report.md`

Created by
Marvellous Onohwakpor
