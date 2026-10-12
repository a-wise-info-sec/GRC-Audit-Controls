# Access Controls — UAC, GAC, and IAM

Controls determined by job roles and duties, applying least privilege on an as-needed basis for user access. UAC addressed individual needs and required programs to complete job tasks. GAC addressed role-based group membership, accesses based upon group need.

Manager-requested access went through the review chain to determine necessity. When granted, access was provided, documented, and added to tracking; group access, user accesses, and company-issued machines. Records underwent quarterly access audits to mitigate compliance violations. All information tracked and compiled for removal at the end of user access life cycle.

## 1. Control overview

| Area | Practice |
|---|---|
| Onboarding | All accesses determined based upon least privilege policy and granted within 24 hours. |
| Individual access — UAC | Determine access needs from the user's job role and duties. |
| Group access — GAC | Determine group membership from the user's role and the access provided by the group. |
| Additional access | Route manager requests through the review chain to determine necessity. |
| Access tracking | Record each user's access, group membership, and assigned machines. |
| Changes | Revisit access when the user's role or access needs change. |
| Quarterly audits | Check for role changes that may not have been communicated and reassess access. |
| Termination | Enforce removal of all access within 24 hours of termination. |

## 2. Requested access

| Step | Process |
|---|---|
| Request | An employee identifies a need and requests a new access through management. |
| Necessity review | The request went through the review chain to determine whether the access was necessary. |
| Decision | Access was granted if the review resulted in authorization. |
| Provisioning | Granted access was provided to the user. |
| Documentation | The access was documented and added to the user's tracking record. |

**Example of User Access:** ManageEngine, Office365, Keycard and door accesses, company-issued technology. An infosec employee requires firewall access, an employee in operations does not.

## 4. Group access record — GAC

Record group membership separately from the access the group provides.

### Group permission reference

| Group | Role/duties served | System/resource |
|---|---|---|---|
| Software Developers | Write, test, and deploy application code | AWS staging, JIRA |
| QA | Validate code quality and manage testing workflows | TestRail, AWS Testing Environment |
| Operations & Finance | Payroll, ledgers, financial workflows | NetSuite, WorkDay, Bank Portal |
|Information Security | Manage firewalls permissions, Azure Groups, and security protocols | ManageEngine, Meraki Firewall, escalation privileges | 

### User group membership

| User ID | Current role | Group | Role-based justification | Status |
|---|---|---|---|---|
| — | — | — | — | — |

## 5. Assigned-machine record

Machine assignments were tracked alongside access. An assigned machine is recorded as an asset; its assignment alone does not establish the user's permissions.

| User ID | Machine identifier | Machine type | Assignment/location | Assignment status |
|---|---|---|---|---|
| — | — | — | — | — |

## 6. Role changes and quarterly review

Access was revisited when roles or access needs changed. Quarterly audits provided another opportunity to identify changes that had not been brought to my attention.

### Representative review record

| User ID | Current role/duties | Access or group reviewed | Still required? | Reason/action needed | Follow-up status | Review date |
|---|---|---|---|---|---|---|
| — | — | — | — | — | — | — |

**Review prompts**

- Does the individual's access match their current duties?
- Is group membership appropriate for the current role?
- Has a role change affected what access is needed?
- Is additional granted access reflected in tracking?
- Do access and machine records reflect the user's current assignments?

## 7. Termination — 24-hour removal requirement

I enforced the strict requirement to remove all access within 24 hours of termination. Maintaining records of what each person could access, where that access existed, their groups, and their machines supported complete offboarding.

### Representative removal record

| User ID | Termination date/time | Removal deadline | Access item/location | Group/direct source | Removal date/time | Completion reference | Within 24 hours? |
|---|---|---|---|---|---|---|---|
| — | — | — | — | — | — | — | — |

### Completion checks

- Account for the access items in the user's tracking record.
- Account for group memberships and the access associated with them.
- Record removal completion against the 24-hour deadline.
- Identify assigned machines for the offboarding process.

Machine recovery and disposition are separate from access removal; their procedures are not specified in this portfolio.

---

**Skills represented:** Individual access assessment · Group access governance · Least privilege · Access-request review · Access and asset tracking · Quarterly access review · Termination policy enforcement
