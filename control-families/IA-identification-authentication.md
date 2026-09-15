# MedLink Authentication Policy Summary

## 1. Purpose

The purpose of this policy is to ensure that only authorized users and services can access MedLink systems and information.

The policy covers passwords, Multi-Factor Authentication (MFA), privileged accounts, service accounts, and account lifecycle management.

## 2. Passwords

MedLink users must:

* Use strong passwords or passphrases.
* Never share passwords with other users.
* Change compromised credentials immediately.
* Never use default passwords on systems.
* Protect passwords from unauthorized disclosure.
* Report suspected credential compromise to IT.

Repeated failed login attempts should be monitored and protected using appropriate account security controls.

## 3. Multi-Factor Authentication

MFA shall be required for high-risk users and systems.

The highest priority shall be given to administrators, remote workers, Finance, HR, and contractors.

MFA should use approved authentication methods such as authenticator applications or hardware security keys.

## 4. Privileged Accounts

Privileged accounts provide elevated permissions and shall be strictly controlled.

Requirements include:

* Privileged access must be based on business need.
* Administrative accounts must use MFA.
* Privileged activities should be logged.
* Administrators should use separate accounts for administrative tasks.
* Privileged accounts must be reviewed regularly.
* Unused privileged accounts must be disabled or removed.

## 5. Service Accounts

Service accounts are accounts used by applications or automated services.

Each service account must have:

* A documented business purpose.
* An assigned owner.
* Only the permissions required for its function.
* Protected credentials.
* Appropriate monitoring.
* Regular review.

Service accounts should not be used for normal human activities.

## 6. Account Lifecycle

MedLink shall manage accounts throughout their lifecycle:

**Join → Create → Authorize → Use → Review → Modify → Disable → Remove**

When a new employee joins, IT creates an account after appropriate authorization.

When an employee changes role, unnecessary permissions are removed and new access is assigned based on the new role.

When an employee leaves MedLink, the account shall be disabled promptly and associated access shall be revoked.

Contractor accounts should have defined expiration dates and must be disabled when the contract or business requirement ends.

## 7. Access Review

User, privileged, and service accounts shall be reviewed periodically to identify:

* Inactive accounts
* Excessive privileges
* Unauthorized accounts
* Former employees' accounts
* Unused service accounts

## 8. Responsibility

| Responsibility                      | Owner                        |
| ----------------------------------- | ---------------------------- |
| User account creation               | IT                           |
| MFA configuration                   | IT                           |
| Privileged account management       | IT/Security                  |
| Service account management          | Application/IT Administrator |
| Employee joiner/leaver notification | HR                           |
| Periodic account review             | IT                           |


# MedLink MFA Rollout Priority Matrix

## Purpose

This matrix defines the priority for deploying Multi-Factor Authentication across MedLink users and systems.

| System/User    | Priority | MFA Requirement          | Reason                                                  |
| -------------- | -------- | ------------------------ | ------------------------------------------------------- |
| Administrators | Critical | Mandatory                | Administrators have elevated system privileges          |
| Remote workers | High     | Mandatory                | Remote access increases exposure to unauthorized access |
| Finance        | High     | Mandatory                | Finance users handle sensitive financial information    |
| HR             | High     | Mandatory                | HR users handle employee and personal information       |
| General staff  | Medium   | Required where supported | Standard business access                                |
| Contractors    | High     | Mandatory                | Third-party access requires additional protection       |

## Rollout Order

### Phase 1 — Critical

Deploy MFA to all administrators first.

### Phase 2 — High

Deploy MFA to:

* Remote workers
* Finance
* HR
* Contractors

### Phase 3 — Medium

Deploy MFA to general staff and other standard users where supported.

## Success Measure

The MFA rollout will be considered successful when all Critical and High-priority accounts have MFA enabled, with exceptions formally documented and approved.


# MedLink Privileged Account Inventory

## Purpose

This inventory identifies accounts with elevated privileges within MedLink systems.

Privileged accounts must be authorized, assigned to an owner, protected with MFA, and reviewed regularly.

| Account ID | Role                      | System            | Owner             | MFA Enabled | Purpose                      | Last Review | Status |
| ---------- | ------------------------- | ----------------- | ----------------- | ----------- | ---------------------------- | ----------- | ------ |
| ADM-001    | IT Administrator          | Microsoft 365     | IT                | Yes         | Microsoft 365 administration | __________  | Active |
| ADM-002    | Network Administrator     | Firewall          | Network Admin     | Yes         | Firewall administration      | __________  | Active |
| ADM-003    | Application Administrator | Customer Portal   | Application Admin | Yes         | Portal administration        | __________  | Active |
| ADM-004    | Database Administrator    | Customer Database | IT                | Yes         | Database administration      | __________  | Active |
| ADM-005    | Security Administrator    | Security Platform | Security Team     | Yes         | Security administration      | __________  | Active |

## Review Checklist

For each privileged account, confirm:

* [ ] Account has an identified owner.
* [ ] Business purpose is documented.
* [ ] Access is still required.
* [ ] MFA is enabled.
* [ ] Permissions follow least privilege.
* [ ] Account activity is logged.
* [ ] Account is not shared.
* [ ] Last review date is recorded.
* [ ] Unnecessary access has been removed.

## Review Frequency

Privileged accounts should be reviewed at least quarterly and whenever an administrator changes role or leaves the organization.


# MedLink Service-Account Review Checklist

## Purpose

This checklist is used to review MedLink service accounts and confirm that they remain necessary, properly protected, and appropriately authorized.

## Service Account Information

**Account ID:** __________________

**Application/Service:** __________________

**Owner:** __________________

**Business Purpose:** __________________

**System Accessed:** __________________

**Review Date:** __________________

## Review Checklist

| Check | Requirement                                       | Result        |
| ----- | ------------------------------------------------- | ------------- |
| 1     | Business purpose is documented                    | ☐ Pass ☐ Fail |
| 2     | Account has an assigned owner                     | ☐ Pass ☐ Fail |
| 3     | Account is still required                         | ☐ Pass ☐ Fail |
| 4     | Access follows least privilege                    | ☐ Pass ☐ Fail |
| 5     | Credentials are securely protected                | ☐ Pass ☐ Fail |
| 6     | Account is not used for normal human login        | ☐ Pass ☐ Fail |
| 7     | Service-account activity is logged                | ☐ Pass ☐ Fail |
| 8     | Account has been reviewed recently                | ☐ Pass ☐ Fail |
| 9     | Unnecessary permissions have been removed         | ☐ Pass ☐ Fail |
| 10    | Account has an appropriate expiration/review date | ☐ Pass ☐ Fail |

## Review Decision

**☐ Continue account**

**☐ Modify permissions**

**☐ Disable account**

**☐ Remove account**

## Reviewer Comments

---

## Approval

**Reviewer:** __________________

**Date:** __________________

**IT/Security Approval:** __________________
