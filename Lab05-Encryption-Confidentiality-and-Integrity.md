# Lab 05: Using Encryption to Enhance Confidentiality and Integrity

## Overview
This lab focused on implementing cryptographic techniques to protect data confidentiality and integrity for data at rest and data in transit. Both symmetric and asymmetric encryption methods were used within a hybrid encryption model to securely encrypt files, exchange encryption keys, and verify data authenticity through digital signatures.

## Objectives
- Understand the role of encryption in protecting sensitive data
- Implement symmetric and asymmetric encryption techniques
- Apply hybrid encryption models for secure communication
- Use digital signatures to ensure authenticity and integrity
- Perform secure file transfers using encrypted protocols

## Tools & Technologies Used
- OpenSSL
- GnuPG (GPG)
- AES-256 symmetric encryption
- Asymmetric public/private key cryptography
- Digital signatures and hashing
- Kleopatra (key management and signature verification)
- WinSCP (secure file transfer)

## Key Activities
- Generated asymmetric key pairs using GPG
- Encrypted files using symmetric AES-256 encryption
- Protected encryption passphrases using public key encryption
- Decrypted files by securely combining asymmetric and symmetric keys
- Created and verified digital signatures to ensure message authenticity
- Validated data integrity through cryptographic hashing
- Transferred encrypted files securely using WinSCP

## Key Findings
- Encryption is critical for preventing unauthorized access to sensitive data
- Hybrid encryption combines the efficiency of symmetric encryption with the security of asymmetric key exchange
- Digital signatures provide authentication, integrity validation, and non-repudiation
- Secure file transfer protocols protect data confidentiality during transmission

## Security Implications
- Unencrypted data is vulnerable to interception and unauthorized access
- Strong encryption algorithms such as AES-256 significantly reduce exposure risk
- Proper key management is essential to maintaining cryptographic security
- Digital signatures help prevent data tampering and impersonation attacks

## Key Takeaways
This lab demonstrated how encryption technologies protect data confidentiality and integrity across systems. Implementing hybrid encryption models and digital signatures ensures secure communication, validates data authenticity, and mitigates the risk of data breaches during storage and transmission.

## Supporting Documentation
- [Using Encryption to Enhance Confidentiality and Integrity (Lab Report PDF)](https://github.com/user-attachments/files/25166988/Lab5_Using_Encryption_to_Enhance_Confidentiality_and_Integrity_4e_-_Hunter_Vornheder.3.pdf)
