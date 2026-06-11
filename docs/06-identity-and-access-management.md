# Identity and Access Management

## Overview

Identity and Access Management (IAM) is the discipline responsible for ensuring that the right individuals and systems have access to the right resources at the right time and for the right reasons.

IAM is one of the most critical domains in cybersecurity because access to systems, applications, and data is ultimately controlled through identities.

Modern organizations rely on IAM to manage users, service accounts, applications, devices, and workloads across on-premises environments, cloud platforms, and hybrid infrastructures.

Effective IAM reduces the risk of unauthorized access, supports regulatory compliance, and serves as a foundation for Zero Trust and Least Privilege principles.

---

## Why It Matters

Most security incidents involve identities in some way.

Attackers frequently target:

- User accounts
- Administrative accounts
- Service accounts
- API credentials
- Authentication mechanisms

A compromised identity can often provide attackers with legitimate access to systems and data.

Strong IAM controls help organizations:

- Protect sensitive information
- Reduce unauthorized access
- Limit insider threats
- Improve accountability
- Strengthen security posture
- Support compliance requirements

Identity has become the primary security perimeter in modern environments.

---

## Core Concepts

### Identity

An identity represents a person, system, application, service, or device.

Examples:

- Employees
- Contractors
- Customers
- Service accounts
- Applications
- Cloud workloads

Each identity should be uniquely identifiable and managed appropriately.

### Authentication

Authentication verifies that an identity is who or what it claims to be.

Examples:

- Passwords
- Multi-Factor Authentication (MFA)
- Smart cards
- Certificates
- Biometrics
- Passwordless authentication

Authentication answers the question:

> Who are you?

### Authorization

Authorization determines what an authenticated identity is allowed to do.

Examples:

- Accessing applications
- Viewing files
- Modifying records
- Managing systems

Authorization answers the question:

> What are you allowed to do?

### Accounting and Auditing

Accounting records activities performed by authenticated identities.

Examples:

- Login events
- Administrative actions
- Access requests
- Configuration changes

Auditing helps organizations investigate incidents and demonstrate compliance.

---

## Identity Lifecycle Management

IAM extends beyond authentication and authorization.

Organizations must manage identities throughout their lifecycle.

### Provisioning

Creating identities and granting appropriate access.

Examples:

- New employee onboarding
- New service account creation
- Application registration

### Modification

Adjusting permissions as responsibilities change.

Examples:

- Promotions
- Department transfers
- Role changes

### Deprovisioning

Removing access when no longer required.

Examples:

- Employee termination
- Contractor departure
- Service retirement

Failure to properly deprovision accounts can create significant security risks.

---

## Authentication Best Practices

Strong authentication is a critical security control.

### Multi-Factor Authentication (MFA)

MFA requires two or more authentication factors.

Examples:

- Password + mobile authenticator
- Password + hardware token
- Certificate + biometric verification

MFA significantly reduces the risk of account compromise.

### Passwordless Authentication

Passwordless solutions eliminate traditional passwords.

Examples:

- FIDO2 security keys
- Biometrics
- Certificate-based authentication

Passwordless authentication helps reduce phishing risks.

### Adaptive Authentication

Authentication requirements change based on risk signals.

Examples:

- Device trust
- User location
- User behavior
- Network characteristics

Higher-risk scenarios may require additional verification.

---

## Access Control Models

Access control determines how permissions are assigned.

### Role-Based Access Control (RBAC)

Permissions are assigned according to organizational roles.

Examples:

- Help Desk
- Security Analyst
- System Administrator
- Application Developer

RBAC simplifies administration and supports Least Privilege.

### Attribute-Based Access Control (ABAC)

Access decisions are based on attributes.

Examples:

- Department
- Location
- Device status
- Classification level

ABAC provides more granular control.

### Policy-Based Access Control

Access decisions are governed by predefined security policies.

Examples:

- Conditional access rules
- Risk-based access decisions
- Compliance requirements

---

## Privileged Access Management

Privileged accounts represent some of the highest-risk identities within an organization.

Examples include:

- Domain administrators
- Cloud administrators
- Database administrators
- Security administrators

Organizations should implement additional controls for privileged accounts.

Common controls include:

- MFA
- Session monitoring
- Privileged session recording
- Credential vaulting
- Just-In-Time access
- Approval workflows

---

## Service Accounts and Non-Human Identities

Modern environments contain large numbers of non-human identities.

Examples:

- Service accounts
- APIs
- Applications
- Containers
- Cloud workloads

These identities often have elevated privileges and require proper management.

Organizations should:

- Minimize permissions
- Rotate credentials
- Monitor usage
- Eliminate unused accounts

---

## Federation and Single Sign-On

Modern IAM environments often use identity federation.

### Single Sign-On (SSO)

SSO allows users to authenticate once and access multiple applications.

Benefits include:

- Improved user experience
- Reduced password fatigue
- Centralized authentication
- Improved visibility

### Identity Federation

Federation enables trust relationships between identity providers and applications.

Common protocols include:

- SAML
- OAuth 2.0
- OpenID Connect (OIDC)

Federation simplifies identity management across organizations and platforms.

---

## Real-World Example

Consider an employee joining an organization.

### Provisioning

- Identity is created in the identity provider.
- Appropriate role assignments are applied.
- MFA is enforced.

### Daily Operations

- User accesses applications through SSO.
- Access is granted according to assigned roles.
- Activity is logged and monitored.

### Role Change

- Permissions are updated to reflect new responsibilities.
- Unnecessary access is removed.

### Departure

- Identity is disabled.
- Access is revoked.
- Associated credentials are removed.

A mature IAM program manages each stage consistently.

---

## Common Mistakes

### Shared Accounts

Shared accounts reduce accountability and complicate investigations.

Each user should have a unique identity.

### Excessive Permissions

Users often accumulate permissions over time.

Regular access reviews help prevent privilege creep.

### Weak Authentication

Reliance on passwords alone increases risk.

Organizations should implement MFA wherever possible.

### Inactive Accounts

Unused accounts frequently become attack vectors.

Dormant identities should be reviewed and removed.

### Poor Service Account Management

Service accounts often receive excessive permissions and insufficient monitoring.

These accounts should be governed like human identities.

---

## Relationship to Other Security Principles

IAM supports multiple cybersecurity principles.

### CIA Triad

Identity controls help protect confidentiality, integrity, and availability.

### Risk Management

Access decisions should align with business risk.

### Defense in Depth

IAM provides an important layer of security.

### Least Privilege

IAM enables effective privilege management.

### Zero Trust

Identity serves as the primary trust boundary within Zero Trust architectures.

---

## Benefits

Organizations with mature IAM programs can achieve:

- Reduced unauthorized access
- Improved visibility
- Better compliance
- Stronger authentication
- Improved accountability
- Reduced insider risk
- Better access governance
- Enhanced security posture

---

## Key Takeaways

- Identity is the foundation of modern cybersecurity.
- Authentication verifies identity.
- Authorization determines permitted actions.
- IAM manages identities throughout their lifecycle.
- MFA significantly improves security.
- Privileged accounts require additional protection.
- IAM is a core component of Zero Trust and Least Privilege.

---

## Security Review Checklist

When evaluating a system, consider the following questions:

### Identity Management

- Are identities uniquely assigned?
- Is the identity lifecycle managed?
- Are inactive accounts removed?

### Authentication

- Is MFA enforced?
- Are strong authentication methods used?
- Are authentication events logged?

### Authorization

- Are permissions based on business requirements?
- Is Least Privilege implemented?
- Are permissions reviewed regularly?

### Privileged Access

- Are privileged accounts identified?
- Are administrative activities monitored?
- Is Just-In-Time access available?

### Service Accounts

- Are service accounts documented?
- Are permissions restricted?
- Are credentials rotated regularly?

### Monitoring

- Are authentication events monitored?
- Are suspicious access patterns detected?
- Are audit logs retained appropriately?

---

## References

- NIST Cybersecurity Framework (CSF)
- NIST SP 800-63 Digital Identity Guidelines
- NIST SP 800-53
- ISO/IEC 27001
- CIS Controls
- OWASP Authentication Cheat Sheet
- OWASP Access Control Guidance

---

**Previous:** Zero Trust

**Next:** Security Hardening →
