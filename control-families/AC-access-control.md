## Access-control matrix

This shows who is allowed to access what system and what level of access they have.
| Role          | Microsoft 365 | Customer Portal | HR System  | Finance System | File Server    |
| ------------- | ------------- | --------------- | ---------- | -------------- | -------------- |
| Staff         | Standard      | Read/Write      | No Access  | No Access      | Read           |
| Administrator | Admin         | Admin           | Admin      | Admin          | Admin          |
| HR            | Standard      | No Access       | Read/Write | Read           | HR Folder      |
| Finance       | Standard      | No Access       | No Access  | Read/Write     | Finance Folder |
| Contractor    | Limited       | Limited         | No Access  | No Access      | Limited        |
| Vendor        | No Access     | Support         | No Access  | No Access      | No Access      |


## Quarterly access review

[ ] Review active user accounts

[ ] Check users who changed roles

[ ] Check former employees

[ ] Check contractors

[ ] Review privileged accounts

[ ] Remove unnecessary permissions

[ ] Record reviewer and review date

[ ] Document identified issues


## Joiner-Mover-Leaver

JOINER
New employee
    ↓
Manager approves access
    ↓
IT creates account
    ↓
Assign role-based permissions
    ↓
Enable MFA

MOVER
Employee changes role
    ↓
Manager requests access change
    ↓
IT removes old permissions
    ↓
IT assigns new permissions
    ↓
Review access

LEAVER
Employee leaves
    ↓
HR informs IT
    ↓
Disable account
    ↓
Revoke sessions/tokens
    ↓
Remove access
    ↓
Recover company devices


## Two assessed controls

 — Account Management

Finding: Some former employee accounts remain active.

Status: Partially Implemented.

 — Least Privilege

Finding: Some users have permissions beyond what is required for their job.

Status: Partially Implemented.









