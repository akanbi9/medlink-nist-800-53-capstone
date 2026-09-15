# PS — Personnel Screening and Onboarding Checklist

## Purpose

This checklist helps MedLink securely screen and onboard new personnel while ensuring that employees receive only the access required for their job responsibilities.

## A. Pre-Employment Screening

| Check | Completed | Notes |
|---|---|---|
| Position and responsibilities defined | [ ] | |
| Security responsibilities identified | [ ] | |
| Appropriate background/suitability check completed | [ ] | |
| References verified where required | [ ] | |
| Screening results reviewed by authorized personnel | [ ] | |
| Confidentiality requirements identified | [ ] | |

## B. Onboarding

| Task | Completed | Owner |
|---|---|---|
| Employee identity verified | [ ] | HR |
| Employment documentation completed | [ ] | HR |
| Security policies provided | [ ] | HR/Security |
| Acceptable-use requirements explained | [ ] | Security |
| Security awareness training completed | [ ] | Security |
| User account created | [ ] | IT |
| MFA enabled | [ ] | IT |
| Appropriate system permissions assigned | [ ] | IT/System Owner |
| Company device assigned | [ ] | IT |
| Device security baseline applied | [ ] | IT |
| Password/authentication requirements explained | [ ] | IT |
| Data-handling requirements explained | [ ] | Security |
| Employee acknowledges security responsibilities | [ ] | HR |
| Emergency/security incident reporting process explained | [ ] | Security |

## C. Access Approval

Access should be based on the employee's job responsibilities and the principle of least privilege.

| System | Access Required | Approved By | Status |
|---|---|---|---|
| Microsoft 365 | Yes/No | System Owner | |
| Customer Portal | Yes/No | System Owner | |
| Customer Database | Yes/No | System Owner | |
| File Server | Yes/No | System Owner | |
| Other | | | |

## Completion

Employee Name/ID: __________________

Department: __________________

Start Date: __________________

Onboarding Completed By: __________________

Date: __________________

---

# PS — Offboarding and Access-Removal Checklist

## Purpose

This checklist ensures that access, equipment, and organizational information are properly protected when personnel leave MedLink.

## A. Notification

| Task | Completed | Owner |
|---|---|---|
| HR confirms termination/separation | [ ] | HR |
| IT notified | [ ] | HR |
| Security Lead notified | [ ] | HR |
| System Owners notified where necessary | [ ] | HR/IT |
| Effective termination date/time confirmed | [ ] | HR |

## B. Access Removal

| Access | Completed |
|---|---|
| Disable Microsoft 365 account | [ ] |
| Disable VPN access | [ ] |
| Disable Customer Portal access | [ ] |
| Remove database access | [ ] |
| Remove file-server access | [ ] |
| Revoke active sessions | [ ] |
| Disable MFA/authentication tokens | [ ] |
| Remove privileged access | [ ] |
| Disable remote-access accounts | [ ] |
| Remove group memberships | [ ] |
| Review shared-account access | [ ] |

## C. Company Assets

| Asset | Returned | Condition |
|---|---|---|
| Laptop | [ ] | |
| Mobile device | [ ] | |
| ID card | [ ] | |
| USB/removable media | [ ] | |
| Other equipment | [ ] | |

## D. Final Security Review

- [ ] Access has been removed from required systems.
- [ ] Privileged permissions have been removed.
- [ ] Company devices have been recovered.
- [ ] Active sessions have been revoked.
- [ ] Company information has been protected.
- [ ] Offboarding actions have been documented.
- [ ] System owners confirmed access removal.

## Completion

Employee/Personnel ID: __________________

Termination Date: __________________

Access Removal Completed By: __________________

Date/Time Completed: __________________

Security Review Completed By: __________________


# PS — Contractor Security Requirements

## Purpose

These requirements define the minimum security expectations for contractors who access MedLink systems, facilities, or information.

## Contractor Requirements

### 1. Authorization

- Contractor must have an approved business purpose.
- Contractor access must be approved by the appropriate manager/system owner.
- Access must be limited to required systems.
- Contractor access must have a defined start and end date.

### 2. Security Responsibilities

Contractors must:

- Follow MedLink security policies.
- Protect company information.
- Keep authentication credentials confidential.
- Use MFA where required.
- Report suspected security incidents.
- Avoid installing unauthorized software.
- Protect company devices and information.
- Follow acceptable-use requirements.

### 3. Access Control

Contractor access should follow least privilege.

| Requirement | Status |
|---|---|
| Business need identified | Required |
| Manager approval | Required |
| System owner approval | Required where applicable |
| MFA | Required where supported |
| Defined access period | Required |
| Least privilege | Required |
| Activity logging | Required where applicable |
| Periodic access review | Required |

### 4. Contractor Offboarding

When the contract ends:

- Disable contractor accounts.
- Revoke remote access.
- Revoke MFA/authentication tokens where applicable.
- Remove system permissions.
- Recover company equipment.
- Recover company information where required.
- Confirm completion with the system owner.

## Contractor Security Principle

Contractors should receive only the access necessary to perform their approved duties and only for the period in which that access is required.
----

# PS — Termination and Transfer Notification Workflow

## Purpose

This workflow ensures that employee termination and role changes are communicated to the appropriate teams so that access can be removed, modified, or reviewed.

## Termination Workflow

```text
Employee Termination Confirmed
            ↓
       HR Notification
            ↓
        IT + Security
            ↓
     Identify All Access
            ↓
   Disable/Revoke Access
            ↓
 Recover Company Assets
            ↓
 System Owner Confirmation
            ↓
     Security Review
            ↓
       Close Record
