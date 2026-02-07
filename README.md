Threat Modelling Project – Web-to-Database Architecture
📌 Overview

This repository documents a structured threat modelling exercise conducted on a Web-to-Database architecture responsible for handling user authentication, transactional processing, and sensitive data storage.

The objective of this project was to identify design-level security risks early and propose effective mitigations using industry-standard frameworks and tools.

🏗 System Description

The system follows a three-tier architecture:

Web Interface (User Interaction)

Backend Application Server

SQL Database

It processes sensitive data including user credentials, transactional records, and system logs.

🔍 Threat Modelling Approach

The analysis was conducted using:

STRIDE Framework for threat categorisation

Data Flow Diagrams (DFDs) to identify trust boundaries and attack surfaces

🛠 Tools Used

Microsoft Threat Modeling Tool

OWASP Threat Dragon

Both tools were used to compare depth of analysis and validate findings.

🚨 Key Risks Identified

Unauthorized access to sensitive database records

Spoofing of trusted system components

Audit log tampering affecting incident response

🛡 Mitigations Proposed

Mutual TLS (mTLS) for secure service authentication

Role-Based Access Control (RBAC) with least privilege

Transparent Data Encryption (TDE) for data at rest

Input validation to protect logging mechanisms

📄 Full Report

📘 Threat Modelling Report (PDF):
/report/Threat_Modelling_Report.pdf

⚠️ Disclaimer

This project was conducted in a controlled lab environment for educational purposes only.
