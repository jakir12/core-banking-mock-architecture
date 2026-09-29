# 🏦 Core Banking Architecture & Mock API Demo

> **Disclaimer:** This repository serves as a high-level architectural demonstration of my expertise in building secure, enterprise-grade banking systems. Due to NDA and strict security compliances with my current and past employers, actual proprietary source code, database schemas, and API keys are strictly excluded.

## 🚀 System Overview
An architectural blueprint and API design concept for handling complex financial workflows. This project outlines the logic for Core Banking Software (CBS) modules, Loan Management, and CLS (Classification of Loan) automation.

## 🛠️ Core Tech Stack & Infrastructure
- **Enterprise Legacy Systems:** Oracle DB, Oracle Forms & Reports
- **Backend Microservices:** .NET Core, Node.js (Express), PHP (Laravel)
- **Database & Caching:** Oracle (Primary ACID Tx), PostgreSQL, Redis (Session/Caching)
- **Security Protocols:** OAuth 2.0, Role-Based Access Control (RBAC), JWT, AES-256 Data Encryption

## 💡 Key Architectural Workflows Demonstrated

### 1. CLS & Written-Off Automation
*   **Batch Processing:** Architecture for daily end-of-day (EOD) batch scripts to identify and classify Non-Performing Loans (NPL).
*   **Rule Engine:** Automated status switching (e.g., Sub-Standard -> Doubtful -> Bad/Loss) based on central bank regulatory guidelines.

### 2. Loan Reschedule Automation
*   **Dynamic Calculation:** Algorithmic approach to recalculate EMI, interest capitalization, and tenure extensions.
*   **Approval Matrix:** Multi-tier authorization workflow before financial payload commitment.

## 🔒 Enterprise Security Measures
*   **SQL Injection Prevention:** Strict usage of parameterized queries and sanitized inputs across all Oracle DB transactions.
*   **Idempotency:** Ensuring API idempotency for all payment and transactional endpoints to prevent duplicate processing.
*   **Audit Logging:** Immutable audit trails for every state change in financial modules.

---
*Developed as a conceptual showcase for modernizing and securing Banking IT infrastructure.*
