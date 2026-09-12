# Incident_Lifecycle_Automation_ServiceNow
ServiceNow Incident Lifecycle Automation manages incidents from creation to resolution. It includes classification, priority, assignment, escalation, Knowledge Management, Emergency Change, child incidents, and SLA tracking. Custom 30-minute response and 4-hour resolution SLAs are tested end to end.
## 📌 Project Overview

**Incident Lifecycle Automation in ServiceNow** is a hands-on IT Service Management project implemented using a ServiceNow Developer Instance.

The project simulates a real-world enterprise IT support scenario in which a user is unable to connect to the corporate VPN.

The incident is systematically processed through:
Incident Creation
        ↓
Classification
        ↓
Priority Assessment
        ↓
Assignment
        ↓
Knowledge Integration
        ↓
Level 2 Escalation
        ↓
Investigation
        ↓
Emergency Change
        ↓
Child Incident
        ↓
Resolution
        ↓
Knowledge Creation
        ↓
SLA Validation
        ↓
Final Validation
The objective is to demonstrate how ServiceNow can provide a structured, traceable, and SLA-driven approach to IT incident management.
# 🎯 Project Objectives

The primary objectives of this project are to:

* Implement a complete Incident Management lifecycle.
* Configure a Service and Service Offering.
* Create and classify incidents.
* Apply Impact, Urgency, and Priority.
* Route incidents to appropriate support groups.
* Demonstrate Level 2 escalation.
* Track investigation using Work Notes.
* Integrate Knowledge Management.
* Coordinate incidents with Emergency Change Management.
* Create and manage parent-child incidents.
* Resolve incidents using structured resolution information.
* Create, approve, and publish Knowledge Articles.
* Configure Response and Resolution SLAs.
* Validate SLA execution on real incident records.
* Perform end-to-end functional testing.
* 
# 🏢 Business Problem

In many organizations, IT incidents are reported through email, phone calls, chat, or informal communication.

This can result in:

* Poor incident tracking
* Incorrect categorization
* Delayed assignment
* Lack of escalation
* Repeated troubleshooting
* SLA breaches
* Poor change traceability
* Lack of reusable troubleshooting knowledge
* Difficulty tracking related incidents

This project addresses these problems by implementing a structured ServiceNow ITSM workflow.
# 💡 Solution

The solution uses ServiceNow to create a controlled incident lifecycle.

A VPN connectivity problem is used as the primary business scenario.

The incident is:

1. Created
2. Classified
3. Prioritized
4. Assigned
5. Investigated
6. Escalated to Level 2
7. Supported using Knowledge Management
8. Coordinated with an Emergency Change
9. Tracked using a Child Incident
10. Resolved
11. Documented through Knowledge Management
12. Validated against SLA requirements
# 🧩 ServiceNow Modules / Capabilities Used

* Incident Management
* Service Configuration
* Service Offering
* Assignment Groups
* Incident Classification
* Impact and Urgency
* Priority Management
* Knowledge Management
* Change Management
* Parent and Child Incidents
* Work Notes
* Resolution Management
* Service Level Management
* SLA Definitions
* Task SLAs
* Functional Testing
* Validation

# ⚙️ ServiceNow Environment

| Component        | Configuration                  |
| ---------------- | ------------------------------ |
| Platform         | ServiceNow                     |
| Environment      | ServiceNow Developer Instance  |
| Application Area | IT Service Management          |
| Primary Process  | Incident Management            |
| Service          | IT Incident Management Service |
| Service Offering | Standard IT Support            |
| Primary Scenario | Corporate VPN Connectivity     |
| Assignment Team  | Network Support                |

---

# 🔄 Complete Incident Lifecycle

User reports VPN problem
        ↓
Incident created
        ↓
Incident classified as Network → VPN
        ↓
Impact + Urgency evaluated
        ↓
Priority calculated
        ↓
Incident assigned to support team
        ↓
Knowledge article consulted
        ↓
Issue escalated to Level 2
        ↓
Network investigation performed
        ↓
Network configuration change required
        ↓
Emergency Change created
        ↓
Child Incident created
        ↓
Change implemented
        ↓
VPN connectivity verified
        ↓
Child Incident resolved
        ↓
Parent Incident resolved
        ↓
Knowledge Article created
        ↓
SLA completion verified
        ↓
Final validation
# 📋 Project Phases

| Phase | Name                               | Status     |
| ----- | ---------------------------------- | ---------- |
| 01    | Requirement Analysis & Planning    | ✅ Complete |
| 02    | Service & Service Offering         | ✅ Complete |
| 03    | Incident Record Creation           | ✅ Complete |
| 04    | Incident Classification & Priority | ✅ Complete |
| 05    | Knowledge Integration              | ✅ Complete |
| 06    | Reassignment & Level 2 Escalation  | ✅ Complete |
| 07    | Level 2 Investigation Tracking     | ✅ Complete |
| 08    | Emergency Change Request Creation  | ✅ Complete |
| 09    | Child Incident Creation            | ✅ Complete |
| 10    | Incident Resolution                | ✅ Complete |
| 11    | Knowledge Creation & Reuse         | ✅ Complete |
| 12    | Final Validation                   | ✅ Complete |
| 13    | Testing & SLA Validation           | ✅ Complete |
| 14    | Conclusion                         | ✅ Complete |


# 🔵 Phase 1 — Requirement Analysis & Planning

The project requirements were analyzed before implementation.

The selected business scenario was a corporate VPN connectivity issue requiring:

* Incident creation
* Classification
* Priority assessment
* Assignment
* Escalation
* Investigation
* Knowledge support
* Change coordination
* Child incident tracking
* Resolution
* SLA monitoring
* Validation

---

# 🔵 Phase 2 — Service & Service Offering

A dedicated service was configured:

**IT Incident Management Service**

A corresponding service offering was created:

**Standard IT Support**

This provides service context for incidents and allows the incident to be associated with a specific IT service offering.

---

# 🔵 Phase 3 — Incident Record Creation

A VPN connectivity incident was created in ServiceNow.

Example:

**INC0010011**

The incident included:

* Caller
* Short Description
* Description
* Service
* Service Offering
* Category
* Subcategory
* Impact
* Urgency
* Priority
* Assignment information

---

# 🔵 Phase 4 — Incident Classification & Priority

The incident was classified as:

**Category:** Network

**Subcategory:** VPN

The incident was evaluated using:

**Impact:** 2 – Medium

**Urgency:** 2 – Medium

**Priority:** 3 – Moderate

This ensures incidents are consistently categorized and prioritized.

---

# 🔵 Phase 5 — Knowledge Integration

The existing Knowledge Article:

**KB0010002 – VPN Connection Troubleshooting**

was used to support investigation.

The article provided standard troubleshooting guidance before escalation to the Network Support team.

This demonstrates Knowledge Reuse during incident resolution.

---

# 🔵 Phase 6 — Reassignment & Level 2 Escalation

The incident was escalated to:

**Assignment Group:** Network Support

**Assigned To:** network admin

Work Notes were used to document the escalation and provide context to the Level 2 team.

---

# 🔵 Phase 7 — Level 2 Investigation Tracking

The Network Support team investigated the VPN problem.

Investigation activities were documented using Work Notes.

The investigation determined that a network-level VPN gateway configuration change was required.

---

# 🔵 Phase 8 — Emergency Change Request

An Emergency Change Request was created:

**CHG00300001**

Configuration:

* Type: Emergency
* Assignment Group: Network Support
* Assigned To: network admin
* Purpose: Modify VPN gateway configuration

The change was associated with the incident through the incident documentation and resolution notes.

The change-management activity demonstrates controlled coordination between Incident Management and Change Management.

---

# 🔵 Phase 9 — Child Incident Creation

A child incident was created:

**Parent:** INC0010011

**Child:** INC0010012

The child incident was used to track the detailed Level 2 technical investigation.

The parent-child relationship provides traceability between the primary user incident and the technical investigation.

---

# 🔵 Phase 10 — Incident Resolution

The child incident was resolved after the required network configuration change was completed.

**Resolution Code:**

`Resolved by change`

Resolution notes documented:

* VPN gateway configuration change
* Emergency Change reference
* Successful connectivity verification
* Related child/parent incident information

The parent incident was then resolved.

---

# 🔵 Phase 11 — Knowledge Creation & Reuse

A new Knowledge Article was created based on the successful resolution:

**KB0010003 – Corporate VPN Gateway Configuration – Resolution Guide**

The article documents:

* Issue
* Symptoms
* Investigation
* Resolution
* Change Reference
* Verification
* Related Incidents
* Support Guidance

The article went through:

Created
   ↓
Approval Requested
   ↓
Approved
   ↓
Published


This demonstrates the full Knowledge Management lifecycle.

---

# 🔵 Phase 12 — Final Validation

The implementation was validated by checking:

### Incident

* State
* Category
* Subcategory
* Priority
* Assignment
* Resolution Information

### Knowledge

* Existing article
* New article
* Approval
* Publication

### Change

* Emergency Change
* Assignment
* Change purpose
* Incident traceability

### Parent / Child

* Parent incident
* Child incident
* Relationship
* Resolution

All major components were successfully validated.

---

# 🔵 Phase 13 — SLA & Testing Validation

Two custom SLA Definitions were configured.

## 13.1 Incident Response SLA

**Name:**

`Incident Response SLA - 30 Minutes`

**Table:**

Incident

**Duration:**

30 Minutes

**Start Condition:**

```text
State = New
```

**Stop Condition:**

```text
State = In Progress
```

---

## 13.2 Incident Resolution SLA

**Name:**

`Incident Resolution SLA - 4 Hours`

**Table:**

Incident

**Duration:**

4 Hours

**Start Condition:**

```text
State = New
```

**Stop Condition:**

```text
State = Resolved
```

---

## SLA Testing

A dedicated test incident was created:

**INC0010013**

The incident automatically received the configured Task SLAs.

The Response SLA was successfully completed after the incident moved into the appropriate response state.

The Resolution SLA was successfully completed when the incident was resolved.

### Final SLA result

Incident Response SLA – 30 Minutes
             ↓
          COMPLETED

Incident Resolution SLA – 4 Hours
             ↓
          COMPLETED


This proves that the custom SLA definitions were not only configured but also functionally tested.

---

# 🧪 Functional Testing

The following areas were tested:

* Incident creation
* Incident classification
* Impact
* Urgency
* Priority
* Assignment
* Level 2 escalation
* Work Notes
* Knowledge integration
* Emergency Change creation
* Child Incident creation
* Parent-child relationship
* Incident resolution
* Knowledge Article creation
* Knowledge Article approval
* Knowledge Article publication
* Response SLA
* Resolution SLA
* Task SLA completion
* Final validation

---

# 📊 Testing Result

| Test Area                 | Result   |
| ------------------------- | -------- |
| Incident Creation         | ✅ Passed |
| Classification            | ✅ Passed |
| Priority                  | ✅ Passed |
| Assignment                | ✅ Passed |
| L2 Escalation             | ✅ Passed |
| Knowledge Integration     | ✅ Passed |
| Emergency Change          | ✅ Passed |
| Child Incident            | ✅ Passed |
| Parent-Child Relationship | ✅ Passed |
| Incident Resolution       | ✅ Passed |
| Knowledge Creation        | ✅ Passed |
| Knowledge Approval        | ✅ Passed |
| Knowledge Publication     | ✅ Passed |
| Response SLA              | ✅ Passed |
| Resolution SLA            | ✅ Passed |
| Final Validation          | ✅ Passed |

---

# 🏆 Final Outcome

The project successfully demonstrates an end-to-end ServiceNow ITSM incident lifecycle.

The implemented solution provides structured management of an incident from:

**Creation → Classification → Priority → Assignment → Knowledge → Escalation → Investigation → Change → Child Incident → Resolution → Knowledge Creation → SLA Validation**

The project demonstrates practical understanding of enterprise IT service management processes and ServiceNow platform capabilities.

---

# 🎓 Skills Demonstrated

## ServiceNow

* Incident Management
* Service Configuration
* Service Offerings
* Incident Classification
* Impact and Urgency
* Priority Management
* Assignment Groups
* Incident Escalation
* Work Notes
* Knowledge Management
* Knowledge Approval
* Knowledge Publication
* Change Management
* Parent and Child Incidents
* Incident Resolution
* Service Level Management
* SLA Definitions
* Task SLAs
* Functional Testing

## ITSM Concepts

* Incident lifecycle management
* Incident prioritization
* Support group escalation
* Knowledge-based troubleshooting
* Change coordination
* Incident traceability
* Parent-child incident management
* SLA management
* Resolution and closure
* Knowledge reuse
* Functional validation

## Documentation & Version Control

* GitHub repository management
* Phase-based project documentation
* Technical documentation
* Implementation evidence
* Structured project organization
* Version-controlled project history

---
 📁 Repository Structure
servicenow-incident-lifecycle-automation/
│
├── Phase-01-Requirement-Analysis/
├── Phase-02-Service-and-Service-Offering/
├── Phase-03-Incident-Record-Creation/
├── Phase-04-Incident-Classification-and-Priority/
├── Phase-05-Knowledge-Integration/
├── Phase-06-Reassignment-and-Level-2-Escalation/
├── Phase-07-Level-2-Investigation-Tracking/
├── Phase-08-Emergency-Change-Request-Creation/
├── Phase-09-Child-Incident-Creation/
├── Phase-10-Incident-Resolution/
├── Phase-11-Knowledge-Creation-and-Reuse/
├── Phase-12-Final-Validation/
├── Phase-13-Testing-and-SLA-Validation/
├── Phase-14-Conclusion/
│
└── README.md

# 🌍 Real-World Applications

This solution can be applied to:

* Corporate IT Help Desks
* Banking IT Operations
* Healthcare IT Support
* Universities and Colleges
* Government IT Departments
* Cloud Service Providers
* Software Companies
* Network Operations Centers
* Enterprise Service Desks

Typical incidents could include:

* VPN connectivity failures
* Network outages
* Authentication failures
* Application failures
* Database problems
* Hardware issues
* Email problems
* Access issues
* Infrastructure incidents

---

# 🚀 Future Enhancements

The project can be extended with:

* Flow Designer automation
* Automated incident assignment
* Automated notifications
* Email-to-Incident integration
* SLA breach notifications
* ServiceNow dashboards
* Incident analytics
* Problem Management integration
* Root Cause Analysis
* Automated Knowledge recommendations
* CMDB integration
* REST API integration
* Automated Change creation
* Automated testing using ATF
* Major Incident Management
* Predictive / AI-assisted incident classification

# 🎥 Recommended Demo Flow

For a project demonstration, use this order:

1. Show Service and Service Offering
        ↓
2. Create Incident
        ↓
3. Show Classification + Priority
        ↓
4. Show Assignment
        ↓
5. Show Knowledge Article
        ↓
6. Demonstrate L2 Escalation
        ↓
7. Show Investigation Work Notes
        ↓
8. Show Emergency Change
        ↓
9. Show Child Incident
        ↓
10. Resolve Child Incident
        ↓
11. Resolve Parent Incident
        ↓
12. Show Knowledge Article
        ↓
13. Show SLA Task Records
        ↓
14. Show Completed Response SLA
        ↓
15. Show Completed Resolution SLA
        ↓
16. Final Validation


# 📌 Conclusion

**Incident Lifecycle Automation in ServiceNow** demonstrates how an enterprise IT organization can manage incidents in a structured, traceable, and SLA-driven manner.

The project integrates Incident Management with Knowledge Management, Change Management, parent-child incident tracking, and Service Level Management.

The final implementation demonstrates the complete journey from a user-reported VPN problem to investigation, escalation, controlled change, resolution, knowledge reuse, SLA completion, and validation.


## ⭐ Project Status

**Status: Completed**

**Platform: ServiceNow Developer Instance**

**Domain: IT Service Management (ITSM)**

**Primary Process: Incident Management**

**Implementation: End-to-End Incident Lifecycle Automation**
