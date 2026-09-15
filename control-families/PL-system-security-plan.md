# PL — System Security Plan (SSP)

## 1. System Overview

Describe the organization and the purpose of the system.

Example:
The organization is a 20-person digital services company that
provides online services to customers. The environment includes
employee laptops, cloud email, a company website, customer data,
online payment services, guest Wi-Fi, and remote workers.

## 2. System Boundary

Define what is included in the assessment.

### In Scope
- Employee laptops
- Cloud email
- Company website
- Customer database
- Network infrastructure
- Online payment environment
- Remote access
- Company social media accounts

### Out of Scope
- Personal employee devices not used for company business
- Third-party systems outside the organization's control

## 3. System Architecture

Describe how the systems connect.

Example:
Employees connect to the company network and cloud services.
The website communicates with the application and database.
Remote workers connect through approved secure access mechanisms.

See:
`architecture/security-architecture.md`

## 4. Assets

List important assets.

| Asset | Description | Importance |
|---|---|---|
| Employee laptops | Used for business operations | High |
| Customer database | Stores customer information | Critical |
| Website | Public-facing service | High |
| Cloud email | Business communication | High |
| Network equipment | Provides connectivity | High |

## 5. Data Types

Identify information handled by the organization.

- Customer information
- Employee information
- Business documents
- Authentication credentials
- Financial/payment information
- System logs

## 6. Security Controls

Describe the controls used to protect the environment.

Examples:
- Multi-factor authentication
- Access control
- Antivirus/endpoint protection
- Firewalls
- Backups
- Security awareness training
- Logging and monitoring
- Encryption
- Incident response procedures

## 7. Roles and Responsibilities

| Role | Responsibility |
|---|---|
| Management | Provides security direction and approval |
| IT Administrator | Maintains systems and access |
| Security Officer | Monitors security and manages incidents |
| Employees | Follow security policies |
| HR | Supports employee security procedures |

## 8. Risks

Identify major risks.

| Risk | Impact | Risk Level |
|---|---|---|
| Phishing | Credential theft | High |
| Ransomware | System/data loss | Critical |
| Unauthorized access | Data exposure | High |
| USB malware | Malware infection | Medium |
| Power failure | Service disruption | High |

## 9. Security Requirements

The organization must:
- Protect sensitive information.
- Restrict unauthorized access.
- Monitor security events.
- Maintain secure configurations.
- Train employees.
- Maintain backups.
- Respond to security incidents.
- Review security controls regularly.

## 10. Authorization

The system must be reviewed and approved by the appropriate
management authority before being placed into operation.

Authorization must be reviewed periodically and when significant
changes occur.


# Rules of Behavior
Rules on what users are allowed and not allowed to do when using company systems.

All users must:

- Use company systems only for authorized business purposes.
- Keep passwords confidential.
- Use MFA where required.
- Lock their computers when leaving their workstation.
- Report suspicious emails and security incidents.
- Protect company information from unauthorized disclosure.
- Use only approved software.
- Follow removable-media rules.
- Protect company devices from theft or damage.

Users must not:

- Share passwords or authentication tokens.
- Install unauthorized software.
- Connect unauthorized USB devices.
- Attempt to bypass security controls.
- Access information they are not authorized to access.
- Share confidential information with unauthorized persons.
- Use company systems for malicious or illegal activities.

Violations may result in disciplinary action and removal of access.












