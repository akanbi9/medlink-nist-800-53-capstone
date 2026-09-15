# RA — Risk Scoring Method

## Purpose

MedLink uses a Likelihood × Impact method to assess cybersecurity risks.

## Risk Formula

```text
Risk Score = Likelihood × Impact
```
---

# 3. Risk Register — 12 Risks

This is the **main part** of your Risk Assessment.

Because you already worked on **IA, AU, CA, CM, CP, IR, PM, PS and PII**, your risks should come from those areas.

Here is a good set of 12 fictional MedLink risks:

| ID | Risk | Likelihood | Impact | Score | Level | Owner |
|---|---|---:|---:|---:|---|---|
| R-001 | Former accounts remain active | 4 | 5 | 20 | Critical | IT |
| R-002 | Phishing attack compromises user credentials | 4 | 4 | 16 | Critical | Security |
| R-003 | Outdated software remains unpatched | 3 | 5 | 15 | Critical | IT |
| R-004 | Ransomware affects critical systems | 3 | 5 | 15 | Critical | Security |
| R-005 | Excessive privileged access | 3 | 5 | 15 | Critical | Security |
| R-006 | Customer PII exposed through unauthorized access | 3 | 5 | 15 | Critical | Security |
| R-007 | Security logs are incomplete or unavailable | 3 | 4 | 12 | High | IT |
| R-008 | Backup cannot successfully restore critical data | 3 | 5 | 15 | Critical | IT |
| R-009 | Unauthorized software installed on endpoints | 3 | 3 | 9 | Medium | IT |
| R-010 | Contractor retains access after contract ends | 3 | 4 | 12 | High | IT/HR |
| R-011 | Security configuration drift | 3 | 4 | 12 | High | IT |
| R-012 | Employee security awareness is insufficient | 4 | 3 | 12 | High | Security/HR |

These are **example project risks**, not findings about a real organization.

---

# 4. `risk-register.csv`

Because your assignment specifically calls it a **risk register**, CSV is a good format.

You can create:

```text
risk-register.csv
```

# RA — Top-Five Risk Heat Map

## Risk Heat Map

| Impact \ Likelihood | 1 | 2 | 3 | 4 | 5 |
|---|---:|---:|---:|---:|---:|
| 5 Severe | 5 | 10 | 15 | 20 | 25 |
| 4 High | 4 | 8 | 12 | 16 | 20 |
| 3 Moderate | 3 | 6 | 9 | 12 | 15 |
| 2 Low | 2 | 4 | 6 | 8 | 10 |
| 1 Very Low | 1 | 2 | 3 | 4 | 5 |

## Top-Five Risks

| Risk ID | Risk | Likelihood | Impact | Score |
|---|---|---:|---:|---:|
| R-001 | Former accounts remain active | 4 | 5 | 20 |
| R-002 | Phishing compromises credentials | 4 | 4 | 16 |
| R-003 | Outdated software remains unpatched | 3 | 5 | 15 |
| R-004 | Ransomware affects critical systems | 3 | 5 | 15 |
| R-005 | Excessive privileged access | 3 | 5 | 15 |


# RA — High-Risk Treatment Decisions

## Purpose

This document records the treatment decision for each High and Critical risk identified in the MedLink risk register.

---

## R-001 — Former Accounts Remain Active

**Risk Score:** 20  
**Risk Level:** Critical  
**Owner:** IT

**Treatment:** Mitigate

**Actions:**
- Implement a formal offboarding process.
- Disable accounts immediately when access is no longer required.
- Review inactive accounts regularly.
- Revoke active sessions and remote access.
- Coordinate HR and IT termination notifications.

**Expected Result:**

Former personnel should no longer have unauthorized access to MedLink systems.

---

## R-002 — Phishing Compromises User Credentials

**Risk Score:** 16  
**Risk Level:** Critical  
**Owner:** Security

**Treatment:** Mitigate

**Actions:**
- Require MFA for high-risk accounts.
- Conduct security awareness training.
- Provide phishing awareness exercises.
- Monitor suspicious authentication activity.
- Use email security controls where appropriate.
- Maintain an account-compromise response procedure.

**Expected Result:**

The likelihood and potential impact of credential compromise are reduced.

---

## R-003 — Outdated Software Remains Unpatched

**Risk Score:** 15  
**Risk Level:** Critical  
**Owner:** IT

**Treatment:** Mitigate

**Actions:**
- Maintain an asset and software inventory.
- Monitor available security updates.
- Prioritize critical vulnerabilities.
- Establish patching deadlines.
- Verify patch installation.
- Track exceptions and overdue patches.

**Expected Result:**

Known software vulnerabilities are identified and remediated within defined timeframes.

---

## R-004 — Ransomware Affects Critical Systems

**Risk Score:** 15  
**Risk Level:** Critical  
**Owner:** Security

**Treatment:** Mitigate

**Actions:**
- Maintain endpoint protection.
- Restrict unnecessary privileges.
- Maintain secure backups.
- Test backup restoration.
- Maintain a ransomware response playbook.
- Conduct incident-response exercises.
- Monitor suspicious activity.

**Expected Result:**

MedLink can reduce ransomware exposure and recover critical services following an incident.

---

## R-005 — Excessive Privileged Access

**Risk Score:** 15  
**Risk Level:** Critical  
**Owner:** Security

**Treatment:** Mitigate

**Actions:**
- Maintain a privileged-account inventory.
- Apply least privilege.
- Require MFA for administrators.
- Use separate administrative accounts.
- Review privileged access quarterly.
- Remove unnecessary privileges.

**Expected Result:**

Administrative access is limited to authorized personnel with a valid business need.

---

## R-006 — Customer PII Exposed

**Risk Score:** 15  
**Risk Level:** Critical  
**Owner:** Security

**Treatment:** Mitigate

**Actions:**
- Maintain a PII inventory.
- Apply least-privilege access.
- Monitor access to sensitive data.
- Minimize unnecessary PII collection.
- Define retention and deletion periods.
- Review privacy procedures regularly.

**Expected Result:**

Unauthorized access or unnecessary retention of customer PII is reduced.

---

## R-007 — Incomplete Security Logs

**Risk Score:** 12  
**Risk Level:** High  
**Owner:** IT

**Treatment:** Mitigate

**Actions:**
- Maintain a log-source inventory.
- Identify critical events that must be logged.
- Review logs regularly.
- Protect logs from unauthorized modification.
- Establish escalation criteria.

**Expected Result:**

MedLink has sufficient audit information to investigate security events.

---

## R-008 — Backup Restoration Failure

**Risk Score:** 15  
**Risk Level:** Critical  
**Owner:** IT

**Treatment:** Mitigate

**Actions:**
- Maintain regular backups.
- Protect backup systems.
- Test restoration periodically.
- Document restoration procedures.
- Verify recovery against RTO and RPO requirements.

**Expected Result:**

MedLink can restore critical systems and data within defined recovery requirements.

---

## R-010 — Contractor Retains Access

**Risk Score:** 12  
**Risk Level:** High  
**Owner:** IT/HR

**Treatment:** Mitigate

**Actions:**
- Give contractors time-limited access.
- Require approval before access is granted.
- Review contractor accounts.
- Disable accounts when contracts end.
- Recover company assets.

**Expected Result:**

Contractor access exists only while there is an approved business requirement.

---

## R-011 — Configuration Drift

**Risk Score:** 12  
**Risk Level:** High  
**Owner:** IT

**Treatment:** Mitigate

**Actions:**
- Maintain secure configuration baselines.
- Review endpoint configurations regularly.
- Document approved changes.
- Investigate unauthorized changes.
- Restore systems to the approved baseline.

**Expected Result:**

Unauthorized configuration changes are identified and corrected.

---

## R-012 — Insufficient Security Awareness

**Risk Score:** 12  
**Risk Level:** High  
**Owner:** Security/HR

**Treatment:** Mitigate

**Actions:**
- Provide security awareness training.
- Track training completion.
- Conduct periodic awareness activities.
- Teach phishing and social-engineering awareness.
- Measure training performance through KPIs.

**Expected Result:**

Employees understand their security responsibilities and are better prepared to identify and report suspicious activity.

