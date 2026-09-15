# SR — Supply Chain Risk Management

## Purpose

The Supply Chain Risk Management (SR) family focuses on identifying and managing security risks introduced by third-party suppliers that provide technology, services, software, cloud services, or business support to MedLink Services Ltd.

MedLink suppliers include:

* Cloud providers
* IT support providers
* Payroll providers
* Software vendors

The main objective is to understand:

> **Who are our suppliers, how important are they, what security risks do they introduce, and what happens if something goes wrong or the relationship ends?**

---

# 1. Supplier Inventory and Criticality Rating

MedLink should maintain an inventory of suppliers and identify the importance and risk associated with each supplier.

| Supplier         | Service                | Criticality | Risk   |
| ---------------- | ---------------------- | ----------- | ------ |
| Microsoft 365    | Email / Cloud Services | Critical    | High   |
| IT Support       | Technical Support      | High        | High   |
| Payroll Provider | Payroll Services       | High        | High   |
| Software Vendor  | Business Application   | Medium      | Medium |

> **Note:** Supplier information above is based on the simulated MedLink scenario.

## Supplier Inventory Template

| Field                | Description                     |
| -------------------- | ------------------------------- |
| Supplier ID          | Unique supplier identifier      |
| Supplier Name        | Name of supplier                |
| Service              | Service provided                |
| Business Owner       | MedLink person responsible      |
| Data Accessed        | Type of data accessed           |
| Criticality          | Critical / High / Medium / Low  |
| Risk Rating          | High / Medium / Low             |
| Contract Status      | Active / Expired / Under Review |
| Security Review Date | Date of latest assessment       |
| Incident Contact     | Supplier security contact       |
| Exit Plan            | Available / Not Available       |

---

# 2. Supplier Risk Assessment

Each important supplier should be assessed before being approved and periodically during the relationship.

## Supplier Information

**Supplier:** __________________________

**Service:** ___________________________

**Business Owner:** ____________________

**Assessment Date:** ___________________

**Reviewer:** ___________________________

## Risk Assessment Checklist

### Business Criticality

* [ ] Supplier provides a critical business service.
* [ ] Service disruption could affect business operations.
* [ ] Supplier processes important MedLink information.
* [ ] Alternative supplier/service is available.

### Data Protection

* [ ] Supplier accesses MedLink data.
* [ ] Type of data handled has been identified.
* [ ] Data protection requirements are documented.
* [ ] Encryption requirements are defined.
* [ ] Data retention requirements are defined.
* [ ] Data deletion requirements are defined.

### Access Control

* [ ] Supplier access is authorized.
* [ ] Supplier users receive least-privilege access.
* [ ] MFA is supported where applicable.
* [ ] Supplier administrative access is controlled.
* [ ] Supplier access is reviewed periodically.

### Security Management

* [ ] Supplier has documented security policies.
* [ ] Supplier performs vulnerability management.
* [ ] Supplier has an incident-response process.
* [ ] Supplier maintains appropriate security monitoring.
* [ ] Supplier has backup and recovery procedures where applicable.

### Third-Party Risk

* [ ] Supplier uses subcontractors.
* [ ] Relevant subcontractors have been identified.
* [ ] Security requirements extend to relevant subcontractors.
* [ ] Supplier's supply-chain risks have been reviewed.

## Risk Rating

| Factor                | Rating                         |
| --------------------- | ------------------------------ |
| Business Impact       | Low / Medium / High / Critical |
| Data Sensitivity      | Low / Medium / High / Critical |
| Access Level          | Low / Medium / High / Critical |
| Service Dependency    | Low / Medium / High / Critical |
| Overall Supplier Risk | Low / Medium / High / Critical |

## Assessment Decision

* [ ] Approved
* [ ] Approved with Conditions
* [ ] Additional Security Review Required
* [ ] Not Approved

**Reviewer:** __________________

**Date:** ______________________

---

# 3. Minimum Supplier Security Requirements

Suppliers providing services to MedLink should meet minimum security requirements appropriate to the service and risk.

## Access Control

Suppliers should:

* Use unique accounts for authorized personnel.
* Apply least-privilege access.
* Protect administrative accounts.
* Support MFA where appropriate.
* Remove access when personnel no longer require it.

## Data Protection

Suppliers should:

* Protect MedLink information from unauthorized access.
* Use appropriate encryption for sensitive information.
* Follow agreed data-handling requirements.
* Follow agreed retention requirements.
* Securely delete or return MedLink data when required.

## Vulnerability and Patch Management

Suppliers should:

* Maintain supported systems.
* Apply security updates.
* Identify and address vulnerabilities.
* Maintain processes for managing security weaknesses.

## Security Monitoring

Suppliers should:

* Monitor relevant security events.
* Maintain appropriate security logs.
* Investigate suspicious activity.
* Provide relevant information during security investigations where required.

## Incident Response

Suppliers should:

* Maintain an incident-response process.
* Provide a security contact.
* Notify MedLink of relevant security incidents.
* Cooperate with incident investigations.

## Business Continuity

Where applicable, suppliers should:

* Maintain backup procedures.
* Maintain recovery procedures.
* Test recovery capabilities.
* Communicate major service disruptions.

## Supplier Management

* [ ] Security requirements included in contract.
* [ ] Supplier responsibilities documented.
* [ ] Security contact identified.
* [ ] Review frequency defined.
* [ ] Incident notification requirements defined.
* [ ] Data return/deletion requirements defined.
* [ ] Supplier termination requirements defined.

---

# 4. Supplier Incident Notification Checklist

MedLink should define how suppliers must report security incidents affecting MedLink systems, services, or information.

## Incident Notification Requirements

The supplier should provide:

* [ ] Date and time of incident.
* [ ] Description of the incident.
* [ ] Systems/services affected.
* [ ] Data potentially affected.
* [ ] Initial impact assessment.
* [ ] Actions already taken.
* [ ] Containment measures.
* [ ] Supplier incident contact.
* [ ] MedLink contact information.
* [ ] Follow-up investigation details.

## Incident Process

```text
Supplier Detects Incident
          |
          v
Notify MedLink
          |
          v
MedLink Assesses Impact
          |
          v
Contain / Coordinate Response
          |
          v
Investigate
          |
          v
Recover
          |
          v
Post-Incident Review
```

## Notification Contact

**MedLink Security Contact:** __________________

**Supplier Security Contact:** _________________

**Escalation Contact:** ________________________

---

# 5. Supplier Exit Plan

MedLink should have an exit plan for critical suppliers so that supplier termination does not create unnecessary security or operational risk.

## Exit Checklist

### Before Termination

* [ ] Business owner confirms termination.
* [ ] Replacement service identified where necessary.
* [ ] Data migration requirements identified.
* [ ] Required records identified.
* [ ] Security risks reviewed.

### Access Removal

* [ ] Supplier user accounts disabled.
* [ ] Remote access removed.
* [ ] API credentials/tokens revoked where applicable.
* [ ] Administrative access removed.
* [ ] Physical access removed where applicable.

### Data

* [ ] MedLink data returned where required.
* [ ] Data securely deleted where required.
* [ ] Deletion confirmation obtained where applicable.
* [ ] Backups and retained copies addressed according to agreement.

### Documentation

* [ ] Contract termination documented.
* [ ] Supplier inventory updated.
* [ ] Access records updated.
* [ ] Security review completed.
* [ ] Outstanding risks transferred or remediated.

### Final Review

**Supplier:** __________________________

**Termination Date:** __________________

**Data Returned:** Yes / No / N/A

**Data Deleted:** Yes / No / N/A

**Access Removed:** Yes / No

**Exit Reviewed By:** __________________

**Date:** ______________________________

---

# 6. Supplier Review Frequency

Supplier reviews should be based on the importance and risk of the service.

| Supplier Risk | Suggested Review                                  |
| ------------- | ------------------------------------------------- |
| Critical      | At least annually and after major security events |
| High          | At least annually                                 |
| Medium        | Periodically based on risk                        |
| Low           | Periodically based on risk                        |

---

# 7. Practical Evidence

| Evidence                        | Purpose                                          |
| ------------------------------- | ------------------------------------------------ |
| Supplier Inventory              | Identifies third-party suppliers                 |
| Criticality Rating              | Shows importance of each supplier                |
| Supplier Risk Assessment        | Identifies and evaluates supplier security risks |
| Minimum Security Requirements   | Defines security expectations for suppliers      |
| Incident Notification Checklist | Defines supplier incident-reporting requirements |
| Supplier Exit Checklist         | Controls termination and offboarding             |

## Assessment Status

**Status:** Partially Implemented — Simulated

The MedLink scenario identifies cloud providers, IT support, payroll vendors, and software vendors as third parties. However, the scenario states that there is no standard security questionnaire for suppliers. Therefore, a formal supplier inventory, risk assessment process, minimum security requirements, incident notification process, and exit process are recommended as remediation artifacts.

## Recommended Improvement

MedLink should establish a formal supplier-risk management process that classifies suppliers according to criticality and risk, performs security assessments, defines minimum security requirements, manages supplier incidents, and maintains documented exit procedures.
