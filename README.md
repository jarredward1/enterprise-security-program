# Enterprise Security Program: Policies, Standards & Procedures (NIST SP 800-53, PCI DSS)

> A full information security program for a fictional e-commerce company preparing for IPO, structured as a governance hierarchy of a plan, policies, standards, and procedures mapped to NIST SP 800-53 and aligned with PCI DSS.

---

## 📌 Overview

SnowBe Online is a growing e-commerce and retail company handling sensitive customer data including PII, credit card information, and order histories. As the company scales toward an IPO, this security program establishes the formal policies, standards, and procedures needed to protect its digital and physical assets.

This project simulates a real-world security planning engagement. This includes identifying roles and responsibilities, defining policy controls, and aligning with industry compliance frameworks.

---

## 🎯 Objectives

- Protect customer PII and cardholder data across e-commerce and retail operations
- Establish enforceable security policies aligned with NIST SP 800-53 and PCI DSS
- Define clear roles and responsibilities across all security functions
- Ensure compliance readiness as SnowBe prepares for public offering
- Reduce risk from insider threats, misconfigurations, and third-party vendors

---

## 🛠️ Frameworks & Standards Applied

| Framework | Purpose |
|-----------|---------|
| **NIST SP 800-53** | Primary control framework for access, integrity, and system protection |
| **PCI DSS** | Payment card data security and compliance |
| **NIST SDLC** | Secure system development lifecycle guidance |

---

## 📂 Scope

This program covers all employees, contractors, vendors, and third-party partners who access SnowBe systems. It applies to:

- Corporate office environments
- Retail point-of-sale locations
- AWS-hosted cloud infrastructure
- Remote access and mobile endpoints

---

## 🏛️ Document Hierarchy

This repository follows a standard governance hierarchy. Each level gets more specific and changes more often:

- **Plan** — the overarching security strategy
- **Policies** — high-level rules stating *what* must happen and *why*, mapped to NIST 800-53 controls
- **Standards** — the specific, measurable requirements that enforce the policies
- **Procedures** — the step-by-step instructions to carry the requirements out

---

## 👥 Roles Defined

The plan establishes 11 security roles with clearly defined responsibilities:

- Chief Information Security Officer (CISO)
- IT Security Manager
- Cloud Systems Administrator
- Network Security Administrator
- Access Control Administrator
- Incident Response Coordinator
- Compliance Officer
- Security Awareness & Training Coordinator
- System Administrators
- Developer
- Project Manager

---

## 📁 Repository Contents

### Plan

- [Enterprise Security Plan](./Security_Plan.pdf) — the overarching security strategy for SnowBe Online
- [Case Study](./Case_Study.pdf) — supporting case study

### Policies

| Policy | Control |
|--------|---------|
| [Separation of Duties & Least Privilege](./Policies/Separation_of_Duties%20and_Least_Privilege_Policy.pdf) | `AC-5 & AC-6` |
| [Device Lock & Session Termination](./Policies/Device_Lock_and%20Session_Termination_Policy.pdf) | `AC-11 & AC-12` |
| [Change Control Management](./Policies/Change_Control_Management_Policy.pdf) | `CCM-03` |
| [Data Retention & Disposal](./Policies/Data_Retention_and%20Disposal_Policy.pdf) | `DR-01` |
| [Security Maturity](./Policies/Security_Maturity%20Policy.pdf) | `SM-01` |
| [Software Patch Management](./Policies/Software_Patch_Management_Policy.pdf) | `SPM-01` |
| [System Development Life Cycle](./Policies/System_Development_Life_Cycle_Policy.pdf) | `SDLC-01` |
| [Vulnerability Management](./Policies/Vulnerability_Management_Policy.pdf) | `VM-01` |

### Standards

| Standard | Control |
|----------|---------|
| [Password Standard](./Standards/Password_Standard.pdf) | `PWS-04` |

### Procedures

| Procedure | Control |
|-----------|---------|
| [New Account Creation Procedure](./Procedures/New_Account_Creation_Procedure.pdf) | `ACP-03` |
| [Linux Password Procedure](./Procedures/Linux_Password%20Procedure.pdf) | `LPP-04` |

---

## 🔄 Version History

| Version | Date | Changes |
|---------|------|---------|
| 1.0 | 11/03/2025 | Original Draft |
| 2.0 | 11/10/2025 | Added Access Controls |
| 3.0 | 11/17/2025 | Added Encryption Controls |
| 4.0 | 03/29/2026 | Added Various Policies (current) |

---

## 👤 Author

**Jarred Ward**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?logo=linkedin&style=for-the-badge)](https://www.linkedin.com/in/jarredward1/)
