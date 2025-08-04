Threat Hunting Report: Windows Event Logs

Analyst
Marvellous Onohwakpor

Date of Analysis
August 4th, 2025


Objective

To simulate suspicious login activity and analyze Windows Event Logs for potential signs of unauthorized access.



Environment

- OS: Windows 10 (VirtualBox VM)
- Tools Used: Event Viewer, Windows Security Logs



Findings
1. Failed Login Attempt

- Event ID: 4625
- Log Name: Security
- Time Logged: 04/08/2025 12:36:33
- Computer Name: DESKTOP-DUM42MK
- Failure Reason: Unknown user name or bad password
- Source: Microsoft Windows Security Auditing
- Keywords: Audit Failure

Screenshot:
![Failed Login](../screenshots/failed-login-event-1.png)

Analysis:
This log indicates a failed login attempt using incorrect credentials. If multiple of these occur in a short period, it may suggest a brute-force attack or unauthorized access attempt.


Conclusion

The simulation of failed login attempts successfully generated relevant logs, allowing detection through Event Viewer. In a real SOC scenario, repeated Event ID 4625 logs would be flagged for immediate review.


