# Stakeholder Map — Attendance Regularization (ESSP)

## Purpose
This document identifies the key stakeholders involved in the Attendance Regularization process in the Employee Self-Service Portal (ESSP), their roles, interests, and how they interact with the system.

---

## Stakeholder Overview

| Role | Description | Responsibilities | Pain Points | Dependencies |
|------|--------------|------------------|--------------|---------------|
| **Employee (Requester)** | Submits attendance regularization requests for missing IN/OUT punches. | Initiate requests, provide justifications, attach supporting documents. | Delay in approval, unclear rejection reasons, lack of visibility on request status. | Line Manager, HR |
| **Line Manager (Approver)** | Reviews and approves or rejects employee requests. | Validate reason, ensure accuracy of regularization. | Too many requests, lack of time, missing context for decisions. | Employee, HR |
| **HR (Monitor / Override)** | Monitors process, manages escalations, and can override decisions if necessary. | Handle escalations, update policies, finalize records before payroll. | Manual corrections, repetitive queries, policy ambiguity. | Employee, Payroll |
| **Payroll (Consumer)** | Consumes approved attendance data to process salaries. | Ensure accuracy of attendance data before salary computation. | Incorrect data affects payroll accuracy. | HR, IT Admin |
| **IT Admin (Configuration)** | Maintains ESSP configuration, roles, and permissions. | System configuration, troubleshooting, ensuring uptime. | Requests for last-minute changes, unclear business rules. | HR, Compliance |
| **Audit / Compliance** | Ensures the process follows organizational and legal guidelines. | Verify data integrity, track approvals and exceptions. | Lack of audit trails or incomplete records. | HR, IT Admin |

---

## Communication Flow
- **Employee → Manager → HR → Payroll** is the standard approval and data flow.
- **Audit/Compliance** reviews post-payroll reports and system logs.
- **IT Admin** supports the workflow configuration and access management.

---

## Notes & Contact Points
- Use these personas to design interview templates and UAT stakeholders.
- For simulated interviews, mark notes as **Simulated** and include assumptions used.
