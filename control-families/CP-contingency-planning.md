# MedLink Critical Services and RTO/RPO

## Purpose

This document identifies MedLink's critical services and defines their Recovery Time Objective (RTO) and Recovery Point Objective (RPO).

| Service           | Criticality |     RTO |     RPO |
| ----------------- | ----------- | ------: | ------: |
| Customer Portal   | Critical    | 4 hours |  1 hour |
| Microsoft 365     | High        | 8 hours | 4 hours |
| Customer Database | Critical    | 4 hours |  1 hour |
| File Server       | High        | 8 hours | 4 hours |

## Recovery Priorities

### Priority 1 — Critical

The Customer Portal and Customer Database must be restored first because their unavailability could significantly affect customers and business operations.

### Priority 2 — High

Microsoft 365 and the File Server should be restored after the critical services and within their defined recovery objectives.

## Recovery Requirements

MedLink shall maintain appropriate backups and recovery procedures for critical systems. Backup and restoration procedures shall be tested periodically to verify that systems and data can be recovered within the defined recovery objectives.

# MedLink Backup and Restore Test Plan

## 1. Purpose

The purpose of this test is to verify that MedLink can successfully restore critical data from backups and meet the organization's recovery requirements.

## 2. Test Scope

The test will cover:

* Customer Database
* File Server
* Backup storage
* Restoration procedures

## 3. Test Objectives

The test will determine whether:

1. Backups are available and readable.
2. Backup data can be restored successfully.
3. Restored data is complete and usable.
4. The restoration process can meet the defined RTO.
5. The restored data meets the defined RPO.
6. Recovery procedures are properly documented.

## 4. Test Procedure

1. Select a recent backup.
2. Verify that the backup is available.
3. Record the backup date and time.
4. Simulate the loss of the selected system or test environment.
5. Restore the system/data from the backup.
6. Verify that the restored data is accessible.
7. Check a sample of files or database records for integrity.
8. Record the restoration start and completion times.
9. Calculate the recovery time.
10. Compare the result against the defined RTO and RPO.
11. Document any problems encountered.
12. Identify corrective actions where necessary.

## 5. Test Record

| Item                        | Result             |
| --------------------------- | ------------------ |
| Test Date                   | __________________ |
| System Tested               | __________________ |
| Backup Date/Time            | __________________ |
| Restore Start Time          | __________________ |
| Restore Completion Time     | __________________ |
| Recovery Time               | __________________ |
| Target RTO                  | __________________ |
| Target RPO                  | __________________ |
| Data Successfully Restored? | Yes / No           |
| Data Integrity Verified?    | Yes / No           |
| RTO Met?                    | Yes / No           |
| RPO Met?                    | Yes / No           |
| Issues Identified           | __________________ |
| Corrective Action           | __________________ |
| Test Owner                  | __________________ |

## 6. Success Criteria

The test is considered successful when the required data is restored correctly and the recovery process meets the defined RTO and RPO requirements.

# MedLink After-Action Report

## 1. Exercise Information

**Exercise Name:** Customer Database Failure Tabletop Exercise

**Date:** __________________

**Facilitator:** __________________

**Participants:** __________________

## 2. Exercise Objective

The objective was to evaluate MedLink's ability to respond to a customer database failure, protect information, communicate with management, and restore critical services within the defined recovery objectives.

## 3. What Went Well

Examples:

* The incident was identified quickly.
* IT personnel understood the basic recovery process.
* Backup locations were identified.
* Critical services were prioritized correctly.

## 4. Problems Identified

| ID      | Finding                                                        | Risk   | Recommended Action            | Owner         |
| ------- | -------------------------------------------------------------- | ------ | ----------------------------- | ------------- |
| AAR-001 | Recovery responsibilities were not clearly assigned            | Medium | Assign recovery roles         | IT            |
| AAR-002 | Backup restoration procedure requires additional documentation | Medium | Update recovery procedure     | IT            |
| AAR-003 | Communication contacts were not up to date                     | Medium | Review emergency contact list | Management/IT |

## 5. Lessons Learned

The exercise demonstrated the importance of clearly defined recovery responsibilities, tested backups, current contact information, and documented recovery procedures.

## 6. Corrective Actions

| Action                              | Owner         | Due Date   | Status |
| ----------------------------------- | ------------- | ---------- | ------ |
| Assign recovery responsibilities    | IT            | __________ | Open   |
| Update backup restoration procedure | IT            | __________ | Open   |
| Review emergency contacts           | Management/IT | __________ | Open   |

## 7. Overall Result

**Exercise Result:** Needs Improvement / Satisfactory / Successful

## 8. Conclusion

The tabletop exercise provided an opportunity to identify gaps in MedLink's contingency and recovery procedures. Identified weaknesses shall be tracked until corrective actions are completed and verified.

# How CP connects everything
             CP — CONTINGENCY PLANNING
                       │
                       ↓
             Identify critical services
                       │
                       ↓
                 Set RTO and RPO
                       │
                       ↓
                 Create backups
                       │
                       ↓
              Test backup restoration
                       │
                       ↓
             Practice emergency response
                (Tabletop Exercise)
                       │
                       ↓
               Identify weaknesses
                       │
                       ↓
              After-Action Report
                       │
                       ↓
                Improve the plan
