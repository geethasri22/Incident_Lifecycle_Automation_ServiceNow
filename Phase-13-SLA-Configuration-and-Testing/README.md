# Phase 13 — SLA Configuration & Testing

## 📌 Overview

This phase introduces Service Level Agreement (SLA) management into the ServiceNow Incident Management workflow.

SLAs define measurable time targets for responding to and resolving Incidents.

Two SLAs were configured for this project:

1. Incident Response SLA — 30 Minutes
2. Incident Resolution SLA — 4 Hours

A dedicated test Incident is used to verify that the configured SLAs are attached to the Incident and progress according to their defined start and stop conditions.

---

## 🎯 Objectives

The objectives of this phase are:

- Configure an Incident Response SLA.
- Configure an Incident Resolution SLA.
- Define SLA time targets.
- Configure SLA start conditions.
- Configure SLA stop conditions.
- Test SLA attachment to an Incident.
- Verify SLA progress.
- Verify completed SLA records.
- Demonstrate measurable Incident service levels.

---

# ⏱️ SLA 1 — Incident Response SLA

The first SLA measures how quickly the support team responds to a newly created Incident.

### Configuration

**Name:**

Incident Response SLA

**Target:**

30 Minutes

### Start Condition

The SLA starts when:
State = New
