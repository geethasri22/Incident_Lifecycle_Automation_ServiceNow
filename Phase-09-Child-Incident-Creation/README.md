# Phase 9 — Child Incident Creation

## 📌 Overview

This phase demonstrates the creation and relationship of a Child Incident with the main Parent Incident.

During the Incident lifecycle, a technical issue may require separate tracking while still being related to the original user-reported problem.

To support this requirement, a Child Incident is created under the Parent Incident.

For this project:

- Parent Incident: INC0010011
- Child Incident: INC0010012

The Parent-Child relationship allows the technical investigation to be tracked separately while maintaining traceability to the original Incident.

---

## 🎯 Objective

The objectives of this phase are:

- Create a Child Incident.
- Associate the Child Incident with the Parent Incident.
- Maintain traceability between related Incidents.
- Track technical work separately.
- Demonstrate Parent-Child Incident relationships.
- Verify the relationship from the Incident records.

---

# 🧑‍💻 Business Scenario

The primary Incident represents a corporate VPN connectivity problem.

During the investigation, additional technical work needs to be tracked separately.

Instead of placing every activity into the original Incident, a Child Incident is created.

The Child Incident provides a separate record for the related technical investigation while remaining connected to the Parent Incident.

---

# 🔗 Parent Incident

The main Incident is:

**INC0010011**

This is the Parent Incident representing the original VPN connectivity issue.

The Parent Incident remains the primary record for the overall user-reported problem.

---

# 👶 Child Incident

The related Child Incident is:

**INC0010012**

The Child Incident is created to separately track the associated technical work.

---

# 🔄 Parent-Child Structure

The relationship is:

Parent Incident
INC0010011
     │
     │
     └───────────────┐
                     ↓
              Child Incident
                 INC0010012
