# Lab 03: Performing Packet Capture and Traffic Analysis

## Overview
This lab focused on analyzing network traffic to understand how data is transmitted across networks and how insecure communication protocols expose sensitive information. Packet capture and traffic inspection techniques were used to examine both encrypted and unencrypted traffic, identify protocol behavior, and evaluate wireless network security risks.

## Objectives
- Capture and analyze network traffic using packet inspection tools
- Identify differences between encrypted and unencrypted protocols
- Analyze packet payloads, ports, and protocol behavior
- Evaluate wireless security mechanisms and authentication processes
- Understand common attack techniques targeting network communications

## Tools & Technologies Used
- Wireshark (packet capture and traffic analysis)
- ICMP, HTTP, FTP, SSH protocol analysis
- Wireless network analysis
- SSID and encryption protocol inspection
- WPA/WPA2 four-way handshake analysis
- aireplay-ng (deauthentication attack simulation)

## Key Activities
- Captured and analyzed network traffic using Wireshark
- Inspected ICMP, HTTP, FTP, and SSH packets to observe protocol behavior
- Analyzed packet payloads, destination ports, and encryption usage
- Identified plaintext data transmission in unencrypted protocols
- Examined wireless network SSIDs and encryption configurations
- Analyzed the WPA/WPA2 four-way handshake used for secure Wi-Fi authentication
- Simulated deauthentication attacks using aireplay-ng to evaluate wireless security risks

## Key Findings
- Unencrypted protocols such as HTTP and FTP expose sensitive data in plaintext
- Encrypted protocols significantly reduce the risk of credential interception
- Wireless networks are vulnerable to deauthentication attacks if improperly secured
- Packet inspection can reveal misconfigurations, insecure protocols, and attack activity

## Security Implications
- Use of encrypted protocols is critical for protecting sensitive data in transit
- Wireless networks must be properly configured with strong encryption and authentication
- Continuous traffic monitoring can help identify malicious activity and misconfigurations
- Packet analysis is a valuable skill for detecting network-based attacks

## Key Takeaways
This lab demonstrated how packet capture and traffic analysis support network security monitoring and threat detection. Understanding protocol behavior and encryption mechanisms enables security professionals to identify weaknesses, investigate suspicious activity, and protect network communications from attack.

## Supporting Documentation
- [Performing Packet Capture and Traffic Analysis (Lab Report PDF)](https://github.com/user-attachments/files/25165752/Lab3_Performing_Packet_Capture_and_Traffic_Analysis_4e_-_Hunter_Vornheder.pdf)
