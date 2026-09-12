# Phase 1 — Requirement Analysis & Project Planning

## 📌 Overview

This phase establishes the business problem, project objectives, functional requirements, incident lifecycle, and implementation plan for the ServiceNow Incident Lifecycle Automation project.

The project is designed around a realistic enterprise IT support scenario involving a corporate VPN connectivity issue.

The objective is to demonstrate how ServiceNow can manage an IT incident from initial reporting through investigation, escalation, change coordination, resolution, knowledge creation, SLA monitoring, and final validation.


## 🎯 Business Scenario

An employee is unable to connect to the organization's corporate VPN.

The issue is initially reported to the IT Service Desk.

First-level support performs standard troubleshooting using the existing Knowledge Base. When the issue cannot be resolved at Level 1, the incident is escalated to the Network Support team for further investigation.

The investigation identifies a VPN gateway configuration issue requiring a network-level change.

An Emergency Change Request is created to implement the required configuration change.

A Child Incident is also used to track the detailed technical investigation while maintaining a relationship with the Parent Incident.

After the change is successfully implemented and connectivity is verified, the incident is resolved.

The resolution is then documented in a new Knowledge Article so that the same issue can be handled more efficiently in the future.

---

## 🎯 Project Objectives

The main objectives of the project are:

- Implement a complete Incident Management lifecycle.
- Configure a Service and Service Offering.
- Create and classify incidents.
- Configure Impact, Urgency, and Priority.
- Assign incidents to appropriate support teams.
- Demonstrate Level 2 escalation.
- Document investigation using Work Notes.
- Use existing Knowledge Articles for troubleshooting.
- Create and manage Emergency Change Requests.
- Implement Parent and Child Incident relationships.
- Resolve incidents using structured resolution information.
- Create, approve, and publish Knowledge Articles.
- Configure Incident Response and Resolution SLAs.
- Validate SLA execution using Task SLA records.
- Perform end-to-end functional testing.

## 🔄 Planned Incident Lifecycle

The planned lifecycle for the project is:


User Reports Incident
        ↓
Incident Creation
        ↓
Service & Service Offering
        ↓
Classification
        ↓
Impact + Urgency
        ↓
Priority Determination
        ↓
Assignment
        ↓
Knowledge-Based Troubleshooting
        ↓
Level 2 Escalation
        ↓
Technical Investigation
        ↓
Emergency Change
        ↓
Child Incident
        ↓
Change Implementation
        ↓
Verification
        ↓
Incident Resolution
        ↓
Knowledge Article Creation
        ↓
SLA Validation
        ↓
Final Testing
