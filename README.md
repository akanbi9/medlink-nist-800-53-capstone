# medlink-nist-800-53-capstone

# SecureCore 53: NIST SP 800-53 Security Assessment

**Student:** NURAIN ABDULLAH 
**Role:** Junior GRC and Cybersecurity Analyst  
**Organization:** MedLink Services Ltd.  
**Project Type:** NIST SP 800-53 GRC Capstone

## Project Overview
This project presents a simulated cybersecurity and privacy assessment of MedLink Services Ltd. using NIST SP 800-53 as a control catalog. The assessment identifies security and privacy control gaps, evaluates risks, develops remediation actions, and provides a 90-day security improvement roadmap.

## Assessment Objectives

- Define the assessment scope and system boundary.
- Identify critical assets and data types.
- Assess selected NIST SP 800-53 controls.
- Cover all 20 NIST control families.
- Assess at least 40 controls.
- Perform deep-dive testing on at least 10 controls.
- Identify and prioritize cybersecurity risks.
- Develop a POA&M for remediation.
- Create a 90-day security improvement roadmap.
- Provide evidence-based recommendations to management.


## Assessment Scope

The assessment covers:

- Microsoft 365 and cloud services
- Windows laptops and desktops
- Customer portal
- HR and payroll application
- On-premises file server
- Network infrastructure
- Backup systems
- Remote and hybrid workers
- Third-party IT and payroll vendors
- Physical security controls
- Security and privacy processes


## Assessment Methodology

The assessment uses a risk-based approach based on NIST SP 800-53 and NIST SP 800-53A concepts.

Controls are assessed using:

1. Documentation examination
2. Interviews
3. Testing and observation
4. Evidence review

Control status is classified as:

- Implemented
- Partially Implemented
- Not Implemented
- Not Applicable


## Top Findings

The assessment identified significant weaknesses in access management, authentication, logging and monitoring, configuration management, backup testing, incident response, removable-media protection, privacy management, risk management, and patch management.

Key findings include:
- Former contractor accounts remain active in the cloud directory.
- MFA is not consistently enforced for remote users.
- No centralized log-review schedule exists.
- Secure laptop configuration baselines are not established.
- Backup restoration has not been tested within the last 12 months.
- The incident response plan has never been exercised.
- Removable-media handling requirements are unclear.
- A current PII inventory has not been completed.
- No consolidated cybersecurity risk register exists.
- Several endpoints are more than 45 days behind on patches.

## Top Five Risks

1. **Unauthorized cloud access** caused by stale user accounts.
2. **Account compromise** caused by inconsistent MFA enforcement.
3. **Data loss and prolonged downtime** caused by untested backups.
4. **System compromise** caused by unpatched endpoints.
5. **PII exposure and privacy risk** caused by inadequate data inventory and management.


## NIST SP 800-53 Control-Family Coverage

| Family | Name | Controls Assessed |
|---|---|---:|
| AC | Access Control | 2+ |
| AT | Awareness and Training | 2+ |
| AU | Audit and Accountability | 2+ |
| CA | Assessment, Authorization and Monitoring | 2+ |
| CM | Configuration Management | 2+ |
| CP | Contingency Planning | 2+ |
| IA | Identification and Authentication | 2+ |
| IR | Incident Response | 2+ |
| MA | Maintenance | 2+ |
| MP | Media Protection | 2+ |
| PE | Physical and Environmental Protection | 2+ |
| PL | Planning | 2+ |
| PM | Program Management | 2+ |
| PS | Personnel Security | 2+ |
| PT | PII Processing and Transparency | 2+ |
| RA | Risk Assessment | 2+ |
| SA | System and Services Acquisition | 2+ |
| SC | System and Communications Protection | 2+ |
| SI | System and Information Integrity | 2+ |
| SR | Supply Chain Risk Management | 2+ |



## 90-Day Security Improvement Roadmap

### Phase 1 — Days 0–30
- Disable stale accounts
- Enforce MFA
- Address critical patches
- Validate backup restoration

### Phase 2 — Days 31–60
- Conduct access reviews
- Improve security awareness records
- Establish log-review procedures
- Exercise the incident-response plan
- Assess critical vendors

### Phase 3 — Days 61–90
- Establish security metrics
- Review policies
- Implement continuous monitoring
- Improve supplier security management
- Establish recurring security tests


## Repository Structure

```text
medlink-nist-800-53-capstone/
│
├── README.md
│
├── scope-and-inventory/
│   ├── system-boundary.md
│   ├── asset-inventory.csv
│   └── data-flow-diagram.png
│
├── control-assessment/
│   ├── control-matrix.csv
│   ├── deep-dive-tests.md
│   └── evidence-register.csv
│
├── control-families/
│   ├── AC-access-control.md
│   ├── AT-awareness-training.md
│   ├── AU-audit-accountability.md
│   └── ...
│
├── risk-and-remediation/
│   ├── risk-register.csv
│   ├── poam.csv
│   └── 90-day-roadmap.md
│
├── templates/
│
├── diagrams/
│   ├── architecture.png
│   └── risk-heat-map.png
│
├── report/
│   └── NIST_800-53_Assessment_Abdullah_Akanbi.pdf
│
├── presentation/
│   └── NIST_800-53_Presentation_Abdullah_Akanbi.pdf
│
└── references/
    └── sources.md



## Evidence and Safety

This project uses simulated, synthetic, or redacted evidence for educational purposes.

No real:
- passwords
- API keys
- customer information
- employee information
- internal IP addresses
- access tokens
- confidential company information

are included in this repository.

All screenshots, logs, records, diagrams, and other evidence are clearly identified as simulated or synthetic where applicable.

No systems were scanned, tested, or accessed without explicit authorization.


## References

- NIST SP 800-53 Rev. 5 — Security and Privacy Controls for Information Systems and Organizations
- NIST SP 800-53A Rev. 5 — Assessing Security and Privacy Controls
- NIST SP 800-53B — Control Baselines
- NIST CSRC official resources
- Additional vendor/product documentation used during the assessment

**NIST version/date consulted:** [Insert version and date]





