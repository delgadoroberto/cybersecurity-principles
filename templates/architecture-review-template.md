# Architecture Review Template

## Overview

This template provides a structured approach for reviewing the security,
resilience, scalability, and operational readiness of a system
architecture.

The goal is to identify architectural weaknesses early, validate design
decisions, and ensure security principles are incorporated into the
solution from the beginning.

This template can be used for:

- Cloud Architectures
- Enterprise Applications
- Infrastructure Platforms
- Data Platforms
- DevSecOps Pipelines
- Kubernetes Environments
- Hybrid Architectures

---

## Review Information

| Field | Value |
| ------- | ------- |
| Review Name | |
| System / Platform | |
| Version | |
| Review Date | |
| Reviewer | |
| Business Owner | |
| Technical Owner | |
| Architecture Type | |

---

## Executive Summary

Provide a high-level summary of the architecture and review outcome.

```text
Describe the architecture, major observations, risks, and recommendations.
```

---

## Business Context

### Purpose

```text
Describe the business purpose of the solution.
```

### Business Criticality

Select one:

- Critical
- High
- Medium
- Low

### Key Business Processes

- Process 1
- Process 2
- Process 3

### Regulatory Requirements

Examples:

- ISO 27001
- SOC 2
- PCI DSS
- GDPR
- HIPAA

---

## Architecture Overview

### Description

```text
Provide a high-level architecture description.
```

### Architecture Diagram

Reference architecture documentation or diagrams.

```text
Insert diagram link or reference.
```

### Components

| Component | Purpose |
| ------- | ------- |
| | |
| | |
| | |

---

## Data Flow Analysis

### Data Sources

| Source | Description |
| ------- | ------- |
| | |
| | |

### Data Destinations

| Destination | Description |
| ------- | ------- |
| | |
| | |

### Data Flow Description

```text
Describe how data moves through the environment.
```

### Sensitive Data

Identify sensitive information processed or stored.

Examples:

- Personal Data
- Financial Data
- Authentication Data
- Intellectual Property
- Operational Data

---

## Trust Boundaries

Identify trust boundaries within the architecture.

| Trust Boundary | Description |
| ------- | ------- |
| | |
| | |

### Review Questions

- Where does trust begin and end?
- Which components communicate across trust boundaries?
- Are controls applied consistently?

---

## Identity and Access Management

### Review Questions

- How are users authenticated?
- Is MFA enforced?
- Is RBAC implemented?
- Are privileged accounts managed?
- Are service accounts secured?
- Is least privilege enforced?

### Observations

```text
Document findings.
```

---

## Network Architecture

### Review Questions

- Is network segmentation implemented?
- Are security zones defined?
- Are management interfaces restricted?
- Is east-west traffic controlled?
- Is remote access protected?

### Observations

```text
Document findings.
```

---

## Data Protection

### Review Questions

- Is sensitive data identified?
- Is encryption used at rest?
- Is encryption used in transit?
- Are cryptographic keys protected?
- Are backups protected?

### Observations

```text
Document findings.
```

---

## Security Monitoring

### Review Questions

- Are logs collected?
- Are logs centralized?
- Are security alerts configured?
- Is monitoring coverage sufficient?
- Can incidents be detected?

### Observations

```text
Document findings.
```

---

## Vulnerability Management

### Review Questions

- Are assets inventoried?
- Are vulnerability scans performed?
- Are remediation processes defined?
- Is patch management implemented?

### Observations

```text
Document findings.
```

---

## High Availability

### Review Questions

- Are redundant components implemented?
- Are single points of failure identified?
- Is failover available?
- Are critical services highly available?

### Observations

```text
Document findings.
```

---

## Backup and Recovery

### Review Questions

- Are backups performed?
- Are backups tested?
- Are recovery procedures documented?
- Are RTO and RPO defined?

### Observations

```text
Document findings.
```

---

## Disaster Recovery

### Review Questions

- Is a disaster recovery plan available?
- Has recovery been tested?
- Are recovery dependencies understood?
- Are alternate recovery locations available?

### Observations

```text
Document findings.
```

---

## Cloud Security (If Applicable)

### Review Questions

- Is the Shared Responsibility Model understood?
- Are cloud identities protected?
- Are public resources reviewed?
- Is cloud logging enabled?
- Are cloud configurations monitored?

### Observations

```text
Document findings.
```

---

## DevSecOps (If Applicable)

### Review Questions

- Are CI/CD pipelines secured?
- Are secrets managed securely?
- Is Infrastructure as Code reviewed?
- Are dependencies scanned?
- Are container images scanned?

### Observations

```text
Document findings.
```

---

## Third-Party Dependencies

### Review Questions

- Which external services are required?
- What happens if a provider becomes unavailable?
- Are third-party risks assessed?
- Are contracts reviewed for security requirements?

### Observations

```text
Document findings.
```

---

## Threat Modeling Review

### Review Questions

- Has threat modeling been performed?
- Are attack paths understood?
- Are trust boundaries identified?
- Are mitigations documented?

### Observations

```text
Document findings.
```

---

## Security Principles Assessment

| Principle | Status | Comments |
| ---------- | ---------- | ---------- |
| Confidentiality | | |
| Integrity | | |
| Availability | | |
| Defense in Depth | | |
| Least Privilege | | |
| Zero Trust | | |
| Monitoring | | |
| Resilience | | |

Status:

- Implemented
- Partially Implemented
- Not Implemented
- Not Applicable

---

## Architecture Risks

| Risk ID | Description | Severity |
| ---------- | ---------- | ---------- |
| AR-001 | | |
| AR-002 | | |
| AR-003 | | |

Severity Levels:

- Critical
- High
- Medium
- Low

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

## Overall Assessment

Select one:

- Strong
- Satisfactory
- Needs Improvement
- High Risk

### Summary

```text
Provide final assessment.
```

---

## Review Sign-Off

| Role | Name | Date |
| ---------- | ---------- | ---------- |
| Reviewer | | |
| Technical Owner | | |
| Business Owner | | |

---

## Supporting Documentation

Reference related documentation.

Examples:

- Architecture Diagrams
- Threat Models
- Security Reviews
- Risk Assessments
- Security Standards
- Operational Procedures

---

## Notes

```text
Additional comments and observations.
```
