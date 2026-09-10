# GRC_LAB_PRACTICE
i ask AI to give me the lab questions and scenario so i can practice the risk Assessment, policy writing, gap analysis and auditing. this project can act as an strong foundation in my GRC carrier ahead.
# DOWNLOAD THE WHOLE FOLDER TO ACCESS EXCEL AND WORD FILE 
------------------------------------------------------------------------------
# GRC Foundations Lab — Northwind Retail

A hands-on, self-directed Governance, Risk & Compliance (GRC) project built around **Northwind Retail**, a fictional 200-employee e-commerce company. This repo contains the full set of GRC artifacts produced across 6 modules + a capstone — the same deliverables a GRC analyst produces in a real role.

## 📋 Scenario

Northwind Retail is a mid-size e-commerce company that:
- Stores customer PII (names, addresses, emails) and processes credit card payments
- Uses **AWS** for hosting, **Salesforce** for CRM, and **Stripe** as its payment gateway
- Has a remote workforce (60% work from home)
- Operates in the **US and EU** (GDPR applies)

## 🎯 What This Project Covers

| Module | Deliverable | File |
|---|---|---|
| 1 | Asset Inventory | `Asset_Inventory.xlsx` (tab: Asset inventory) |
| 2 | Risk Register (Likelihood × Impact scoring) | `Asset_Inventory.xlsx` (tab: Risk Register) |
| 3 | Security Policies — Access Control, Incident Response, Acceptable Use | `module_3_Northwind_Retail_policy.docx` |
| 4 | NIST CSF 2.0 Control Gap Assessment | `Asset_Inventory.xlsx` (tab: Gap assessment) |
| 5 | Third-Party Vendor Risk Assessment (Stripe) | `Asset_Inventory.xlsx` (tab: vendor assessment) |
| 6 | Mini Audit Simulation | `Asset_Inventory.xlsx` (tab: Audit test) |
| Capstone | Executive Risk Summary | `Capstone_Executive_Risk_Summary.docx` |

A polished PDF summary combining all of the above is included: `GRC_Lab_Northwind_Retail.pdf`

## 🔍 Key Findings & Highlights

- **Top risk identified:** Unpatched software vulnerabilities (Risk Score: 20/25)
- **Critical audit finding:** Offboarding process showed a 14-day delay in revoking access for a departed contractor, violating a 24-hour policy SLA
- **Framework used:** NIST Cybersecurity Framework (CSF) 2.0 — mapped across Identify, Protect, Detect, Respond, Recover, and Govern functions
- **Vendor risk rating (Stripe):** Low — backed by PCI DSS Level 1 and SOC 2 Type II certifications
- **Recommendation delivered to leadership:** Automate IAM provisioning/offboarding (~$3,000–$6,000/yr, 2–3 weeks implementation) to close the offboarding gap

## 🧠 Skills Demonstrated

- Risk assessment and scoring methodology (Likelihood × Impact)
- Security policy drafting (Purpose, Scope, Policy Statements, Enforcement, Review Cycle)
- NIST CSF 2.0 framework mapping and control gap analysis
- Third-party / vendor risk assessment
- Internal audit test design and finding documentation
- Executive-level risk communication and business-cost framing

## 📁 Repository Structure

```
grc-foundations-lab-northwind/
├── README.md
├── Asset_Inventory.xlsx                       # Modules 1, 2, 4, 5, 6
├── module_3_Northwind_Retail_policy.docx       # Module 3 — Policies
├── Capstone_Executive_Risk_Summary.docx        # Capstone
└── GRC_Lab_Northwind_Retail.pdf                # Formatted project summary
```

## 🛠️ Tools Used

- Microsoft Excel — Risk register, control mapping, audit tracking
- Microsoft Word — Policy documents, executive summary
- Framework reference: NIST CSF 2.0

## 📝 Note

Northwind Retail is a fictional company created for learning purposes. All data, risks, and findings in this project are illustrative and used to practice real-world GRC methodology.

---

**Author:** ADIT ADHIKARI
**Connect:** https://www.linkedin.com/in/adit-adhikari-233ab9285/
