# Lab 08: Implementing Security Monitoring and Logging

## Overview
This lab focused on implementing security monitoring and logging mechanisms to detect unauthorized actions across systems and networks. The primary objective was to configure host-based and network-based monitoring tools that provide visibility into authentication failures, cryptographic errors, suspicious network activity, and unauthorized file modifications.

## Objectives
- Implement centralized logging for Windows and Linux systems
- Detect unauthorized access attempts through system log analysis
- Monitor network traffic for suspicious activity using intrusion detection tools
- Implement file integrity monitoring to detect unauthorized system changes
- Understand how layered monitoring improves incident detection and response

## Tools & Technologies Used
- Windows Event Viewer
- rsyslog (Linux logging)
- Snort (Network Intrusion Detection System)
- Tripwire (File Integrity Monitoring)
- ICMP traffic analysis
- VPN tunnel configuration and traceroute

## Key Activities
- Configured Windows Event Viewer to track failed login attempts and cryptographic audit failures
- Identified cryptographic operation errors using Event ID 5061
- Implemented rsyslog on Linux systems to monitor authentication failures and system events
- Installed and configured Snort to monitor network traffic and alert on suspicious ICMP-based activity
- Enabled Snort Legacy Blocking Mode for real-time intrusion prevention
- Deployed Tripwire to monitor file integrity and detect unauthorized system modifications
- Selected and evaluated VPN tunnel modes based on traceroute analysis

## Key Findings
- System and authentication logs provide critical insight into unauthorized access attempts
- Network monitoring detects reconnaissance and probing activity that may precede attacks
- File integrity monitoring is essential for identifying stealthy system changes
- Cryptographic audit failures can indicate encryption misconfigurations or security issues
- Combining host, network, and integrity monitoring creates a stronger security posture

## Security Implications
- Proactive monitoring reduces dwell time by detecting threats early
- Centralized logging enables faster investigation and correlation of security events
- Intrusion detection systems enhance visibility into network-based attack techniques
- File integrity monitoring protects against unauthorized persistence mechanisms
- Layered monitoring significantly improves overall incident detection and response

## Key Takeaways
This lab demonstrated that effective security monitoring and logging are critical components of a defensive security strategy. By correlating host logs, network alerts, and file integrity changes, organizations gain the visibility required to detect, analyze, and respond to security incidents before they escalate into full system compromise.

## Supporting Documentation
- [Lab 08 – Implementing Security Monitoring and Logging (PDF)](https://github.com/user-attachments/files/25168106/Lab8_Implementing.Security.Monitoring.and.Logging.4e.-.Hunter.Vornheder.pdf)
