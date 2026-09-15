# MedLink Laptop Configuration Baseline Checklist

## Purpose

This checklist defines the minimum secure configuration required for MedLink company laptops.

| No. | Configuration Item            | Required Baseline                                            | Check |
| --: | ----------------------------- | ------------------------------------------------------------ | :---: |
|   1 | Operating system              | Supported Windows version installed                          |   ☐   |
|   2 | Security updates              | Automatic security updates enabled                           |   ☐   |
|   3 | Firewall                      | Windows Firewall enabled                                     |   ☐   |
|   4 | Antivirus/Endpoint Protection | Enabled and up to date                                       |   ☐   |
|   5 | User account                  | Standard user account used for daily activities              |   ☐   |
|   6 | Administrator access          | Restricted to authorized administrators                      |   ☐   |
|   7 | Password                      | Strong password policy enforced                              |   ☐   |
|   8 | MFA                           | MFA enabled for supported services                           |   ☐   |
|   9 | Screen lock                   | Automatic lock enabled after inactivity                      |   ☐   |
|  10 | Disk encryption               | Device encryption/BitLocker enabled where supported          |   ☐   |
|  11 | USB/removable media           | Controlled according to organizational policy                |   ☐   |
|  12 | Browser                       | Supported and updated browser installed                      |   ☐   |
|  13 | Unnecessary software          | Unapproved applications removed                              |   ☐   |
|  14 | Remote access                 | Only approved remote-access tools allowed                    |   ☐   |
|  15 | Backup                        | Important business data protected according to backup policy |   ☐   |
|  16 | Logging                       | Required security logging enabled                            |   ☐   |
|  17 | Screen privacy                | Laptop configured to reduce unauthorized viewing             |   ☐   |

## Baseline Approval

**Baseline Owner:** IT Administrator
**Review Frequency:** Quarterly and after major security changes
**Approved By:** IT/Security Lead
**Baseline Version:** 1.0

# Authorized Software List Template
**What software is allowed to be installed on MedLink laptops?**

# MedLink Authorized Software List

## Purpose

This document identifies software that is approved for installation and use on MedLink company laptops.

Only software listed as authorized or specifically approved through the change-management process should be installed on company devices.

| Software           | Version                   | Purpose             | Authorized | Owner/Approver |
| ------------------ | ------------------------- | ------------------- | ---------- | -------------- |
| Microsoft Windows  | Supported version         | Operating system    | Yes        | IT             |
| Microsoft Edge     | Current supported version | Web browsing        | Yes        | IT             |
| Google Chrome      | Current supported version | Web browsing        | Yes        | IT             |
| Microsoft 365 Apps | Current supported version | Productivity        | Yes        | IT             |
| Microsoft Teams    | Current supported version | Communication       | Yes        | IT             |
| Windows Security   | Current supported version | Endpoint protection | Yes        | IT             |
| VLC Media Player   | Approved version          | Media playback      | Yes        | IT             |

## Unauthorized Software

Examples of software that must not be installed without approval include:

* Cracked or pirated software
* Unapproved remote-access tools
* Unlicensed applications
* Software from unknown or suspicious sources
* Applications that are not required for business activities

## Software Approval Process

If an employee requires software that is not on the authorized list, they must submit a change request.

IT shall review the software for:

1. Business necessity
2. Security risk
3. Licensing requirements
4. Vendor reputation
5. Compatibility
6. Privacy implications

The software may only be installed after authorization.

# MedLink Change Request and Approval Form

## Change Request

**Change Request ID:** CM-CR-001
**Date:** __________________
**Requester:** __________________
**Department:** __________________
**System/Device:** __________________

### 1. Description of Change

Describe what configuration or software change is being requested:

---

### 2. Reason for Change

Explain why the change is required:

---

### 3. Security Impact

What security risks could result from this change?

---

### 4. Business Impact

How will the change affect normal business operations?

---

### 5. Implementation Plan

Explain how the change will be implemented:

---

### 6. Rollback Plan

Explain how the configuration can be returned to the previous secure state if the change causes problems:

---

## Approval

| Role             | Name | Decision          | Date | Signature |
| ---------------- | ---- | ----------------- | ---- | --------- |
| Requester        |      | Submitted         |      |           |
| IT Administrator |      | Approved/Rejected |      |           |
| Security/IT Lead |      | Approved/Rejected |      |           |
| Manager          |      | Approved/Rejected |      |           |

## Implementation Record

**Implementation Date:** __________________

**Implemented By:** __________________

**Result:** Successful / Unsuccessful

**Configuration Updated:** Yes / No

**Documentation Updated:** Yes / No


# MedLink Configuration Drift Review Process

## 1. Purpose

The purpose of this process is to identify and correct differences between the approved MedLink laptop configuration baseline and the actual configuration of company devices.

## 2. Review Frequency

Configuration drift reviews shall be performed monthly and after significant system changes.

Critical configuration changes may be investigated immediately when detected.

## 3. Review Process

1. Identify the approved laptop configuration baseline.
2. Collect the current configuration of MedLink laptops.
3. Compare the actual configuration against the approved baseline.
4. Identify differences or unauthorized changes.
5. Determine whether each difference is authorized.
6. Check the change-management records for approved changes.
7. Record unauthorized differences as configuration drift.
8. Assess the security risk of the drift.
9. Restore the device to the approved baseline where appropriate.
10. Create a change request if the new configuration is legitimately required.
11. Document the corrective action.
12. Recheck the device to confirm that the drift has been resolved.

## 4. Examples of Configuration Drift

Examples include:

* Firewall disabled
* Security updates disabled
* Unauthorized software installed
* Antivirus/endpoint protection disabled
* Unauthorized administrator account created
* Disk encryption disabled
* Unapproved remote-access software installed
* Security settings changed without approval

## 5. Drift Review Record

| Device     | Drift Detected                  | Risk   | Authorized Change? | Action                 | Status |
| ---------- | ------------------------------- | ------ | ------------------ | ---------------------- | ------ |
| ML-LAP-001 | Firewall disabled               | High   | No                 | Firewall re-enabled    | Closed |
| ML-LAP-002 | Unauthorized software installed | Medium | No                 | Software removed       | Closed |
| ML-LAP-003 | New approved software installed | Low    | Yes                | Change record verified | Closed |
| ML-LAP-004 | Security update missing         | High   | No                 | Update installed       | Closed |

## 6. Escalation

High-risk configuration drift shall be reported to the IT/Security Lead immediately.

Examples include:

* Disabled endpoint protection
* Disabled firewall
* Unauthorized administrator account
* Unauthorized remote-access software
* Significant security-control changes

## 7. Documentation

All detected configuration drift and corrective actions shall be documented and retained as evidence of configuration management activities.


