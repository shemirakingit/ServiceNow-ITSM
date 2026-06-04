# ServiceNow ITIL
Hands-on ServiceNow ITSM lab using a free Personal Developer Instance. Covers incident management, service catalogue creation, change requests with approval workflows, and operational reporting. Aligned to CompTIA A+, Network+, and ITIL 4 Foundation

**📹 Loom Walkthrough**

🎥 Watch the full lab walkthrough on Loom (coming soon)


**Overview**  

This lab demonstrates hands-on experience with ServiceNow, one of the most widely deployed IT Service Management (ITSM) platforms in enterprise IT. Using a free Personal Developer Instance (PDI), I built and worked through core ITSM workflows including incident management, service catalogue creation, change management with approval routing, and operational reporting.

ServiceNow is used across IT Support, Help Desk, Sysadmin, and Cloud Operations roles from day one. This lab builds the foundational platform fluency expected in professional IT environments.


**Tools Used**    -
ServiceNow Personal Developer Instance — Free at developer.servicenow.com


**Certification Alignment**     -
CompTIA A+
CompTIA Network+
ITIL 4 Foundation


**What This Lab Covers**    -
Create and resolve an Incident
Set ticket priority and SLA
Assign tickets to queues and individuals
Build a Service Catalogue item
Create an approval workflow for Change Requests
Run reports on ticket volume and resolution time
Apply ITIL Incident vs Problem vs Change concepts


**Lab Steps**     -


Step 1 — Provision a Free ServiceNow PDI Created a free account at developer.servicenow.com, requested a Personal Developer Instance (Washington release), and received instance URL and credentials via email within 15 minutes.

Step 2 — Navigate the Platform Explored core modules including Incidents, Problems, Changes, Service Catalog, Reports, and Flow Designer.

Step 3 — Create and Work an Incident Created an incident for a user unable to access Outlook due to a corrupted OST file. Set Priority 3 — Moderate, assigned to the Service Desk queue, added work notes, documented investigation steps, logged resolution, and closed with user confirmation.

Step 4 — Build a Service Catalogue Item Created a New Laptop Request catalogue item under the Hardware category with variables for Requester Name, Business Justification, Required By Date, and Laptop Model Preference. Published to the self-service portal.

Step 5 — Create a Change Request with Approval Workflow Logged a Standard Change for a monthly security patch deployment. Documented Test Plan, Backout Plan, and maintenance window. Submitted for approval, approved as admin, and moved to Scheduled state.

Step 6 — Build Operational Reports Built three reports: Incident Volume by Priority (Last 30 Days), Mean Time to Resolution by Assignment Group, and Open Incidents by Assigned Agent.


**ITIL Concepts Applied**     



Incident — Unplanned service interruption. Goal: restore service as quickly as possible.

Problem — Root cause of one or more incidents. Goal: eliminate the root cause permanently.

Change — Planned modification to infrastructure. Goal: implement with minimal risk.

Service Request — User request for something new such as access or hardware. Not a break/fix.

SLA — Committed response and resolution time per priority level.

CMDB — Record of every IT asset and its relationships.

Knowledge Base — Known issue articles that reduce repeat incident volume.


**Screenshots**     -
screenshots/incident-resolved.png — Completed incident with work notes and resolution
screenshots/service-catalog-item.png — New Laptop Request catalogue item with variables
screenshots/change-request-approval.png — Change request in Scheduled state after approval
screenshots/report-incident-volume.png — Incident Volume by Priority — Last 30 Days report


**Key Takeaways**     



ServiceNow enforces ITIL process discipline at the platform level — tickets follow defined state workflows, changes require approval, and SLAs are tracked automatically
The difference between an Incident (restore service now) and a Problem (fix the root cause permanently) is fundamental to how enterprise IT teams operate
Service Catalogues reduce help desk call volume by giving users a structured self-service path for routine requests
Reporting and metrics aren't optional — IT operations decisions are driven by ticket volume, MTTR, and SLA compliance data



Built by Shemira | Windows Systems Administrator | CompTIA Security+ | AWS Cloud Practitioner
