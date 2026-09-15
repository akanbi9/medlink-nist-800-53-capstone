# PT — PII Inventory and Data Map

## Purpose

This document identifies the major categories of Personally Identifiable Information (PII) processed by MedLink, why the information is needed, where it is stored, who uses it, and who may receive it.

## PII Inventory

| PII Category | Purpose | Location | Internal Users | Recipients | Retention |
|---|---|---|---|---|---|
| Employee Name | Employment administration | HR System | HR, Management | Authorized HR personnel | Employment + required period |
| Employee Email | Business communication | Microsoft 365 | Staff | Authorized staff | Business need |
| Employee ID | Employee identification | HR System | HR, IT | Authorized personnel | Employment + required period |
| Payroll Information | Salary processing | HR/Payroll | HR, Finance | Authorized finance/payroll personnel | Required period |
| Customer Name | Service delivery | Customer Portal | Support | Authorized support staff | Business need |
| Customer Email | Customer communication | Customer Portal/Microsoft 365 | Support | Authorized staff | Business need |
| Customer Phone | Customer support | Customer Portal | Support | Authorized support staff | Business need |
| Customer Account Data | Service delivery | Customer Database | Authorized staff | Authorized system users | Business/legal need |
| IP Address | Security monitoring | Security Logs | IT, Security | Authorized security personnel | Defined security period |

## Data Flow

```text
Customer
   ↓
Customer Portal
   ↓
Customer Database
   ↓
Authorized Support Staff
   ↓
Service Delivery

Employee
   ↓
HR
   ↓
HR System
   ↓
Payroll / Finance
   ↓
Salary Processing

Users
   ↓
Microsoft 365
   ↓
Business Communication

Systems
   ↓
Security Logs
   ↓
IT / Security Team
   ↓
Security Monitoring

---

# PT — PII Retention and Deletion Schedule

## Purpose

This schedule defines how MedLink manages the retention and secure deletion of PII.

## Retention Schedule

| PII Category | Retention Rule | Deletion Trigger | Disposal Method |
|---|---|---|---|
| Employee Records | Employment + required period | Retention period expires | Secure deletion |
| Employee Email | Employment + defined business period | Account closure/retention expiry | Account removal |
| Payroll Information | Required employment/payroll period | Retention requirement expires | Secure deletion |
| Customer Name | Active service + defined period | Account closure and retention expiry | Secure deletion |
| Customer Email | Business/service need | Retention need ends | Secure deletion |
| Customer Phone | Business/service need | Retention need ends | Secure deletion |
| Customer Account Data | Active account + defined period | Account closure and retention expiry | Secure deletion |
| Security Logs | Defined security retention period | Retention period expires | Secure deletion |

## Retention Principles

- PII must not be retained indefinitely without a documented reason.
- Retention periods should be based on business, contractual, security, employment, or legal requirements.
- Retention periods should be reviewed periodically.
- PII that is no longer required should be securely deleted or disposed of.
- Legal holds or investigations may require information to be preserved beyond normal deletion schedules.
- Deletion activities should be documented where appropriate.

## Deletion Process

```text
PII Identified
      ↓
Retention Period Defined
      ↓
Business/Legal Need Ends
      ↓
Check for Legal Hold or Investigation
      ↓
Secure Deletion Approved
      ↓
PII Deleted
      ↓
Deletion Recorded



**Important:** Since this is a student portfolio, don't invent specific statutory retention periods unless your assignment gives you a particular law or regulation to apply.

---

# 4. Privacy Notice Improvement Recommendation

A **privacy notice** explains to people how their personal information is being processed.

A good notice should clearly tell the person:

- What information is collected
- Why it is collected
- How it is used
- Who it is shared with
- How long it is retained
- What rights/options are available
- How to contact the organization about privacy

### `privacy-notice-improvement.md`

```markdown
# PT — Privacy Notice Improvement Recommendations

## Purpose

MedLink should improve its privacy notice so that customers and employees can easily understand how their PII is collected, used, shared, retained, and protected.

## Recommended Improvements

### 1. Explain What PII Is Collected

The privacy notice should clearly identify major categories of information collected.

Examples:

- Name
- Email address
- Phone number
- Account information
- Employment information
- Payroll information where applicable
- Security and technical information

### 2. Explain Why PII Is Collected

Each major category should have a clear purpose.

For example:

> Customer contact information is used to provide services and communicate with customers.

### 3. Explain Who Receives PII

The notice should identify relevant categories of recipients, such as:

- Authorized employees
- Service providers
- Payroll/financial service providers where applicable
- Security and technology providers
- Authorities where disclosure is required by applicable law

### 4. Explain Data Retention

The notice should explain how long information is retained or the criteria used to determine the retention period.

### 5. Explain Data Security

The notice should provide a general description of measures used to protect PII, without revealing sensitive security details.

Examples:

- Access controls
- Authentication
- Encryption where appropriate
- Security monitoring
- Employee security training

### 6. Explain Individual Rights and Choices

The notice should explain applicable privacy rights and how individuals can make privacy-related requests.

### 7. Provide a Privacy Contact

MedLink should provide a clear method for contacting the organization about privacy questions or requests.

### 8. Use Clear Language

The privacy notice should:

- Avoid unnecessary technical language.
- Use clear headings.
- Be easy to read.
- Clearly distinguish required information from optional information.
- Explain important information before collecting PII.

## Recommended Notice Structure

```text
1. Introduction
2. Information We Collect
3. Why We Collect It
4. How We Use It
5. Who We Share It With
6. Data Retention
7. Data Security
8. Privacy Rights and Choices
9. Cookies/Tracking Where Applicable
10. Contact Information
11. Privacy Notice Updates


