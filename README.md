# Secure Networked System with Public Key Infrastructure (PKI)

## Project Overview
This project aims to secure a networked system using **Public Key Infrastructure (PKI)** by implementing **Transport Layer Security (TLS)** on **HTTP** for HTTPS connections. The setup involves configuring a **Certification Authority (CA)**, securing a **web server** with **Apache2** on Linux, managing **DNS and firewall settings**, generating **Certificate Signing Requests (CSR)**, issuing certificates, installing **SSL**, and verifying security using **Wireshark**.

## Features
- Establishment of a **Certification Authority (CA)**
- Configuration of **Apache2** web server for **HTTPS**
- Implementation of **TLS encryption**
- **DNS and firewall configuration**
- **CSR generation** and certificate issuance
- Installation and testing of **SSL certificates**
- **Security verification** using **Wireshark**

## Prerequisites
Ensure you have the following installed and configured:
- **Ubuntu/Linux**
- **Apache2 Web Server**
- **OpenSSL**
- **Wireshark**
- **DNS Server** (if applicable)
- **Firewall (UFW/Iptables)**

## Security Measures
- **TLSv1.2/TLSv1.3 enforced**
- **Strong cipher suites enabled**
- **HTTP to HTTPS redirection enabled**
- **Firewall rules restricting unnecessary ports**

## Conclusion
This project ensures secure web communication using PKI and TLS encryption, effectively preventing **MITM attacks**, **data interception**, and unauthorized access. 

---
**Author:** [Your Name]  
**Date:** [YYYY-MM-DD]  
**License:** MIT  
