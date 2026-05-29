# Asset Inventory

**Organisation:** EugTech Solutions Ltd
**ISO 27001 Reference:** Annex A 5.9

## Information Asset Register

| Asset ID | Asset Name                        | Asset Type | Classification | Owner            | Location               | Controls Applied                                                   |
| -------- | --------------------------------- | ---------- | -------------- | ---------------- | ---------------------- | ------------------------------------------------------------------ |
| A-001    | Client personal data (Azure Blob) | Data       | Restricted     | Head of Delivery | Azure UK South         | Encryption at rest, RBAC, audit logging, Key Vault                 |
| A-002    | Source code repositories (GitHub) | Software   | Confidential   | Dev Lead         | GitHub Enterprise      | Branch protection, secret scanning, 2FA mandatory                  |
| A-003    | Microsoft 365 tenant              | System     | Confidential   | IT Manager       | Microsoft Cloud        | MFA, CA policies, DLP, Defender for Office 365                     |
| A-004    | Azure subscription                | System     | Restricted     | ISM              | Azure UK South         | RBAC, Defender for Cloud, Sentinel, activity logging               |
| A-005    | Staff laptops (50 devices)        | Hardware   | Confidential   | IT Manager       | Staff locations        | BitLocker, MDM, antivirus, auto-lock, VPN                          |
| A-006    | Client contracts                  | Data       | Restricted     | Legal Counsel    | SharePoint (encrypted) | Access restricted to Partners + Legal, audit log                   |
| A-007    | Financial records                 | Data       | Restricted     | Finance Director | SharePoint + local NAS | RBAC, backup, physical access control                              |
| A-008    | Staff personal data (HR)          | Data       | Restricted     | HR Manager       | HR System (cloud)      | GDPR controls, access restricted to HR, retention schedule         |
| A-009    | AWS accounts (client-managed)     | System     | Confidential   | Cloud Architect  | AWS eu-west-2          | IAM, CloudTrail, GuardDuty, SCPs                                   |
| A-010    | VPN infrastructure                | System     | Confidential   | IT Manager       | Azure + on-premise     | Certificate-based authentication, log monitoring, patch management |
