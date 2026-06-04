# ServiceNow ITIL
Hands-on ServiceNow ITSM lab using a free Personal Developer Instance. Covers incident management, service catalogue creation, change requests with approval workflows, and operational reporting. Aligned to CompTIA A+, Network+, and ITIL 4 Foundation

📹 Loom Walkthrough
🎥 Watch the full lab walkthrough on Loom (coming soon)


Overview  

This lab demonstrates hands-on experience with ServiceNow, one of the most widely deployed IT Service Management (ITSM) platforms in enterprise IT. Using a free Personal Developer Instance (PDI), I built and worked through core ITSM workflows including incident management, service catalogue creation, change management with approval routing, and operational reporting.

ServiceNow is used across IT Support, Help Desk, Sysadmin, and Cloud Operations roles from day one. This lab builds the foundational platform fluency expected in professional IT environments.


Certification Alignment
Certification
Relevance
CompTIA A+
Incident creation, ticket routing, resolution documentation
CompTIA Network+
Network-related incident scenarios, change management
ITIL 4 Foundation
Incident vs Problem vs Change, SLAs, Service Catalogue, KEDB



Tools Used
Tool
Cost
ServiceNow Personal Developer Instance
Free — developer.servicenow.com



What This Lab Covers
Skill
Real-World Application
Create and resolve an Incident
Core daily task in every IT support role
Set ticket priority and SLA
Defines response time commitments to the business
Assign tickets to queues and individuals
Proper routing reduces resolution time in team environments
Build a Service Catalogue item
Enables user self-service for common IT requests
Create an approval workflow for Change Requests
Enforces ITIL change control before production modifications
Run reports on ticket volume and resolution time
Metrics that drive IT operations decisions at every level
Apply ITIL Incident vs Problem vs Change concepts
Language used in every enterprise IT role



Lab Steps
Step 1 — Provision a Free ServiceNow PDI
Created a free account at developer.servicenow.com
Requested a Personal Developer Instance (Washington release)
Received instance URL and credentials via email within 15 minutes
Step 2 — Navigate the Platform
Explored core modules: Incidents, Problems, Changes, Service Catalog, Reports, Flow Designer
Oriented to the admin interface and left navigation structure
Step 3 — Create and Work an Incident
Created an incident for a user unable to access Outlook (corrupted OST file scenario)
Set Priority 3 — Moderate, assigned to Service Desk queue
Added work notes, documented investigation steps, logged resolution
Closed ticket with user confirmation
Step 4 — Build a Service Catalogue Item
Created a New Laptop Request catalogue item under the Hardware category
Configured variables: Requester Name, Business Justification, Required By Date, Laptop Model Preference
Published item to the self-service portal
Step 5 — Create a Change Request with Approval Workflow
Logged a Standard Change for a monthly security patch deployment (CVE-2024-0001, CVSS 7.8)
Documented Test Plan, Backout Plan, and maintenance window (Saturday 2–6 AM)
Submitted for approval → approved as admin → moved to Scheduled state
Step 6 — Build Operational Reports
Incident Volume by Priority — Last 30 Days (Bar Chart)
Mean Time to Resolution (MTTR) by Assignment Group (Bar Chart)
Open Incidents by Assigned Agent (for workload balancing)


ITIL Concepts Applied
ITIL Term
Definition
ServiceNow Module
Incident
Unplanned service interruption — restore service ASAP
Service Desk → Incidents
Problem
Root cause of one or more incidents — eliminate permanently
Service Desk → Problems
Change
Planned modification to infrastructure — implement with minimal risk
Change → Changes
Service Request
User request for something new (access, hardware) — not break/fix
Service Catalog
SLA
Committed response and resolution time per priority level
SLA → SLA Definitions
CMDB
Record of every IT asset and its relationships
Configuration → CIs
Knowledge Base
Known issue articles that reduce repeat incident volume
Knowledge → Articles



Screenshots
#
Screenshot
Description
1
screenshots/incident-resolved.png
Completed incident with work notes and resolution
2
screenshots/service-catalog-item.png
New Laptop Request catalogue item with variables
3
screenshots/change-request-approval.png
Change request in Scheduled state after approval
4
screenshots/report-incident-volume.png
Incident Volume by Priority — Last 30 Days report



Key Takeaways
ServiceNow enforces ITIL process discipline at the platform level — tickets follow defined state workflows, changes require approval, and SLAs are tracked automatically
The difference between an Incident (restore service now) and a Problem (fix the root cause permanently) is fundamental to how enterprise IT teams operate
Service Catalogues reduce help desk call volume by giving users a structured self-service path for routine requests
Reporting and metrics aren't optional — IT operations decisions are driven by ticket volume, MTTR, and SLA compliance data


Lab Series
Lab
Topic
Status
Lab 1
NTFS File Server — Azure VMs, Active Directory, SMB Shares
✅ Complete
Lab 2
Azure AD Domain Controller — Terraform + PowerShell
✅ Complete
Lab 3
Wireshark Network Analysis — TCP, HTTP, DNS Capture
✅ Complete
Lab 4
ServiceNow ITSM — Incidents, Catalogue, Change, Reports
✅ Complete




Built by Shemira | Windows Systems Administrator | CompTIA Security+ | AWS Cloud Practitioner
