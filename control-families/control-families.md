# MA — Maintenance

## 1. Purpose

The Maintenance (MA) control family ensures that maintenance of MedLink Services Ltd. systems is properly authorized, performed by approved personnel, monitored, and documented.

The main objective is to control:

* Who is allowed to perform maintenance.
* What maintenance activities they are allowed to perform.
* When and where maintenance can take place.
* How remote and third-party maintenance is controlled.
* How maintenance activities are recorded.
* How emergency maintenance is approved and reviewed.

---

# 2. Approved Maintenance Procedure

## Purpose

This procedure establishes the requirements for performing maintenance on MedLink systems, laptops, servers, network equipment, cloud services, and other information systems.

## Maintenance Requirements

### Step 1 — Identify the Maintenance Need

The person requesting maintenance must identify:

* System or asset requiring maintenance.
* Reason for maintenance.
* Type of maintenance required.
* Expected date and duration.
* Person or company performing the work.
* Potential security or business impact.

### Step 2 — Obtain Authorization

Normal maintenance must be approved before work begins.

Authorization should come from the appropriate system or IT owner.

The approval should confirm:

* Maintenance is necessary.
* The technician is authorized.
* The planned activity is appropriate.
* Required security controls are in place.

### Step 3 — Verify the Maintenance Personnel

Before maintenance begins, MedLink should verify the identity and authorization of the person performing the work.

For third-party personnel, MedLink should verify:

* Company/vendor identity.
* Technician identity.
* Scope of work.
* Contract or service agreement.
* Required security requirements.
* Approved access method.

### Step 4 — Protect the System

Before maintenance begins:

* Back up important data where appropriate.
* Confirm that recovery procedures are available.
* Restrict access to only what is required.
* Use approved administrator accounts.
* Avoid sharing passwords.
* Use secure remote-access methods.
* Ensure maintenance tools are trusted and authorized.

### Step 5 — Perform Maintenance

The technician should only perform activities included in the approved maintenance request.

Any major change outside the original scope requires additional authorization.

Examples include:

* Installing approved software.
* Applying security patches.
* Replacing hardware.
* Troubleshooting network equipment.
* Updating system configurations.
* Performing approved server maintenance.

### Step 6 — Monitor and Record the Activity

Maintenance activity should be logged.

The record should include:

* Date and time.
* Technician/person performing the work.
* Asset affected.
* Work performed.
* Approval reference.
* Remote-access details where applicable.
* Result of the maintenance.
* Any problems identified.

### Step 7 — Verify the System

After maintenance:

* Confirm that the system operates correctly.
* Confirm that security controls remain active.
* Remove temporary access.
* Close remote sessions.
* Confirm that unauthorized software or accounts were not created.
* Record the final result.

### Step 8 — Close the Maintenance Request

The responsible IT personnel should review the maintenance record and formally close the request.

Any security issue discovered during maintenance should be escalated and documented.

---

# 3. Maintenance Activity Log

The following template should be used to record maintenance activities.

| Field                    | Information                                |
| ------------------------ | ------------------------------------------ |
| Maintenance ID           | MA-001                                     |
| Date                     | YYYY-MM-DD                                 |
| Start Time               | HH:MM                                      |
| End Time                 | HH:MM                                      |
| Asset/System             | System or asset name                       |
| Asset ID                 | Asset identifier                           |
| Maintenance Type         | Preventive / Corrective / Emergency        |
| Reason                   | Reason for maintenance                     |
| Technician               | Name of technician                         |
| Organization             | MedLink / Third Party                      |
| Approval ID              | Related approval/request                   |
| Maintenance Performed    | Description of work                        |
| Remote Access Used       | Yes / No                                   |
| Remote Access Method     | Approved method                            |
| Changes Made             | Summary of changes                         |
| Security Impact          | None / Low / Medium / High                 |
| Backup Confirmed         | Yes / No / N/A                             |
| Result                   | Successful / Partially Successful / Failed |
| Issues Found             | Description                                |
| Temporary Access Removed | Yes / No / N/A                             |
| Verified By              | Reviewer                                   |
| Closure Date             | YYYY-MM-DD                                 |
| Additional Notes         | Additional information                     |

## Example

| Field                    | Example                             |
| ------------------------ | ----------------------------------- |
| Maintenance ID           | MA-001                              |
| Date                     | 2026-09-15                          |
| Asset/System             | Windows Laptop                      |
| Asset ID                 | A-014                               |
| Maintenance Type         | Preventive                          |
| Reason                   | Apply security updates              |
| Technician               | IT Administrator                    |
| Organization             | MedLink IT                          |
| Approval ID              | MNT-2026-014                        |
| Maintenance Performed    | Installed approved security updates |
| Remote Access Used       | No                                  |
| Security Impact          | Low                                 |
| Backup Confirmed         | Yes                                 |
| Result                   | Successful                          |
| Temporary Access Removed | N/A                                 |
| Verified By              | IT Manager                          |

---

# 4. Third-Party Maintenance Authorization Checklist

Third-party maintenance must be authorized before the vendor receives access to MedLink systems.

## Vendor Information

* [ ] Vendor/company name recorded.
* [ ] Technician's name recorded.
* [ ] Technician's identity verified.
* [ ] Contact information recorded.
* [ ] Contract or service agreement confirmed.

## Maintenance Information

* [ ] System/asset requiring maintenance identified.
* [ ] Reason for maintenance documented.
* [ ] Scope of work documented.
* [ ] Expected start and end time recorded.
* [ ] Expected security impact assessed.

## Access Controls

* [ ] Access has been approved.
* [ ] Only required privileges are provided.
* [ ] Temporary accounts are used where appropriate.
* [ ] Shared credentials are prohibited.
* [ ] MFA is enabled where applicable.
* [ ] Remote access uses an approved secure method.
* [ ] Vendor access is monitored/logged.
* [ ] Access expiration time is defined.

## Data Protection

* [ ] Vendor does not receive unnecessary data.
* [ ] Sensitive information is protected.
* [ ] Data transfer is authorized if required.
* [ ] Vendor is required to follow MedLink security requirements.

## Completion

* [ ] Maintenance completed within approved scope.
* [ ] System functionality verified.
* [ ] Temporary access removed.
* [ ] Vendor session terminated.
* [ ] Maintenance activity recorded.
* [ ] Any security issues reported.
* [ ] IT owner reviewed and closed the activity.

### Authorization

**Requested By:** __________________

**Approved By:** __________________

**Date:** __________________

**Approval ID:** __________________

---

# 5. Emergency Maintenance Process

Emergency maintenance may be required when a system has a serious security, availability, or operational problem and waiting for the normal maintenance process could increase risk.

Examples include:

* Critical security vulnerability.
* Active malware infection.
* Major system failure.
* Critical server outage.
* Network equipment failure.
* Security incident requiring immediate technical action.

## Emergency Maintenance Workflow

### 1. Identify the Emergency

The responsible IT or security personnel identify the problem and determine whether immediate maintenance is necessary.

### 2. Assess the Risk

Determine:

* What system is affected?
* What is the business impact?
* What security risk exists?
* What could happen if maintenance is delayed?
* What action is required?

### 3. Obtain Emergency Approval

Where possible, approval should be obtained from the IT Manager or another designated authority before maintenance begins.

If immediate action is required and prior approval is not possible, the technician may perform only the minimum necessary action to stabilize the system.

The reason for bypassing normal approval must be documented.

### 4. Control Access

Only authorized personnel should perform the emergency maintenance.

Access should be:

* Limited.
* Monitored where possible.
* Appropriate to the emergency.
* Removed when no longer required.

### 5. Perform the Minimum Necessary Work

The technician should focus on resolving or containing the emergency.

Unnecessary configuration changes should be avoided.

### 6. Document the Activity

The technician must record:

* What happened.
* Why emergency maintenance was required.
* Who performed the work.
* What actions were taken.
* What systems were affected.
* What changes were made.
* What evidence was collected.
* Whether the system was restored.

### 7. Post-Maintenance Review

After the emergency:

* Verify the system.
* Review the changes.
* Remove temporary access.
* Update documentation.
* Identify security weaknesses.
* Determine whether further remediation is required.
* Update the risk register if necessary.

## Emergency Maintenance Approval Record

| Field                               | Information      |
| ----------------------------------- | ---------------- |
| Emergency ID                        | EM-001           |
| Date/Time                           | YYYY-MM-DD HH:MM |
| Affected System                     | System/asset     |
| Emergency Description               | Description      |
| Business/Security Impact            | Impact           |
| Immediate Action Required           | Yes/No           |
| Technician                          | Name             |
| Approver                            | Name             |
| Reason Normal Approval Was Bypassed | Explanation      |
| Actions Performed                   | Description      |
| Temporary Access Used               | Yes/No           |
| System Restored                     | Yes/No           |
| Follow-up Required                  | Yes/No           |
| Post-Maintenance Reviewer           | Name             |
| Review Date                         | YYYY-MM-DD       |

---

# 6. Maintenance Security Rules

MedLink maintenance personnel should follow these rules:

1. Only authorized personnel may perform maintenance.
2. Maintenance must be approved before it begins whenever possible.
3. Access must follow the principle of least privilege.
4. Remote maintenance must use approved secure access methods.
5. Third-party maintenance must be authorized and monitored.
6. Maintenance activities must be documented.
7. Temporary access must be removed after maintenance.
8. Emergency maintenance must be reviewed after the emergency.
9. Unauthorized software or configuration changes are prohibited.
10. Security issues discovered during maintenance must be reported.

---

# 7. Practical Evidence

The following artifacts provide evidence that the MA controls are being implemented:

| Evidence                            | Purpose                                         |
| ----------------------------------- | ----------------------------------------------- |
| Approved Maintenance Procedure      | Shows how maintenance is controlled             |
| Maintenance Activity Log            | Shows maintenance activities are recorded       |
| Third-Party Authorization Checklist | Shows vendor maintenance is controlled          |
| Emergency Maintenance Process       | Shows emergency work is controlled and reviewed |
| Maintenance Approval Records        | Shows authorization before work                 |
| Remote Access Logs                  | Shows remote maintenance activity               |
| Change Records                      | Shows system changes                            |
| Post-Maintenance Review             | Shows maintenance was verified                  |

## Assessment Status

**Status:** Partially Implemented — Simulated

**Reason:** MedLink has IT maintenance activities, but the scenario does not provide evidence of a standardized maintenance procedure, complete maintenance logs, third-party maintenance authorization, or a documented emergency maintenance approval process. These artifacts are therefore proposed as remediation controls and simulated evidence for the assessment.

## Recommended Improvement

MedLink should establish a standardized maintenance procedure covering authorization, least-privilege access, remote maintenance, third-party maintenance, logging, emergency maintenance, and post-maintenance review.
