# Deep-Dive Control Assessment Tests

## 1. Assessment Methodology

The purpose of this assessment is to check whether the security controls in the organization are properly implemented and working as expected.
Each selected control is assessed using one or more of the following methods:

A simple and repeatable assessment method will be used. The assessment is based on the basic concepts of NIST SP 800-53A.

1. Examine
2. Interview
3. Test/Observe

### Examine

Review documented policies, procedures, configurations, system records, logs, screenshots, reports, and other evidence to determine whether the control has been implemented.

### Interview

Speak with the responsible personnel or control owner to understand how the control operates and whether the documented process is followed.

### Test/Observe

Perform or observe a practical test of the control to determine whether it operates as intended.

---

## 2. Assessment Process

For each control:

1. Identify the control requirement.
2. Determine whether the control is applicable.
3. Identify the responsible control owner.
4. Collect supporting evidence.
5. Examine documentation and records.
6. Interview responsible personnel where necessary.
7. Test or observe the control where practical.
8. Compare the evidence with the control requirement.
9. Record the assessment status.
10. Document findings and risks.
11. Assign a responsible risk owner.
12. Set a target due date for remediation where required.

---

## 3. Control Status Definitions

### Implemented

The control is implemented and operating as intended. Sufficient evidence exists to support the assessment.

### Partially Implemented

The control is implemented to some extent, but weaknesses, gaps, or inconsistencies were identified.

### Not Implemented

The required control has not been implemented or there is insufficient evidence that it operates.

### Not Applicable

The control does not apply to the system or organization.

Not Applicable because the organization does not develop or maintain its own cryptographic modules.

---

## 4. Assessment Methods

| Method | Description | Example Evidence |
|---|---|---|
| Examine | Review documentation and records | Policies, procedures, logs |
| Interview | Discuss control operation with responsible personnel | IT staff interview |
| Test | Verify whether the control works as required | Access control test |
| Observe | Observe the control operating in practice | MFA login demonstration |

---

## 5. Example Deep-Dive Test: AC-2 Account Management

### Control

AC-2 — Account Management

### Purpose

Ensure that user accounts are properly created, managed, reviewed, disabled, and removed.

### Assessment Procedures

**Examine**

- Review the account management policy.
- Review the user directory.
- Review records of recently terminated employees.
- Check whether inactive accounts are disabled.

**Interview**

Interview the IT administrator responsible for account management.

Questions:

- Who creates user accounts?
- Who approves new accounts?
- How are accounts disabled when employees leave?
- How often are accounts reviewed?

**Test/Observe**

I will select a sample of user accounts and compare them with the organization's current employee records.

I will check whether:

- Active employees have valid accounts.
- Former employees have been disabled.
- Privileged accounts are properly identified.
- Unused accounts are disabled.

### Evidence Required

- Directory export
- Account management policy
- User account review records
- Employee termination records
- Screenshots of account status

### Expected Result

User accounts should be created and managed according to the organization's procedures.

When an employee leaves the organization, their account should be disabled or removed within the required timeframe.

Regular account reviews should also be performed to identify inactive, unnecessary, or unauthorized accounts.

### Example Finding

During the review of the user directory, some accounts belonging to former employees were found to still be active.

This shows that the account removal process is not being followed consistently.

### Risk

Active accounts belonging to former employees could be used for unauthorized access.

### Status

Partially Implemented

### Recommended Action

The organization should review user accounts regularly and make sure that accounts belonging to employees who leave the organization are disabled promptly.

The organization should also maintain records of account reviews and employee offboarding activities.
