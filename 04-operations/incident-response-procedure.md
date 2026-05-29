# Incident Response Procedure

**Organisation:** EugTech Solutions Ltd
**ISO 27001 Reference:** Annex A 5.24

## Incident Classification

| Severity      | Definition & Response Time                                                                                                                                   |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| P1 – Critical | Active data breach, ransomware, system compromise. Response within 1 hour. ISM + CEO notified immediately. ICO notification may be required within 72 hours. |
| P2 – High     | Suspected breach, significant service disruption, malware detected. Response within 4 hours. ISM notified within 30 minutes.                                 |
| P3 – Medium   | Policy violation, phishing email opened, unauthorised access attempt. Response within 24 hours. ISM notified same business day.                              |
| P4 – Low      | Minor policy breach, lost company property with no sensitive data, suspicious email reported. Response within 72 hours. Logged and reviewed.                 |

## Incident Response Phases

### Phase 1 – IDENTIFY

Any staff member who suspects a security incident must report immediately via:

* Email to [security@eugtech.co.uk](mailto:security@eugtech.co.uk)
* Direct call to the Information Security Manager (ISM)

Sentinel and Defender for Cloud alerts are auto-triaged by the ISM.

Initial classification assigned within 30 minutes.

### Phase 2 – CONTAIN

Immediate actions to limit damage:

* Disable compromised accounts (Entra ID)
* Isolate affected VMs (NSG changes)
* Revoke and rotate affected credentials (Key Vault)
* Preserve forensic evidence (Sentinel logs, CloudTrail)

Do not wipe systems before evidence is captured.

### Phase 3 – ERADICATE

Remove the root cause:

* Patch vulnerabilities
* Remove malware
* Close attack vectors
* Reset compromised credentials

Confirm eradication through Sentinel and Defender for Cloud monitoring before moving to recovery.

### Phase 4 – RECOVER

Restore systems from clean backups (Azure Backup).

Re-enable services gradually with enhanced monitoring.

Notify affected clients if required.

Comply with ICO 72-hour notification requirement for personal data breaches.

### Phase 5 – LEARN

Post-incident review within 5 business days.

* Root cause analysis documented
* Lessons learned shared with all staff
* Risk register updated if new risk identified
* Controls updated in SoA if gaps found
* Management review agenda updated
