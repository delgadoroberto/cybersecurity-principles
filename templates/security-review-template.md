# Security Review Template

## Review Information

| Field | Value |
| ------- | ------- |
| Review Name | |
| System / Application | |
| Review Date | |
| Reviewer | |
| Business Owner | |
| Technical Owner | |
| Environment | |
| Review Type | |
| Version | |

---

## Executive Summary

Provide a high-level overview of the system, review scope, major
findings, and overall security posture.

### Example

- Security posture is generally mature.
- Identity controls are implemented.
- Backup testing requires improvement.
- Several medium-risk findings were identified.

---

## Scope

Define the systems, services, and components included in the review.

### In Scope

- Infrastructure
- Applications
- Cloud Resources
- Data Platforms
- CI/CD Pipelines
- Identity Services

### Out of Scope

- Third-Party Services
- Legacy Systems
- End User Devices

---

## Business Context

### Purpose

Describe the purpose of the system.

### Business Criticality

Select one:

- Critical
- High
- Medium
- Low

### Key Business Functions

- Function 1
- Function 2
- Function 3

### Regulatory Requirements

Examples:

- ISO 27001
- SOC 2
- PCI DSS
- HIPAA
- GDPR

---

## Asset Identification

### Assets Reviewed

| Asset | Description | Criticality |
| ------- | ------- | ------- |
| | | |
| | | |
| | | |

### Sensitive Data

Identify data processed, stored, or transmitted.

Examples:

- Customer Data
- Financial Data
- Authentication Data
- Intellectual Property
- Operational Data

---

## Security Review Areas

---

# Identity and Access Management

## Questions

- Is MFA enforced?
- Is RBAC implemented?
- Are privileged accounts identified?
- Are access reviews performed?
- Are dormant accounts removed?

## Observations

```text
Document observations here.
```

## Findings

| Severity | Finding |
| ------- | ------- |
| | |

---

# Least Privilege

## Questions

- Do users have only required permissions?
- Are administrative privileges restricted?
- Is temporary privileged access available?

## Observations

```text
Document observations here.
```

## Findings

| Severity | Finding |
| ------- | ------- |
| | |

---

# Network Security

## Questions

- Is network segmentation implemented?
- Are management interfaces restricted?
- Are firewall rules reviewed?
- Is remote access secured?

## Observations

```text
Document observations here.
```

## Findings

| Severity | Finding |
| ------- | ------- |
| | |

---

# Data Protection

## Questions

- Is data classified?
- Is encryption used at rest?
- Is encryption used in transit?
- Are encryption keys protected?

## Observations

```text
Document observations here.
```

## Findings

| Severity | Finding |
| ------- | ------- |
| | |

---

# Security Hardening

## Questions

- Are secure baselines implemented?
- Are unnecessary services disabled?
- Are default accounts secured?
- Are configurations periodically reviewed?

## Observations

```text
Document observations here.
```

## Findings

| Severity | Finding |
| ------- | ------- |
| | |

---

# Vulnerability Management

## Questions

- Are vulnerability scans performed?
- Is asset inventory maintained?
- Are vulnerabilities prioritized?
- Is remediation verified?

## Observations

```text
Document observations here.
```

## Findings

| Severity | Finding |
| ------- | ------- |
| | |

---

# Logging and Monitoring

## Questions

- Are logs collected?
- Are logs centralized?
- Are alerts configured?
- Are logs protected from tampering?

## Observations

```text
Document observations here.
```

## Findings

| Severity | Finding |
| ------- | ------- |
| | |

---

# Incident Response

## Questions

- Is there an incident response plan?
- Are roles defined?
- Are exercises conducted?
- Are lessons learned documented?

## Observations

```text
Document observations here.
```

## Findings

| Severity | Finding |
| ------- | ------- |
| | |

---

# Backup and Recovery

## Questions

- Are backups performed?
- Are backups tested?
- Are recovery procedures documented?
- Are recovery objectives defined?

## Observations

```text
Document observations here.
```

## Findings

| Severity | Finding |
| ------- | ------- |
| | |

---

# Business Continuity

## Questions

- Are continuity plans documented?
- Are recovery exercises performed?
- Are critical services identified?

## Observations

```text
Document observations here.
```

## Findings

| Severity | Finding |
| ------- | ------- |
| | |

---

# Cloud Security

## Questions

- Is the Shared Responsibility Model understood?
- Is MFA enforced?
- Are cloud logs monitored?
- Are public exposures reviewed?

## Observations

```text
Document observations here.
```

## Findings

| Severity | Finding |
| ------- | ------- |
| | |

---

# DevSecOps

## Questions

- Are secrets scanning tools used?
- Are dependencies scanned?
- Is Infrastructure as Code reviewed?
- Are container images scanned?

## Observations

```text
Document observations here.
```

## Findings

| Severity | Finding |
| ------- | ------- |
| | |

---

# Security Architecture

## Questions

- Has threat modeling been performed?
- Are trust boundaries identified?
- Are security controls layered?
- Are single points of failure understood?

## Observations

```text
Document observations here.
```

## Findings

| Severity | Finding |
| ------- | ------- |
| | |

---

## Risk Summary

### Findings by Severity

| Severity | Count |
| ------- | ------- |
| Critical | |
| High | |
| Medium | |
| Low | |
| Informational | |

---

## Detailed Findings

### Finding ID

**Title**

**Severity**

- Critical
- High
- Medium
- Low
- Informational

**Description**

```text
Describe the issue.
```

**Risk**

```text
Describe potential impact.
```

**Recommendation**

```text
Describe recommended actions.
```

**Owner**

```text
Responsible team.
```

**Target Date**

```text
Expected remediation date.
```

---

## Overall Assessment

Select one:

- Strong
- Satisfactory
- Needs Improvement
- High Risk

### Summary

```text
Provide overall assessment.
```

---

## Recommendations

### Immediate Actions

- Action 1
- Action 2
- Action 3

### Short-Term Improvements

- Improvement 1
- Improvement 2
- Improvement 3

### Long-Term Improvements

- Improvement 1
- Improvement 2
- Improvement 3

---

## Review Sign-Off

| Role | Name | Date |
| ------- | ------- | ------- |
| Reviewer | | |
| Technical Owner | | |
| Business Owner | | |

---

## Notes

```text
Additional comments and supporting information.
```
