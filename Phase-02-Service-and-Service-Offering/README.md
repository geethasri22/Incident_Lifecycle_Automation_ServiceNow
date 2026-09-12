# Phase 2 — Service and Service Offering Configuration

## 📌 Overview

This phase focuses on creating and configuring the Service and Service Offering required for the Incident Management workflow.

A Service provides the overall business or technical service context, while a Service Offering represents a specific way in which that service is provided to users.

For this project, a dedicated IT incident management service and a standard IT support offering were configured in ServiceNow.

---

## 🎯 Objective

The objectives of this phase are:

- Create a dedicated Service in ServiceNow.
- Configure the Service with appropriate lifecycle information.
- Create a Service Offering associated with the Service.
- Establish the parent-child relationship between the Service and Service Offering.
- Prepare the service structure for use during Incident Management.

---

# 🏢 Service Configuration

## Service Name

**IT Incident Management Service**

### Service Details

| Field | Configuration |
|---|---|
| Service Name | IT Incident Management Service |
| Type | Business Service |
| Phase | Pipeline |
| Status | Requirements |

The Service acts as the main service context for the Incident Management process.

---

## 📸 Screenshot — Service Created

![IT Incident Management Service](screenshots/01-service-created.png)

This screenshot shows the Service record created in ServiceNow.

---

## 📸 Screenshot — Service Details

![Service Details](screenshots/02-service-details.png)

The screenshot demonstrates the configured service information, including the service type, phase, and status.

---

# 🛠️ Service Offering Configuration

A Service Offering was created under the main service.

## Service Offering Name

**Standard IT Support**

The Service Offering represents the standard IT support capability provided through the Incident Management Service.

### Configuration

| Field | Configuration |
|---|---|
| Service Offering | Standard IT Support |
| Parent | IT Incident Management Service |

---

## 📸 Screenshot — Service Offering

![Standard IT Support](screenshots/03-service-offering-created.png)

This screenshot shows the Standard IT Support Service Offering created in ServiceNow.

---

## 📸 Screenshot — Parent Service Relationship

![Service Offering Parent](screenshots/04-service-offering-parent.png)

The screenshot demonstrates that:

**Standard IT Support**

is associated with:

**IT Incident Management Service**

through the Parent field.


# 🔗 Service Structure

The configuration establishes the following hierarchy:
IT Incident Management Service
            │
            └── Standard IT Support
                 Service Offering
