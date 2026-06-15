# Threat Model Template

## Overview

This template provides a structured approach for identifying threats,
understanding risks, evaluating attack paths, and defining security
controls for systems, applications, cloud environments, infrastructure,
and business services.

The objective is to proactively identify security risks during design,
implementation, and operational reviews.

Threat modeling should be performed as early as possible and updated
when significant changes occur.

---

## Threat Model Information

| Field | Value |
| ------- | ------- |
| Project Name | |
| System / Application | |
| Version | |
| Assessment Date | |
| Reviewer | |
| Business Owner | |
| Technical Owner | |

---

## System Description

### Purpose

Describe the purpose of the system.

```text
Describe the system and business objectives.
```

### Scope

Describe what is included in the threat model.

```text
Define the assessment scope.
```

### Assumptions

Document assumptions made during the assessment.

```text
List assumptions.
```

### Constraints

Document known limitations.

```text
List constraints.
```

---

## Architecture Overview

### Components

List the primary components.

| Component | Description |
| ------- | ------- |
| | |
| | |
| | |

### External Dependencies

| Dependency | Purpose |
| ------- | ------- |
| | |
| | |
| | |

### Trust Boundaries

Identify trust boundaries within the architecture.

| Trust Boundary | Description |
| ------- | ------- |
| | |
| | |

---

## Asset Identification

Identify assets that require protection.

### Assets

| Asset | Description | Criticality |
| ------- | ------- | ------- |
| | | |
| | | |
| | | |

### Sensitive Data

Identify sensitive information handled by the system.

Examples:

- Customer Data
- Authentication Data
- Financial Data
- Personal Information
- Intellectual Property
- Operational Data

---

## Entry Points

Identify how users, systems, or attackers may interact with the
environment.

### Entry Points

| Entry Point | Description |
| ------- | ------- |
| | |
| | |
| | |

Examples:

- Web Applications
- APIs
- VPN Connections
- Administrative Interfaces
- CI/CD Pipelines
- Cloud Management Consoles

---

## Threat Actors

Identify potential threat actors.

### Internal Threat Actors

- Employees
- Contractors
- Administrators
- Developers

### External Threat Actors

- Cybercriminals
- Nation-State Actors
- Competitors
- Hacktivists
- Malicious Third Parties

### Threat Actor Analysis

| Threat Actor | Motivation | Capability |
| ------- | ------- | ------- |
| | | |
| | | |

---

## Attack Surface Analysis

Identify exposed components and potential attack vectors.

### Public Exposure

| Component | Exposure |
| ------- | ------- |
| | |
| | |

### Administrative Exposure

| Component | Exposure |
| ------- | ------- |
| | |
| | |

### Third-Party Exposure

| Component | Exposure |
| ------- | ------- |
| | |
| | |

---

## Threat Identification

### Threat Register

| ID | Threat | Asset | Impact |
| ------- | ------- | ------- | ------- |
| T-001 | | | |
| T-002 | | | |
| T-003 | | | |

---

## STRIDE Analysis (Optional)

Use STRIDE to identify threats systematically.

| Category | Description | Applicable |
| ------- | ------- | ------- |
| Spoofing | Identity impersonation | |
| Tampering | Unauthorized modification | |
| Repudiation | Denial of actions | |
| Information Disclosure | Unauthorized data access | |
| Denial of Service | Service disruption | |
| Elevation of Privilege | Unauthorized privilege escalation | |

---

## Threat Analysis

### Threat ID

**Threat Name**

```text
Describe the threat.
```

### Attack Scenario

```text
Describe how the attack could occur.
```

### Affected Assets

```text
List affected assets.
```

### Existing Controls

```text
Describe current protections.
```

### Potential Impact

```text
Describe business and technical impact.
```

### Likelihood

Select one:

- Low
- Medium
- High

### Impact

Select one:

- Low
- Medium
- High

### Risk Rating

Select one:

- Low
- Medium
- High
- Critical

---

## Security Controls Assessment

### Preventive Controls

Examples:

- MFA
- Network Segmentation
- Encryption
- Secure Configuration
- Least Privilege

| Control | Implemented |
| ------- | ------- |
| | |
| | |

---

### Detective Controls

Examples:

- Logging
- Monitoring
- Alerting
- SIEM

| Control | Implemented |
| ------- | ------- |
| | |
| | |

---

### Corrective Controls

Examples:

- Incident Response
- Backup and Recovery
- Disaster Recovery

| Control | Implemented |
| ------- | ------- |
| | |
| | |

---

## Risk Assessment

### Risk Matrix

| Likelihood | Impact | Risk Level |
| ------- | ------- | ------- |
| Low | Low | Low |
| Low | Medium | Low |
| Medium | Medium | Medium |
| High | Medium | High |
| High | High | Critical |

---

## Risk Register

| Risk ID | Description | Risk Level | Owner |
| ------- | ------- | ------- | ------- |
| R-001 | | | |
| R-002 | | | |
| R-003 | | | |

---

## Recommended Mitigations

| Threat | Recommendation | Priority |
| ------- | ------- | ------- |
| | | |
| | | |
| | | |

### Priority Levels

- Critical
- High
- Medium
- Low

---

## Residual Risk

Describe remaining risks after mitigation.

```text
Document residual risks.
```

---

## Security Review Questions

### Identity

- Is MFA enforced?
- Are privileged accounts protected?
- Is least privilege implemented?

### Data Protection

- Is sensitive data encrypted?
- Are encryption keys protected?

### Monitoring

- Can suspicious activity be detected?
- Are alerts configured?

### Recovery

- Can data be restored?
- Are backups tested?

### Architecture

- Are trust boundaries identified?
- Are security controls layered?

---

## Findings Summary

| Severity | Count |
| ------- | ------- |
| Critical | |
| High | |
| Medium | |
| Low | |

---

## Conclusions

```text
Summarize the results of the threat model.
```

---

## Approval

| Role | Name | Date |
| ------- | ------- | ------- |
| Reviewer | | |
| Technical Owner | | |
| Business Owner | | |

---

## Supporting Documentation

Reference related documents.

Examples:

- Architecture Diagrams
- Security Reviews
- Risk Assessments
- Security Standards
- Security Requirements
