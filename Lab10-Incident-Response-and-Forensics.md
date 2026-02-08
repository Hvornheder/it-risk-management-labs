# Lab 10: Performing Incident Response and Forensic Analysis

## Overview
This lab focused on performing incident response and forensic analysis to investigate potential security breaches. The primary objective was to analyze network traffic and disk artifacts in order to identify malicious activity, reconstruct an incident timeline, and assess the overall scope of system compromise.

## Objectives
- Analyze network traffic captures for signs of malicious activity
- Perform disk forensic analysis to identify hidden malware
- Correlate evidence from multiple data sources
- Reconstruct an incident timeline and document findings
- Develop an incident response report outlining impact and remediation

## Tools & Technologies Used
- NetWitness Investigator
- Autopsy (Digital Forensics Suite)
- PCAP analysis
- Disk image analysis
- Incident Response documentation

## Key Activities
- Analyzed PCAP files using NetWitness Investigator to identify malicious sessions and possible data exfiltration
- Examined a disk image using Autopsy to detect hidden malware, including keylogger artifacts
- Identified forensic artifacts such as scheduled tasks, modified system files, and executable traces
- Correlated network evidence with disk artifacts to reconstruct the incident timeline
- Discovered and analyzed execution of the "Actual Keylogger" executable
- Documented affected systems, users, event timestamps, and vulnerabilities in an Incident Response Report

## Key Findings
- Network traffic analysis revealed suspicious sessions consistent with data exfiltration attempts
- Disk forensic analysis uncovered stealthy malware installation techniques
- Correlating network and host evidence was critical to identifying the full scope of compromise
- Attack activity evolved over time, requiring continuous reassessment during the investigation

## Key Takeaways
This lab demonstrated the importance of accurate forensic analysis and structured incident response procedures. Correlating data from diverse sources enabled the detection of subtle attack patterns that would be missed in isolated analysis. The exercise reinforced the need for real-time monitoring, early threat detection, and thorough documentation to ensure effective containment, remediation, and post-incident analysis.

## Supporting Document
- [Lab 10 – Performing Incident Response and Forensic Analysis (PDF)](https://github.com/user-attachments/files/25168749/Lab10_Performing.Incident.Response.and.Forensic.Analysis.4e.-.Hunter.Vornheder.pdf)
