# Lab 09: Configuring Backup and Recovery Functions

## Overview
This lab focused on implementing backup, recovery, and high-availability mechanisms to support business continuity, disaster recovery, and system resilience. The objective was to ensure that critical systems could be restored quickly after failures while maintaining availability through redundancy and load balancing.

## Objectives
- Implement system state backups for critical infrastructure
- Configure shared storage for high availability
- Deploy load balancing and failover mechanisms
- Test disaster recovery and continuity processes

## Tools & Technologies Used
- Windows Server Backup
- Windows Recovery Wizard
- Linux NFS (Network File System)
- pfSense Firewall
- HAProxy
- DNS hostname overrides

## Key Activities
- Installed and configured Windows Server Backup to perform daily System State backups on a domain controller
- Verified recovery readiness using the Windows Recovery Wizard
- Configured an NFS shared file system across multiple Linux web servers
- Implemented HAProxy on pfSense to load balance traffic between backend web servers
- Configured frontend and backend pools (`http_access` and `http_server_pool`)
- Performed failover testing by intentionally disabling a server and validating automatic traffic rerouting
- Monitored session persistence and traffic flow using HAProxy statistics

## Key Takeaways
This lab reinforced the importance of proactive backup and recovery planning as a core component of IT infrastructure resilience. System State backups enable rapid recovery from failures, while load balancing and shared storage improve availability and performance. Failover testing demonstrated the necessity of continuous monitoring and health checks to ensure uninterrupted service delivery. These practices collectively support effective business continuity and disaster recovery planning.

## Supporting Document
- [Lab 9 – Configuring Backup and Recovery Functions (PDF)](https://github.com/user-attachments/files/25168187/Lab9_Configuring.Backup.and.Recovery.Functions.4e.-.Hunter.Vornheder.pdf)

