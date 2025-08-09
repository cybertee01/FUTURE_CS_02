# FUTURE_CS_02
A report on my security alert monitoring and incident response 

A simulated security operations center (SOC) where I practice identifying and responding to digital threats.

**The Mission** 

This project was a deep dive into the world of Security Operations. I took on the role of a SOC analyst, using a SIEM (Security Information and Event Management) tool to monitor simulated security alerts. The goal was to sift through the noise, identify actual threats, classify them, and document my findings in a professional incident response report. It's like being a digital detective, with logs as my clues!

**Skills on Display** 

During this project, I gained practical experience in:
Log Analysis: Learning to interpret log data to spot anomalies and suspicious patterns.
Alert Triage: Prioritizing security alerts to focus on the most critical threats first.
Incident Classification: Categorizing security events based on their type and severity.
SOC Operations Basics: Understanding the fundamental workflows and responsibilities within a security operations center.

**The Arsenal** 

To get the job done, I used a few essential tools of the trade:
Splunk: A powerful SIEM tool used for searching, monitoring, and analyzing machine-generated big data.
Sample Log Files: Simulated log data that provided a realistic environment for analysis.

**Findings & Deliverables** 

The culmination of this project is a detailed Incident Response Report. This report outlines the security incidents discovered, including:
Alert Analysis: A breakdown of the alerts, what they mean, and why they were flagged as suspicious.
Incident Classification: Categorizing each incident by threat type (e.g., malware, login attempts).
Remediation Recommendations: Actionable steps to mitigate the identified threats and prevent future occurrences.
This report is a testament to my ability to move from raw data to a clear, actionable security plan.

Incident Response Report: Analysis of Simulated Security Alerts

Overview:
A total of 50 events were analyzed from the provided log files11. The logs were from a host with the source
C:\Users\gideo\Downloads\SOC_Task2_Sample_Logs.txt and a sourcetype of FUTURE INTERN CSO2 The analysis focused on identifying and classifying suspicious activities.

Key Findings:
Several suspicious activities were identified, including:
Malware Detections:
A user named
bob was associated with a Ransomware threat. The log entry shows an action of malware detected and a threat of Ransomware This occurred on July 3, 2025, at 09:10:14 from IP address 172.16.

A user named ava was associated with a Rootkit Signature threat on July 3, 2025, at 07:51:14 from IP address 10.0.0.5.

Multiple Trojan threats were detected, linked to users charlie, bob, david, and eve

A Worm infection was detected for user bob

Spyware was detected for user alice

Login and File Access Attempts:
There were multiple instances of successful and failed login attempts for various users. An action of file access was recorded for users bob, eve, charlie, and david


Incident Classification:
The identified incidents can be classified as follows:
Critical: Malware infections, specifically the Ransomware and Rootkit threats, which pose a high risk of data compromise and system control


High: Trojan, Worm, and Spyware detections, as these can lead to data theft, system degradation, and network lateral movement


Medium: Failed login attempts, which may indicate a brute-force attack or unauthorized access attempts


Remediation Recommendations:
Isolate Affected Systems: Immediately quarantine the devices associated with the users where malware was detected (bob, ava, charlie, david, eve, alice) to prevent the threats from spreading.


Password Reset: Force a password reset for all users involved, especially those with failed login attempts, to mitigate potential credential compromise.


Antivirus/Endpoint Protection Scan: Run a full system scan with up-to-date antivirus software on all affected hosts.
Security Awareness Training: Provide additional training to all users on how to identify and avoid phishing emails and malicious downloads, which are common vectors for malware.


Review Access Controls: Investigate the successful file access events to ensure they align with legitimate business operations. Implement the principle of least privilege to restrict access to sensitive files.
Threat Hunting: Conduct a deeper threat hunt using the identified indicators of compromise (IP addresses, usernames, and threat types) to find any other related malicious activity in the logs


Patch Management: Ensure all systems are fully patched and updated to prevent exploitation of known vulnerabilities





