# gdpr-nis2-compliance-plan-healthcare
GDPR &amp; NIS2 Compliance Plan for a 500-employee Regional Hospital | Risk Analysis, Technical Measures, Incident Response &amp; Governance

# GDPR & NIS2 Compliance Plan - Regional Hospital Case Study

**Author:** Aye Khine Lwin  
**Focus:** Cybersecurity & Operational Compliance | MSc in Informática  
**Scope:** Healthcare | EHR, Billing Data, PII | 500 Employees

This is a complete compliance plan for a regional hospital handling Electronic Health Records (EHR), billing data, and Personally Identifiable Information (PII).

The hospital operates in a high-risk environment: ransomware attacks, phishing, device loss, and human error can directly impact patient care and trigger major GDPR and NIS2 penalties.

## What This Plan Covers

### Phase 1 - Risk Analysis
Risk assessment for:
- Ransomware attacks on EHR systems
- Phishing and credential theft
- Device loss / theft (laptops, tablets)
- Human error and insider threats
- Third-party vendor risks

Each risk is scored by Likelihood x Impact, with clear mitigation owners.

### Phase 2 - Policy Establishment
- Access Control Policy - Role-Based Access Control (RBAC), Least Privilege
- Data Retention & Minimization Policy (GDPR Art. 5)
- Password Policy - Minimum 12 characters + MFA
- BYOD & Remote Work Policy
- Third-Party Vendor / DPA Management

Aligned with GDPR Art. 25 (Data Protection by Design) and Art. 32 (Security of Processing).

### Phase 3 - Technical Measures
- Encryption: AES-256 for data at rest, TLS 1.2+ in transit
- Multi-Factor Authentication (MFA) for all clinical systems
- Network Segmentation, Firewalls, Intrusion Detection (IDS/IPS)
- Endpoint Detection & Response (EDR)
- Secure Backup: 3-2-1 strategy, offline backups, quarterly restore tests

Aligned with NIS2 Directive (EU) 2022/2555 Art. 21.

### Phase 4 - Monitoring & Incident Response
- 24/7 SIEM monitoring
- Incident Response Plan with clear roles: CISO, DPO, IT Team, Legal
- Breach Notification: 72-hour notification to Supervisory Authority (GDPR Art. 33)
- Notification to affected Data Subjects without undue delay (GDPR Art. 34)
- Post-incident review and lessons learned

### Phase 5 - Training & Awareness
- Quarterly cybersecurity training for all staff
- Phishing simulation for clinical and admin staff
- Specific GDPR training for data handlers

## Compliance Mapping

| Framework | Key Articles Covered |
| :--- | :--- |
| **GDPR** | Art. 5, Art. 25, Art. 32, Art. 33, Art. 34, Art. 35 (DPIA) |
| **NIS2** | Art. 21 (Cybersecurity Risk Management), Incident Reporting |

## Files
- `gdpr-nis2-compliance-plan-healthcare_Medicare.pdf` — Full Compliance Plan (Final Version)

## Disclaimer
This is an academic case study based on a fictional regional hospital scenario, created for educational and portfolio purposes. It demonstrates practical application of GDPR and NIS2 in a healthcare environment.
