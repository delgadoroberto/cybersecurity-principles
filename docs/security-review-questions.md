# Security Review Questions

## Overview

This document provides a practical collection of security review
questions that can be used when assessing systems, applications,
infrastructure, cloud environments, data platforms, and business
services.

The purpose is not to provide a compliance checklist.

The goal is to help security professionals think critically about risk,
security controls, resilience, and operational readiness.

These questions can be used during:

- Security Assessments
- Architecture Reviews
- Cloud Security Reviews
- Infrastructure Reviews
- DevSecOps Reviews
- Risk Assessments
- Internal Audits
- Security Design Discussions

---

## Assets and Business Context

Before evaluating controls, understand what is being protected.

### Questions

- What is the purpose of the system?
- Which business processes depend on it?
- What assets are being protected?
- What data is stored, processed, or transmitted?
- Which assets are most critical?
- What would be the impact of a security incident?
- What are the regulatory or contractual requirements?

### Red Flags

- Asset ownership is unclear.
- Critical assets have not been identified.
- Data classification does not exist.
- Business impact is unknown.

---

## Identity and Access Management

Identity is often the primary security boundary.

### Questions

- How are users authenticated?
- Is Multi-Factor Authentication (MFA) enforced?
- Are privileged accounts identified?
- Are administrative accounts separated from user accounts?
- Is Role-Based Access Control (RBAC) implemented?
- Are permissions reviewed periodically?
- Are dormant accounts removed?
- Are service accounts managed securely?
- Are shared accounts prohibited?
- Is access revoked when users leave the organization?

### Red Flags

- Shared administrator accounts.
- No MFA.
- Excessive permissions.
- Unknown privileged accounts.
- No access reviews.

---

## Least Privilege

Access should be limited to what is necessary.

### Questions

- Do users have only the permissions required for their roles?
- Are elevated privileges temporary when possible?
- Are privileged activities monitored?
- Is Just-In-Time (JIT) access used?
- Can permissions be justified by business need?

### Red Flags

- Permanent administrative access.
- Broad permissions granted by default.
- Excessive access accumulation over time.

---

## Network Security

Review how systems communicate and how access is controlled.

### Questions

- Is network segmentation implemented?
- Are management interfaces restricted?
- Are firewall rules documented and reviewed?
- Are unnecessary ports exposed?
- Is remote access secured?
- Is network traffic encrypted?
- Are third-party connections controlled?

### Red Flags

- Open management ports.
- Unrestricted inbound access.
- Legacy protocols in use.
- Excessive network trust relationships.

---

## Data Protection

Sensitive information should be identified and protected.

### Questions

- What sensitive data exists?
- Is data classified?
- Is encryption used at rest?
- Is encryption used in transit?
- How are encryption keys managed?
- Are backups protected?
- Is sensitive data retained only as long as necessary?

### Red Flags

- Unencrypted sensitive data.
- Poor key management.
- Unknown data locations.
- Excessive data retention.

---

## Security Hardening

Systems should follow secure configuration standards.

### Questions

- Are security baselines defined?
- Are systems hardened according to recognized standards?
- Are unnecessary services disabled?
- Are default accounts removed or secured?
- Are administrative interfaces protected?
- Are secure configurations validated periodically?

### Red Flags

- Default configurations.
- Unused services enabled.
- Weak administrative controls.
- No hardening standard.

---

## Vulnerability Management

Security weaknesses should be identified and remediated continuously.

### Questions

- Is asset inventory maintained?
- Are vulnerability scans performed regularly?
- How are vulnerabilities prioritized?
- Is exploitability considered?
- Are remediation timelines defined?
- Is remediation verified after fixes are applied?
- Are third-party dependencies monitored?

### Red Flags

- No vulnerability scanning.
- Critical vulnerabilities remain unresolved.
- No remediation process.
- No asset inventory.

---

## Logging and Monitoring

Organizations should have visibility into security events.

### Questions

- Which security events are logged?
- Are logs centralized?
- Are logs protected from tampering?
- Are alerts configured for critical events?
- Are logs retained appropriately?
- Can suspicious activity be detected?
- Are monitoring responsibilities clearly assigned?

### Red Flags

- Logging disabled.
- No centralized log collection.
- No alerting capability.
- Logs not reviewed.

---

## Incident Response

Organizations should be prepared to respond to security incidents.

### Questions

- Is there an incident response process?
- Are responsibilities defined?
- How are incidents detected?
- How are incidents escalated?
- Are incident response exercises performed?
- Is forensic evidence preserved?
- Are lessons learned documented?

### Red Flags

- No response plan.
- Undefined responsibilities.
- No testing or exercises.
- No post-incident review.

---

## Backup and Recovery

Recovery capabilities are critical for resilience.

### Questions

- Are backups performed regularly?
- Are backups encrypted?
- Are backups stored separately?
- Are backup restorations tested?
- Are recovery procedures documented?
- Are immutable backups used where appropriate?
- Can critical systems be restored within business requirements?

### Red Flags

- Backups never tested.
- Recovery procedures undocumented.
- Single backup location.
- Unknown recovery capabilities.

---

## Business Continuity and Disaster Recovery

Organizations should be prepared for disruptive events.

### Questions

- Are critical services identified?
- Are Recovery Time Objectives (RTOs) defined?
- Are Recovery Point Objectives (RPOs) defined?
- Are continuity plans documented?
- Are disaster recovery exercises performed?
- Are dependencies understood?

### Red Flags

- No recovery objectives.
- No continuity planning.
- Recovery procedures untested.

---

## Cloud Security

Cloud environments require continuous governance and monitoring.

### Questions

- Is the Shared Responsibility Model understood?
- Are cloud identities managed securely?
- Is MFA enforced?
- Are cloud resources inventoried?
- Are cloud logs collected and monitored?
- Are storage services configured securely?
- Are public exposures reviewed regularly?

### Red Flags

- Publicly exposed resources.
- Excessive permissions.
- Unmonitored cloud accounts.
- Unknown cloud assets.

---

## DevSecOps

Security should be integrated into development processes.

### Questions

- Are security controls integrated into CI/CD pipelines?
- Is source code reviewed?
- Are secrets prevented from entering repositories?
- Are dependencies scanned?
- Is Infrastructure as Code reviewed?
- Are container images scanned?
- Are security findings tracked and remediated?

### Red Flags

- Hardcoded credentials.
- No code review process.
- No security testing.
- No dependency management.

---

## Third-Party Risk

External providers may introduce risk.

### Questions

- Which third parties have access to data or systems?
- Are security requirements defined contractually?
- Are vendor assessments performed?
- Are third-party access permissions reviewed?
- Are critical suppliers identified?

### Red Flags

- Unknown vendor access.
- No supplier security reviews.
- Excessive third-party permissions.

---

## Security Architecture

Security should be incorporated into design decisions.

### Questions

- Has a threat model been performed?
- Are trust boundaries identified?
- Are security controls layered?
- Are failure scenarios considered?
- Is resilience built into the architecture?
- Are single points of failure understood?

### Red Flags

- No architectural review.
- No threat modeling.
- Security added after deployment.

---

## Universal Security Questions

Regardless of technology, every review should answer the following:

### Assets

- What are we protecting?

### Access

- Who has access and why?

### Data

- How is sensitive information protected?

### Monitoring

- Can we detect suspicious activity?

### Vulnerabilities

- How are weaknesses identified and remediated?

### Recovery

- Can services and data be restored?

### Resilience

- What happens if the system fails?

### Risk

- What is the business impact if controls fail?

---

## Security Review Mindset

Effective reviews are driven by curiosity and critical thinking.

Do not assume:

- Backups work.
- Logs are monitored.
- Permissions are appropriate.
- Security controls are effective.

Validate assumptions whenever possible.

Security reviews should focus on evidence rather than trust.

---

## Key Takeaways

- Start with business context and assets.
- Focus on risk rather than technology alone.
- Verify assumptions.
- Evaluate prevention, detection, response, and recovery.
- Consider people, processes, and technology.
- Use structured questions to identify security gaps.
- Prioritize findings based on business impact and risk.

---

**Purpose:** Practical Security Assessment and Review Reference Guide.# Security Review Questions

## Overview

This document provides a practical collection of security review
questions that can be used when assessing systems, applications,
infrastructure, cloud environments, data platforms, and business
services.

The purpose is not to provide a compliance checklist.

The goal is to help security professionals think critically about risk,
security controls, resilience, and operational readiness.

These questions can be used during:

- Security Assessments
- Architecture Reviews
- Cloud Security Reviews
- Infrastructure Reviews
- DevSecOps Reviews
- Risk Assessments
- Internal Audits
- Security Design Discussions

---

## Assets and Business Context

Before evaluating controls, understand what is being protected.

### Questions

- What is the purpose of the system?
- Which business processes depend on it?
- What assets are being protected?
- What data is stored, processed, or transmitted?
- Which assets are most critical?
- What would be the impact of a security incident?
- What are the regulatory or contractual requirements?

### Red Flags

- Asset ownership is unclear.
- Critical assets have not been identified.
- Data classification does not exist.
- Business impact is unknown.

---

## Identity and Access Management

Identity is often the primary security boundary.

### Questions

- How are users authenticated?
- Is Multi-Factor Authentication (MFA) enforced?
- Are privileged accounts identified?
- Are administrative accounts separated from user accounts?
- Is Role-Based Access Control (RBAC) implemented?
- Are permissions reviewed periodically?
- Are dormant accounts removed?
- Are service accounts managed securely?
- Are shared accounts prohibited?
- Is access revoked when users leave the organization?

### Red Flags

- Shared administrator accounts.
- No MFA.
- Excessive permissions.
- Unknown privileged accounts.
- No access reviews.

---

## Least Privilege

Access should be limited to what is necessary.

### Questions

- Do users have only the permissions required for their roles?
- Are elevated privileges temporary when possible?
- Are privileged activities monitored?
- Is Just-In-Time (JIT) access used?
- Can permissions be justified by business need?

### Red Flags

- Permanent administrative access.
- Broad permissions granted by default.
- Excessive access accumulation over time.

---

## Network Security

Review how systems communicate and how access is controlled.

### Questions

- Is network segmentation implemented?
- Are management interfaces restricted?
- Are firewall rules documented and reviewed?
- Are unnecessary ports exposed?
- Is remote access secured?
- Is network traffic encrypted?
- Are third-party connections controlled?

### Red Flags

- Open management ports.
- Unrestricted inbound access.
- Legacy protocols in use.
- Excessive network trust relationships.

---

## Data Protection

Sensitive information should be identified and protected.

### Questions

- What sensitive data exists?
- Is data classified?
- Is encryption used at rest?
- Is encryption used in transit?
- How are encryption keys managed?
- Are backups protected?
- Is sensitive data retained only as long as necessary?

### Red Flags

- Unencrypted sensitive data.
- Poor key management.
- Unknown data locations.
- Excessive data retention.

---

## Security Hardening

Systems should follow secure configuration standards.

### Questions

- Are security baselines defined?
- Are systems hardened according to recognized standards?
- Are unnecessary services disabled?
- Are default accounts removed or secured?
- Are administrative interfaces protected?
- Are secure configurations validated periodically?

### Red Flags

- Default configurations.
- Unused services enabled.
- Weak administrative controls.
- No hardening standard.

---

## Vulnerability Management

Security weaknesses should be identified and remediated continuously.

### Questions

- Is asset inventory maintained?
- Are vulnerability scans performed regularly?
- How are vulnerabilities prioritized?
- Is exploitability considered?
- Are remediation timelines defined?
- Is remediation verified after fixes are applied?
- Are third-party dependencies monitored?

### Red Flags

- No vulnerability scanning.
- Critical vulnerabilities remain unresolved.
- No remediation process.
- No asset inventory.

---

## Logging and Monitoring

Organizations should have visibility into security events.

### Questions

- Which security events are logged?
- Are logs centralized?
- Are logs protected from tampering?
- Are alerts configured for critical events?
- Are logs retained appropriately?
- Can suspicious activity be detected?
- Are monitoring responsibilities clearly assigned?

### Red Flags

- Logging disabled.
- No centralized log collection.
- No alerting capability.
- Logs not reviewed.

---

## Incident Response

Organizations should be prepared to respond to security incidents.

### Questions

- Is there an incident response process?
- Are responsibilities defined?
- How are incidents detected?
- How are incidents escalated?
- Are incident response exercises performed?
- Is forensic evidence preserved?
- Are lessons learned documented?

### Red Flags

- No response plan.
- Undefined responsibilities.
- No testing or exercises.
- No post-incident review.

---

## Backup and Recovery

Recovery capabilities are critical for resilience.

### Questions

- Are backups performed regularly?
- Are backups encrypted?
- Are backups stored separately?
- Are backup restorations tested?
- Are recovery procedures documented?
- Are immutable backups used where appropriate?
- Can critical systems be restored within business requirements?

### Red Flags

- Backups never tested.
- Recovery procedures undocumented.
- Single backup location.
- Unknown recovery capabilities.

---

## Business Continuity and Disaster Recovery

Organizations should be prepared for disruptive events.

### Questions

- Are critical services identified?
- Are Recovery Time Objectives (RTOs) defined?
- Are Recovery Point Objectives (RPOs) defined?
- Are continuity plans documented?
- Are disaster recovery exercises performed?
- Are dependencies understood?

### Red Flags

- No recovery objectives.
- No continuity planning.
- Recovery procedures untested.

---

## Cloud Security

Cloud environments require continuous governance and monitoring.

### Questions

- Is the Shared Responsibility Model understood?
- Are cloud identities managed securely?
- Is MFA enforced?
- Are cloud resources inventoried?
- Are cloud logs collected and monitored?
- Are storage services configured securely?
- Are public exposures reviewed regularly?

### Red Flags

- Publicly exposed resources.
- Excessive permissions.
- Unmonitored cloud accounts.
- Unknown cloud assets.

---

## DevSecOps

Security should be integrated into development processes.

### Questions

- Are security controls integrated into CI/CD pipelines?
- Is source code reviewed?
- Are secrets prevented from entering repositories?
- Are dependencies scanned?
- Is Infrastructure as Code reviewed?
- Are container images scanned?
- Are security findings tracked and remediated?

### Red Flags

- Hardcoded credentials.
- No code review process.
- No security testing.
- No dependency management.

---

## Third-Party Risk

External providers may introduce risk.

### Questions

- Which third parties have access to data or systems?
- Are security requirements defined contractually?
- Are vendor assessments performed?
- Are third-party access permissions reviewed?
- Are critical suppliers identified?

### Red Flags

- Unknown vendor access.
- No supplier security reviews.
- Excessive third-party permissions.

---

## Security Architecture

Security should be incorporated into design decisions.

### Questions

- Has a threat model been performed?
- Are trust boundaries identified?
- Are security controls layered?
- Are failure scenarios considered?
- Is resilience built into the architecture?
- Are single points of failure understood?

### Red Flags

- No architectural review.
- No threat modeling.
- Security added after deployment.

---

## Universal Security Questions

Regardless of technology, every review should answer the following:

### Assets

- What are we protecting?

### Access

- Who has access and why?

### Data

- How is sensitive information protected?

### Monitoring

- Can we detect suspicious activity?

### Vulnerabilities

- How are weaknesses identified and remediated?

### Recovery

- Can services and data be restored?

### Resilience

- What happens if the system fails?

### Risk

- What is the business impact if controls fail?

---

## Security Review Mindset

Effective reviews are driven by curiosity and critical thinking.

Do not assume:

- Backups work.
- Logs are monitored.
- Permissions are appropriate.
- Security controls are effective.

Validate assumptions whenever possible.

Security reviews should focus on evidence rather than trust.

---

## Key Takeaways

- Start with business context and assets.
- Focus on risk rather than technology alone.
- Verify assumptions.
- Evaluate prevention, detection, response, and recovery.
- Consider people, processes, and technology.
- Use structured questions to identify security gaps.
- Prioritize findings based on business impact and risk.

---

**Purpose:** Practical Security Assessment and Review Reference Guide.
