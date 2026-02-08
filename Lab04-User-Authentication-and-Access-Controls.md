# Lab 04: Applying User Authentication and Access Controls

## Overview
This lab focused on implementing and verifying user authentication and access control mechanisms within an IT environment. Active Directory and file system permissions were configured to enforce role-based access control (RBAC), ensuring that users were granted only the permissions required for their roles. The objective was to protect system data confidentiality, integrity, and availability by preventing unauthorized access.

## Objectives
- Implement user authentication using Active Directory
- Configure security groups and role-based access controls (RBAC)
- Apply file and folder permissions to restrict access
- Verify authentication and authorization behavior
- Identify risks associated with improper access control configurations

## Tools & Technologies Used
- Active Directory Users and Computers (ADUC)
- Windows Server file permissions
- Role-Based Access Control (RBAC)
- NTFS security permissions
- TrueNAS Access Control Lists (ACLs)
- SMB file sharing

## Key Activities
- Created user accounts and security groups within Active Directory
- Assigned users to groups based on defined roles and responsibilities
- Configured folder-level permissions to restrict access by role
- Applied NTFS permissions to HR, Manager, and Development folders
- Configured SMB shares and datasets within TrueNAS
- Verified access behavior by testing authorized and unauthorized user access
- Observed and documented failed authentication and access attempts

## Key Findings
- Properly configured RBAC effectively prevents unauthorized data access
- Users with insufficient permissions were correctly denied access to restricted resources
- Misconfigured permissions can introduce significant data exposure risks
- Access controls must be tested and validated to ensure enforcement

## Security Implications
- Principle of Least Privilege (PoLP) is essential for minimizing attack surface
- Centralized authentication and access management improves security oversight
- File system permissions are a critical layer of defense against insider threats
- Continuous validation of access controls helps prevent privilege escalation

## Key Takeaways
This lab demonstrated the importance of strong authentication and access control mechanisms in securing IT systems. Implementing RBAC and validating permissions ensures that users can only access resources necessary for their roles, reducing the risk of data breaches and unauthorized activity.

## Supporting Documentation
- [Applying User Authentication and Access Controls (Lab Report PDF)](https://github.com/user-attachments/files/25166499/Lab4_Applying_User_Authentication_and_Access_Controls_4e_-_Hunter_Vornheder.pdf)
