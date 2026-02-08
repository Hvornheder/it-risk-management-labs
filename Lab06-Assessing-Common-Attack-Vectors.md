# Lab 06: Assessing Common Attack Vectors

## Overview
This lab focused on understanding how attackers gain unauthorized access by exploiting common attack vectors, including injection attacks, malware delivery, denial-of-service behavior, and social engineering. The objective was to simulate these techniques in a controlled environment and evaluate the defensive measures that reduce risk.

## Objectives
- Simulate common attack vectors in a controlled lab environment
- Observe how web vulnerabilities and user interaction can lead to compromise
- Identify defensive measures to mitigate injection, malware, denial-of-service, and social engineering attacks
- Reinforce the value of layered defenses and continuous monitoring

## Tools & Technologies Used
- OWASP Juice Shop (web application testing)
- Kali Linux
- Metasploit Framework (msfvenom)
- Social Engineering Toolkit (SET)
- pfSense (observing resource exhaustion / state limits)

## Key Activities
- Performed injection-based testing and executed DOM-based and reflected XSS payloads in a vulnerable web application
- Validated successful access scenarios (including elevated access/login behavior) as part of attack simulation
- Generated a malware payload using msfvenom and observed post-execution behavior (including system information collection)
- Observed distributed denial-of-service conditions and related firewall/resource impacts (e.g., connection failure and pf state limits)
- Built a phishing simulation using SET, including composing and sending a phishing email as part of the social engineering exercise
- Documented attack outcomes and developed defensive recommendations for each attack category

## Key Findings
- Web application vulnerabilities can rapidly escalate from client-side execution to broader compromise if not contained
- Malware delivery combined with user interaction increases the likelihood of endpoint compromise
- Denial-of-service conditions can disrupt availability and trigger firewall/resource limits
- Social engineering remains a high-probability entry point when users are not trained and strong authentication is not enforced

## Security Implications
- Strong input validation and secure coding practices reduce injection and XSS risk
- Endpoint protection and restrictive execution controls reduce malware impact
- DDoS resilience requires layered controls (attack surface reduction + protective services)
- Awareness training and MFA significantly reduce social engineering effectiveness
- Continuous monitoring is critical because real-world attacks are often multi-stage and layered

## Key Takeaways
This lab reinforced how attackers combine technical vulnerabilities with user-driven exploitation to achieve compromise. Performing these exercises in a controlled environment strengthened my understanding of layered defense strategies, the importance of secure configuration and validation, and the value of active monitoring in detecting and containing threats.

## Supporting Documentation
- [Assessing Common Attack Vectors (Lab Report PDF)](https://github.com/user-attachments/files/25168053/Lab6_Assessing_Common_Attack_Vectors_4e_-_Hunter_Vornheder.pdf)
