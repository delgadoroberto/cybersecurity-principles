# Security Review Checklist

## Overview

Security reviews help identify risks, validate security controls, and
improve overall security posture.

This checklist provides a structured approach for evaluating systems,
applications, cloud environments, infrastructure platforms, and
technology solutions.

The objective is not to achieve perfect security.

The objective is to ensure critical security considerations are not
overlooked.

---

## Purpose

Security reviews help organizations:

- Identify risks
- Validate security controls
- Improve resilience
- Support compliance efforts
- Reduce security gaps
- Improve decision making

A consistent review process improves security outcomes.

---

## Security Review Methodology

When reviewing a system, focus on the following areas:

1. Assets
2. Access
3. Data Protection
4. Hardening
5. Vulnerability Management
6. Monitoring
7. Incident Response
8. Backup and Recovery
9. Business Continuity
10. Architecture
11. Compliance
12. Risk Management

---

## Assets

### Asset Identification

- Are critical assets identified?
- Is asset ownership defined?
- Is asset inventory maintained?
- Are dependencies understood?

### Data Identification

- What data is stored?
- What data is processed?
- Is sensitive data identified?
- Is data classified appropriately?

---

## Access Management

### Authentication

- Are users authenticated securely?
- Is multi-factor authentication implemented?
- Are default credentials removed?

### Authorization

- Is least privilege enforced?
- Are permissions reviewed regularly?
- Are privileged accounts controlled?

### Identity Lifecycle

- Are user accounts provisioned appropriately?
- Are accounts removed when no longer required?
- Are dormant accounts reviewed?

---

## Data Protection

### Encryption

- Is data encrypted at rest?
- Is data encrypted in transit?

### Key Management

- Are cryptographic keys protected?
- Is key rotation defined?

### Data Retention

- Are retention requirements documented?
- Are deletion requirements defined?

---

## Security Hardening

### Secure Configuration

- Are secure baselines defined?
- Are unnecessary services disabled?
- Are default settings reviewed?

### System Security

- Are administrative interfaces protected?
- Is remote access restricted?
- Are security updates applied?

---

## Vulnerability Management

### Vulnerability Identification

- Are vulnerability scans performed?
- Are findings reviewed regularly?

### Vulnerability Remediation

- Are vulnerabilities prioritized by risk?
- Are remediation timelines defined?
- Are exceptions documented?

---

## Logging and Monitoring

### Logging

- Are security events logged?
- Are logs retained appropriately?

### Monitoring

- Are alerts configured?
- Are suspicious activities monitored?
- Are critical assets monitored?

### Visibility

- Can security incidents be investigated effectively?
- Is monitoring coverage sufficient?

---

## Incident Response

### Preparation

- Is an incident response process documented?
- Are roles and responsibilities defined?

### Detection

- Can incidents be identified quickly?
- Are escalation procedures defined?

### Response

- Are containment procedures documented?
- Are recovery procedures established?

### Lessons Learned

- Are incidents reviewed after resolution?
- Are improvements implemented?

---

## Backup and Recovery

### Backup Strategy

- Are backups performed?
- Are backup schedules defined?
- Are critical assets included?

### Recovery

- Can backups be restored successfully?
- Has recovery testing been performed?
- Are recovery objectives defined?

---

## Business Continuity

### Availability

- Are critical services identified?
- Are availability requirements documented?

### Resilience

- Are single points of failure identified?
- Are redundancy mechanisms implemented?

### Disaster Recovery

- Are disaster recovery procedures documented?
- Are recovery exercises performed?

---

## Security Architecture

### Design Review

- Has a security architecture review been conducted?
- Are security requirements documented?

### Segmentation

- Is network segmentation implemented?
- Are trust boundaries defined?

### Security Controls

- Are security controls aligned with risks?
- Are layered defenses implemented?

---

## Compliance and Governance

### Security Requirements

- Which standards apply?
- Which regulatory requirements apply?

### Documentation

- Are policies documented?
- Are procedures documented?

### Control Validation

- Are controls periodically reviewed?
- Is compliance monitored?

---

## Risk Management

### Risk Identification

- Have risks been identified?
- Have threat scenarios been evaluated?

### Risk Treatment

- Have mitigation strategies been defined?
- Are residual risks understood?

### Risk Ownership

- Is risk ownership assigned?
- Are risks reviewed periodically?

---

## Cloud Security Review

When reviewing cloud environments, additionally consider:

### Identity

- Is MFA enforced?
- Are privileged roles controlled?

### Configuration

- Are secure baselines implemented?
- Are configurations monitored?

### Monitoring

- Are cloud audit logs enabled?
- Are alerts configured?

### Data Protection

- Is cloud data encrypted?
- Is key management defined?

### Recovery

- Are cloud backups configured?
- Are recovery procedures tested?

---

## DevSecOps Review

When reviewing DevSecOps practices, consider:

### Development

- Are security requirements defined early?
- Is secure coding encouraged?

### CI/CD

- Are security checks automated?
- Are deployments validated?

### Infrastructure as Code

- Are infrastructure changes reviewed?
- Are security controls validated automatically?

### Continuous Improvement

- Are findings incorporated into future releases?

---

## Common Review Mistakes

### Focusing Only on Compliance

Compliance should not replace risk-based security.

### Ignoring Recovery Requirements

Availability and recoverability should both be evaluated.

### Reviewing Technology Only

People and processes should also be considered.

### Missing Monitoring Requirements

Visibility is critical for detection and response.

### Not Validating Assumptions

Security assumptions should be verified regularly.

---

## Key Takeaways

- Security reviews should be systematic and repeatable.
- Security reviews should address people, processes, and technology.
- Risk management should drive security decisions.
- Backup and recovery should always be evaluated.
- Monitoring and visibility are critical.
- Security principles should guide all review activities.
- Effective reviews reduce the likelihood of overlooked security gaps.

---

## References

- NIST Cybersecurity Framework (CSF)
- NIST SP 800-53
- ISO/IEC 27001
- CIS Controls
- OWASP
- Cloud Security Alliance (CSA)

---

**Previous:** Security Frameworks

**End of Learning Path**
