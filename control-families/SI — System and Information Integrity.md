# SI — System and Information Integrity

## Purpose

The System and Information Integrity (SI) family focuses on maintaining the security, accuracy, and integrity of MedLink Services Ltd. systems and information.

This family covers:

* Patching
* Vulnerability management
* Malware protection
* Integrity monitoring
* Security alerts

## Assessment Status

**Status:** Partially Implemented — Simulated

The assessment scenario identified endpoints that were more than 45 days behind on patches. The scenario does not provide evidence of a formal patch-management procedure, vulnerability remediation SLA, standardized endpoint protection checklist, or monthly vulnerability and patch reporting process.

---

# Practical Evidence

This folder contains:

1. Patch Management Procedure
2. Vulnerability Remediation SLA
3. Endpoint Protection Checklist
4. Monthly Vulnerability/Patch Status Report

---

# 1. Patch Management Procedure

## Purpose

The patch-management procedure ensures that operating systems, applications, and security software are regularly updated to address known vulnerabilities and security issues.

## Scope

This procedure applies to:

* Windows laptops
* Desktop computers
* Servers
* Network devices
* Business applications
* Security software
* Cloud systems where applicable

## Patch Management Process

### Step 1 — Identify Available Updates

IT personnel should identify available:

* Security patches
* Operating system updates
* Application updates
* Firmware updates
* Security tool updates

### Step 2 — Identify Vulnerabilities

Known vulnerabilities should be reviewed and assigned a severity level.

Severity should consider:

* Technical impact
* Business impact
* Exploit availability
* Affected systems
* Exposure to attackers

### Step 3 — Prioritize

Patches should be prioritized according to their severity and business risk.

Critical vulnerabilities receive the highest priority.

### Step 4 — Test

Where practical, patches should be tested before deployment to important production systems.

Testing should verify:

* System functionality
* Application compatibility
* Security controls
* Possible operational impact

### Step 5 — Deploy

Approved patches should be deployed to affected systems.

Deployment may be:

* Automatic
* Scheduled
* Manual
* Emergency

### Step 6 — Verify

After deployment, IT should verify that:

* The patch was successfully installed.
* The system is operating correctly.
* No important security controls were disabled.
* Failed installations are identified.

### Step 7 — Record

Patch activities should be recorded and included in the monthly patch-status report.

### Step 8 — Handle Exceptions

If a system cannot be patched within the required timeframe, the exception should be documented.

The record should include:

* Affected system
* Reason for delay
* Risk
* Compensating control
* Responsible owner
* Expected remediation date

---

# 2. Vulnerability Remediation SLA

The following remediation targets are used to prioritize vulnerability treatment.

| Severity | Remediation Target |
| -------- | -----------------: |
| Critical |             7 days |
| High     |            14 days |
| Medium   |            30 days |
| Low      |            60 days |

## SLA Requirements

### Critical

Critical vulnerabilities should be addressed within **7 days**.

If immediate patching is not possible, temporary risk-reduction measures should be considered and the exception documented.

### High

High-severity vulnerabilities should be addressed within **14 days**.

### Medium

Medium-severity vulnerabilities should be addressed within **30 days**.

### Low

Low-severity vulnerabilities should be addressed within **60 days**.

## SLA Tracking

Each vulnerability should have:

* Vulnerability ID
* Affected asset
* Severity
* Date identified
* Remediation target
* Responsible owner
* Current status
* Remediation date

---

# 3. Endpoint Protection Checklist

The following checklist should be used to verify that MedLink endpoints have appropriate security protections.

## Antivirus / Anti-Malware

* [ ] Approved endpoint protection installed.
* [ ] Endpoint protection is enabled.
* [ ] Real-time protection is enabled.
* [ ] Malware definitions/signatures are updated.
* [ ] Regular malware scans are enabled.
* [ ] Detected malware is investigated.

## Operating System

* [ ] Supported operating system is installed.
* [ ] Security updates are installed.
* [ ] Automatic updates are enabled where appropriate.
* [ ] Unsupported software is removed or upgraded.

## Access Protection

* [ ] User authentication is enabled.
* [ ] Administrator privileges are restricted.
* [ ] Unnecessary accounts are disabled.
* [ ] Screen lock is configured.

## Application Security

* [ ] Approved software is installed.
* [ ] Unnecessary applications are removed.
* [ ] Applications are regularly updated.
* [ ] Unauthorized software is investigated.

## Integrity Monitoring

* [ ] Important system files are monitored where appropriate.
* [ ] Unauthorized configuration changes are investigated.
* [ ] Security logs are available.
* [ ] Suspicious changes generate alerts where supported.

## Security Alerts

* [ ] Malware alerts are monitored.
* [ ] Failed security updates are reviewed.
* [ ] Vulnerability alerts are reviewed.
* [ ] Suspicious endpoint activity is investigated.
* [ ] High-risk alerts are escalated.

## Review

**Asset ID:** __________________

**Device:** ____________________

**Reviewer:** __________________

**Review Date:** _______________

**Status:** Pass / Fail / Exception

---

# 4. Integrity Monitoring

Integrity monitoring helps identify unauthorized or unexpected changes to important systems and information.

MedLink should monitor important changes such as:

* Critical system files
* Security configurations
* Application configurations
* Administrator accounts
* Security software settings
* Important business data

## Example

```text
Expected Configuration
        |
        v
   System Monitoring
        |
        v
Unexpected Change?
     /       \
   No         Yes
   |           |
Continue     Alert
               |
               v
          Investigation
```

Any suspicious change should be investigated and documented.

---

# 5. Security Alerts

Security alerts should be reviewed according to their severity.

Examples include:

* Malware detection
* Failed security updates
* Critical vulnerability alerts
* Unauthorized configuration changes
* Suspicious login activity
* Endpoint security disabled
* Repeated failed authentication
* Unusual system activity

## Alert Handling

```text
Security Alert
      |
      v
Review Alert
      |
      v
Determine Severity
      |
      v
Investigate
      |
      v
Contain / Remediate
      |
      v
Document Result
```

Critical security alerts should be escalated according to the organization's incident-response process.

---

# 6. Monthly Vulnerability / Patch Status Report

**Reporting Period:** September 2026

**Prepared By:** IT/Security Team

**Report Date:** 30 September 2026

## Patch Status Summary

| Metric                    | Result |
| ------------------------- | -----: |
| Total Endpoints           |     58 |
| Fully Patched             |     42 |
| Pending Patches           |     16 |
| Critical Vulnerabilities  |      2 |
| High Vulnerabilities      |      5 |
| Medium Vulnerabilities    |      8 |
| Low Vulnerabilities       |      4 |
| Overdue Remediation Items |      3 |

> **Note:** The figures above are simulated evidence created for the MedLink assessment and do not represent real organizational data.

## Vulnerability Status

| Vulnerability ID | Affected Asset  | Severity | Date Identified | SLA     | Status      | Owner            |
| ---------------- | --------------- | -------- | --------------- | ------- | ----------- | ---------------- |
| VUL-001          | Laptop Group A  | Critical | 2026-09-05      | 7 days  | Remediated  | IT               |
| VUL-002          | Customer Portal | Critical | 2026-09-10      | 7 days  | In Progress | Application Team |
| VUL-003          | Laptop Group B  | High     | 2026-09-08      | 14 days | Remediated  | IT               |
| VUL-004          | File Server     | High     | 2026-09-12      | 14 days | In Progress | System Admin     |
| VUL-005          | Employee Laptop | Medium   | 2026-09-15      | 30 days | Open        | IT               |

## Patch Compliance

| Category         | Number |
| ---------------- | -----: |
| Total Systems    |     58 |
| Patched          |     42 |
| Pending          |     16 |
| Patch Compliance |  72.4% |

## Key Observations

1. Some endpoints require security updates.
2. Critical and high vulnerabilities require priority remediation.
3. Three remediation items are currently overdue.
4. Patch deployment should be monitored regularly.
5. Vulnerability status should be reviewed monthly.

## Recommended Actions

* Prioritize critical vulnerabilities.
* Complete overdue patches.
* Investigate systems that repeatedly fail patch deployment.
* Review vulnerability status monthly.
* Maintain documented remediation exceptions.
* Improve endpoint patch compliance.

## Report Approval

**Prepared By:** ______________________

**Reviewed By:** ______________________

**Approved By:** ______________________

**Date:** ______________________________

---

# 7. Practical Evidence Summary

| Evidence                           | Purpose                                                            |
| ---------------------------------- | ------------------------------------------------------------------ |
| Patch Management Procedure         | Defines how patches are identified, tested, deployed, and verified |
| Vulnerability Remediation SLA      | Defines how quickly vulnerabilities should be addressed            |
| Endpoint Protection Checklist      | Verifies endpoint security controls                                |
| Monthly Vulnerability/Patch Report | Shows ongoing vulnerability and patch monitoring                   |
| Integrity Monitoring Records       | Shows monitoring of important system changes                       |
| Security Alert Records             | Shows detection and investigation of security events               |

## Overall Improvement

MedLink should establish a formal patch and vulnerability-management process, enforce remediation timelines, maintain endpoint protection, monitor system integrity, and produce regular vulnerability and patch-status reports.
