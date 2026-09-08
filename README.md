# 🔐 SecureTrust Config

> **Centralized configuration management for the SecureTrust microservices ecosystem.**

This repository contains centralized, environment-specific configuration files used by the **Spring Cloud Config Server** to manage configuration across SecureTrust microservices.

---

## 🏗️ Services

| Service | Description |
|---|---|
| 💳 **Accounts** | Account-related configuration |
| 💰 **Cards** | Card-related configuration |
| 🏦 **Loans** | Loan-related configuration |

---

## 🌎 Environments

🟢 **Default** &nbsp; | &nbsp; 🟡 **QA** &nbsp; | &nbsp; 🔴 **Production**

---

## 📂 Configuration Files

```text
securetrust-config/
│
├── 📄 accounts.yml
├── 📄 accounts-qa.yml
├── 📄 accounts-prod.yml
│
├── 📄 cards.yml
├── 📄 cards-qa.yml
├── 📄 cards-prod.yml
│
├── 📄 loans.yml
├── 📄 loans-qa.yml
└── 📄 loans-prod.yml
