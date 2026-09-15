# Control Assessment Plan

## 1. Purpose

The purpose of this Control Assessment Plan is to establish a repeatable process for assessing the effectiveness of security and privacy controls within the organization's information system.

## 2. Assessment Methods

Controls will be assessed using three primary methods:

| Method              | Description                                                            | Example                                                 |
| ------------------- | ---------------------------------------------------------------------- | ------------------------------------------------------- |
| Examination         | Review documents, configurations, records, and other evidence          | Review access-control policies                          |
| Interview           | Ask responsible personnel questions about how controls operate         | Interview the IT Administrator about account management |
| Testing/Observation | Test or observe controls to determine whether they operate as intended | Test whether MFA is required for user login             |

## 3. Assessment Process

The assessment process will follow these steps:

1. Identify the controls to be assessed.
2. Define the assessment objective and expected result.
3. Identify the evidence required.
4. Examine relevant documents and system records.
5. Interview responsible personnel where necessary.
6. Test or observe the control where appropriate.
7. Record the assessment results.
8. Identify weaknesses or deficiencies.
9. Assign a risk level to each weakness.
10. Record weaknesses in the POA&M/remediation tracker.
11. Assign an owner and due date for remediation.
12. Conduct follow-up assessments to verify that weaknesses have been corrected.
13. Report significant findings to management.

## 4. Assessment Result Categories

| Result              | Meaning                                                  |
| ------------------- | -------------------------------------------------------- |
| Satisfied           | Control is implemented and operating effectively         |
| Partially Satisfied | Control is implemented but has some weaknesses           |
| Not Satisfied       | Control is missing or ineffective                        |
| Not Applicable      | Control does not apply to the organization's environment |

## 5. Assessment Frequency

Critical controls may be assessed more frequently based on risk. Formal security control assessments should be performed at least annually and after significant changes to the system or security environment.

## 6. Assessment Evidence

Examples of assessment evidence include:

* Security policies
* Configuration screenshots
* Access-control records
* Audit logs
* Vulnerability scan results
* Training records
* Backup test results
* System configurations
* Interview notes
* Test results

## 7. Reporting

Assessment findings shall be documented and reported to management. Identified weaknesses shall be entered into the POA&M/remediation tracker and monitored until they are resolved or formally accepted by authorized management.


## Continuous Monitoring Schedule
| Activity                    | Frequency | Owner         | Evidence                    |
| --------------------------- | --------- | ------------- | --------------------------- |
| User access review          | Quarterly | IT            | Access review report        |
| Vulnerability review        | Monthly   | IT            | Vulnerability scan report   |
| Audit log review            | Weekly    | IT            | Weekly log-review record    |
| Backup test                 | Quarterly | IT            | Backup test report          |
| Security assessment         | Annually  | Security Team | Assessment report           |
| Firewall rule review        | Quarterly | Network Admin | Firewall review record      |
| Security awareness review   | Quarterly | IT/HR         | Training records            |
| Incident-response exercise  | Annually  | Security Team | Exercise report             |
| System configuration review | Monthly   | IT            | Configuration review record |

## POA&M (Plan of Action and Milestones)
For example, during an assessment you discover:
A former employee's account is still active.
ID,Weakness,Risk,Owner,Due Date,Status,Remediation
POA-001,Former accounts remain active,High,IT,2026-10-15,Open,Disable terminated user accounts
POA-002,Some laptops have missing security updates,High,IT,2026-10-30,In Progress,Install required security patches
POA-003,Annual security awareness training not completed by all staff,Medium,HR/IT,2026-11-15,Open,Complete awareness training and quiz
POA-004,Firewall rules have not been reviewed recently,Medium,Network Admin,2026-10-25,Open,Perform firewall rule review
POA-005,Backup restoration test has not been documented,Medium,IT,2026-11-01,Planned,Perform and document backup restoration test

## procedure to follow when to do  POA&M


Assessment 
    ↓
Find weakness
    ↓
Record in POA&M
    ↓
Assign owner
    ↓
Set deadline
    ↓
Fix weakness
    ↓
Verify the fix
    ↓
Close the weakness

# Management Authorization Recommendation

## Recommendation: Approve with Conditions

Based on the completed control assessment and review of identified security weaknesses, it is recommended that management **approve the continued operation of the information system with conditions**.

The assessment identified several weaknesses, including inactive accounts that require removal, missing security updates on some endpoints, incomplete security awareness training, and outstanding firewall and backup reviews.

The identified weaknesses are being tracked through the organization's POA&M/remediation tracker. High-risk findings shall be prioritized and remediated within the agreed timeframe.

Management should receive periodic updates on remediation progress. The authorization should be reviewed if a major security incident occurs, significant system changes are introduced, or identified risks increase beyond the organization's acceptable level.

### Conditions of Authorization

1. High-risk findings must be remediated within the approved timeframe.
2. Remediation activities must be documented.
3. IT must regularly monitor outstanding POA&M items.
4. Significant security incidents must be reported to management.
5. Continuous monitoring activities must continue according to the approved schedule.
6. A follow-up assessment must verify that completed remediation actions are effective.

### Final Recommendation

**Approve with conditions.**

The system may continue operating because the identified risks are being actively managed; however, outstanding high-risk weaknesses must be addressed within the agreed remediation period.
