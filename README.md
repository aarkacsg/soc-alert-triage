# SOC Alert Triage

This repository documents simulated Tier 1 SOC alert investigations completed in a controlled training environment.

The project focuses on structured alert triage using the following workflow:

**Alert → Hypothesis → Evidence → Verdict → Severity → Action → Justification → MITRE ATT&CK**

The investigations cover identity alerts, endpoint detections, network activity, MFA events, suspicious email reports and duplicate alert handling.

## Skills Demonstrated

- SOC alert triage
- Log and evidence analysis
- True positive vs false positive classification
- Incident severity assessment
- ServiceNow incident documentation
- Identity and authentication investigation
- Endpoint malware triage
- Network alert analysis
- Email security validation
- MITRE ATT&CK mapping
- Escalation and remediation recommendations

## Case Studies

| Case | Scenario | Verdict |
| --- | --- | --- |
| [CLD-0101](cases/CLD-0101.md) | Authentication failures during credential rotation | False Positive |
| [CLD-0102](cases/CLD-0102.md) | Credential-stealing malware on an endpoint | True Positive |
| [CLD-0103](cases/CLD-0103.md) | Authorised vulnerability scan | False Positive |
| [CLD-0104](cases/CLD-0104.md) | MFA failures followed by successful sign-in | False Positive |
| [CLD-0105](cases/CLD-0105.md) | Reported payroll email | False Positive |
| [CLD-0106](cases/CLD-0106.md) | Duplicate Defender malware alert | Duplicate |

## Triage Method

For each case, I documented:

1. What triggered the alert
2. A malicious and benign hypothesis
3. Evidence reviewed
4. Final verdict
5. Severity assessment
6. Recommended action
7. Justification
8. MITRE ATT&CK mapping where appropriate

## Environment

The cases were completed in a simulated SOC training environment using synthetic data.

Tools and concepts used included:

- ServiceNow
- Microsoft Entra ID authentication logs
- Microsoft Defender alerts
- Network / IDS alerts
- Email header analysis
- MITRE ATT&CK
- Structured SOC incident documentation

## Repository Structure

```text
soc-alert-triage/
│
├── README.md
│
└── cases/
    ├── CLD-0101.md
    ├── CLD-0102.md
    ├── CLD-0103.md
    ├── CLD-0104.md
    ├── CLD-0105.md
    └── CLD-0106.md
```

## Purpose

The purpose of this project is to demonstrate practical Tier 1 SOC investigation skills, evidence-based decision making and clear incident documentation.

All scenarios use synthetic training data. No production, customer or confidential information is included.
