# Risk Register

**Organisation:** EugTech Solutions Ltd
**ISO 27001 Clause:** 6.1.2 Risk Assessment & Risk Register

| Risk ID | Asset                  | Threat                                              | Likelihood (1-5) | Impact (1-5) | Rating   | Residual Risk | Status      |
| ------- | ---------------------- | --------------------------------------------------- | ---------------- | ------------ | -------- | ------------- | ----------- |
| R-001   | Client data in Azure   | Unauthorised access via misconfigured IAM           | 3                | 5            | HIGH: 15 | MED: 9        | IN PROGRESS |
| R-002   | Staff laptops          | Device theft or loss exposing client data           | 3                | 4            | HIGH: 12 | LOW: 4        | IMPLEMENTED |
| R-003   | Source code repository | Hardcoded credentials committed to GitHub           | 2                | 5            | HIGH: 10 | MED: 6        | IN PROGRESS |
| R-004   | Supplier access        | Third-party vendor with excessive access to systems | 2                | 4            | MED: 8   | LOW: 4        | IMPLEMENTED |
| R-005   | Staff                  | Phishing attack leading to credential compromise    | 4                | 4            | HIGH: 16 | MED: 8        | IN PROGRESS |
| R-006   | Cloud infrastructure   | Ransomware encrypting client data backups           | 2                | 5            | HIGH: 10 | LOW: 5        | IMPLEMENTED |
| R-007   | Network                | Man-in-the-middle on remote worker connections      | 2                | 3            | MED: 6   | LOW: 3        | IMPLEMENTED |
| R-008   | Microsoft 365          | Business email compromise (BEC)                     | 3                | 4            | HIGH: 12 | MED: 6        | IMPLEMENTED |
| R-009   | Client data            | Data retention holding data beyond agreed period    | 2                | 4            | MED: 8   | LOW: 4        | IN PROGRESS |
| R-010   | Key personnel          | Knowledge loss if key staff depart suddenly         | 3                | 3            | MED: 9   | MED: 6        | OPEN        |

## Risk Rating Criteria

| Score | Classification |
| ----- | -------------- |
| 1-8   | Low Risk       |
| 9-15  | Medium Risk    |
| 16-25 | High Risk      |

## Treatment Guidance

* **Low Risk (1-8):** Accept or monitor.
* **Medium Risk (9-15):** Treat with controls and review quarterly.
* **High Risk (16-25):** Immediate treatment required and escalate to management.
