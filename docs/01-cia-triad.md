# CIA Triad

## Overview

The CIA Triad is one of the most fundamental models in cybersecurity and information security.

It provides a simple but powerful framework for understanding security objectives and evaluating security controls. Nearly every security requirement, control, standard, or framework can be mapped to one or more components of the CIA Triad.

The model consists of three core principles:

- Confidentiality
- Integrity
- Availability

Together, these principles help organizations protect information, systems, and services from unauthorized access, modification, and disruption.

---

## Why It Matters

Security technologies, platforms, and threats evolve continuously.

The principles of the CIA Triad remain relevant regardless of the environment being protected.

Whether securing:

- A Linux server
- A cloud environment
- A web application
- A database
- A Kubernetes cluster
- A data platform

Security professionals should always evaluate how confidentiality, integrity, and availability are maintained.

The CIA Triad serves as a foundational decision-making model for security architecture, risk assessments, audits, security reviews, and compliance initiatives.

---

## Confidentiality

### Definition

Confidentiality ensures that information is accessible only to authorized individuals, systems, or processes.

The objective is to prevent unauthorized disclosure of sensitive information.

### Examples

- Protecting customer records from unauthorized access.
- Restricting administrative access to privileged users.
- Preventing attackers from viewing sensitive data.
- Limiting access to confidential business information.

### Common Threats

- Unauthorized access
- Credential theft
- Insider threats
- Data leaks
- Misconfigured permissions
- Social engineering attacks

### Common Security Controls

- Authentication
- Multi-Factor Authentication (MFA)
- Authorization
- Role-Based Access Control (RBAC)
- Encryption
- Data Classification
- Data Loss Prevention (DLP)
- Privileged Access Management (PAM)

### Security Review Questions

- Who can access the data?
- Is access restricted to authorized users?
- Are privileged accounts properly managed?
- Is sensitive data encrypted?
- Are permissions reviewed regularly?

---

## Integrity

### Definition

Integrity ensures that information remains accurate, complete, and trustworthy throughout its lifecycle.

The objective is to prevent unauthorized or unintended modification of data.

### Examples

- Preventing unauthorized changes to financial records.
- Ensuring software packages have not been tampered with.
- Verifying the authenticity of a digital document.
- Maintaining accurate audit logs.

### Common Threats

- Unauthorized modifications
- Malware
- Data corruption
- Human error
- Supply chain attacks
- Misconfigured systems

### Common Security Controls

- Hashing
- Digital Signatures
- Change Management
- File Integrity Monitoring
- Version Control
- Access Controls
- Audit Trails
- Configuration Management

### Security Review Questions

- How is data integrity verified?
- Can unauthorized changes be detected?
- Are changes tracked and approved?
- Are audit logs protected from tampering?
- Is configuration drift monitored?

---

## Availability

### Definition

Availability ensures that systems, services, and information remain accessible when needed.

The objective is to minimize downtime and maintain operational continuity.

### Examples

- Keeping business applications online.
- Recovering systems after hardware failure.
- Restoring data after a ransomware attack.
- Maintaining service availability during peak demand.

### Common Threats

- Hardware failures
- Software failures
- Ransomware
- Denial-of-Service (DoS) attacks
- Natural disasters
- Power outages
- Human error

### Common Security Controls

- Backup and Recovery
- Disaster Recovery Planning
- Business Continuity Planning
- Redundancy
- High Availability Architectures
- Monitoring and Alerting
- Capacity Management
- Fault Tolerance

### Security Review Questions

- Are backups performed regularly?
- Have backups been tested successfully?
- What are the Recovery Time Objective (RTO) and Recovery Point Objective (RPO)?
- Is there a disaster recovery plan?
- Are critical services redundant?

---

## Balancing the CIA Triad

Security decisions often require balancing confidentiality, integrity, and availability.

Improving one area may affect another.

Examples:

| Decision | Benefit | Potential Trade-Off |
|-----------|----------|---------------------|
| Strong access controls | Improves confidentiality | May reduce usability |
| Strict change controls | Improves integrity | May slow deployments |
| High availability architectures | Improves availability | May increase complexity and cost |

Security professionals must understand business requirements and risk tolerance when making security decisions.

The goal is not to maximize a single principle but to achieve an appropriate balance among all three.

---

## Real-World Example

Consider a data analytics platform containing sensitive business information.

### Confidentiality

- Access is restricted using RBAC.
- MFA is required for administrative users.
- Data is encrypted at rest and in transit.

### Integrity

- Configuration changes are reviewed and approved.
- Audit logs record administrative activity.
- Data validation mechanisms detect unauthorized changes.

### Availability

- Backups are performed regularly.
- Recovery procedures are documented and tested.
- Critical services are deployed with redundancy.

A weakness in any of these areas can significantly increase organizational risk.

---

## Common Mistakes

### Focusing Only on Confidentiality

Many security initiatives focus heavily on access control and encryption while neglecting resilience and recovery.

### Ignoring Backup Validation

Backups that have never been tested may not be recoverable when needed.

### Weak Change Management

Unauthorized or poorly managed changes can compromise system integrity.

### Lack of Monitoring

Without monitoring, organizations may be unable to detect attacks or failures affecting confidentiality, integrity, or availability.

---

## Key Takeaways

- The CIA Triad is a foundational cybersecurity model.
- Confidentiality protects information from unauthorized disclosure.
- Integrity protects information from unauthorized modification.
- Availability ensures information and services remain accessible.
- Most security controls support one or more components of the CIA Triad.
- Effective security requires balancing all three principles.
- The CIA Triad can be applied to any technology, platform, or environment.

---

## Security Review Checklist

Use the following questions when evaluating a system:

### Confidentiality

- Who can access the system?
- Are permissions appropriately assigned?
- Is sensitive data encrypted?

### Integrity

- How are changes controlled?
- How is integrity verified?
- Are audit trails maintained?

### Availability

- Are backups performed and tested?
- Is monitoring implemented?
- Is there a documented recovery process?

---

## References

- NIST Cybersecurity Framework (CSF)
- NIST SP 800 Series
- ISO/IEC 27001
- CIS Controls
- OWASP Security Principles

---

**Next:** Risk Management →
