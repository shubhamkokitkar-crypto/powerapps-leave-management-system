# Leave Management System

A professional **Leave Management System** built using **Microsoft Power Platform** to manage employee leave requests, approvals, leave calendars, reports, organization settings, and administration.

> **Portfolio Note:** This repository is a sanitized portfolio/demo representation. No company-confidential data, credentials, production records, or internal information should be included.

---

## 📌 Project Overview

The Leave Management System provides a centralized solution for employees, managers, HR, and administrators to manage the complete leave lifecycle.

### Main Objectives

- Submit and manage leave requests
- Provide manager approval workflows
- Track leave request status
- Display approved leaves in a calendar
- Provide reports and analytics
- Manage organization settings
- Support role-based administration
- Manage attachments related to leave requests
- Provide search, filtering, and pagination
- Automate notifications and approvals

---

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| **Power Apps** | Canvas application and user interface |
| **Power Automate** | Approval workflows and automation |
| **SharePoint** | Data storage and list management |
| **Power BI** | Reports and analytics |
| **Power Fx** | Application logic and formulas |
| **Microsoft 365** | Platform integration |

---

## 🏗️ Application Architecture

```text
                     ┌─────────────────────┐
                     │      Employee       │
                     └──────────┬──────────┘
                                │
                                ▼
                     ┌─────────────────────┐
                     │     Power Apps      │
                     │    Canvas App       │
                     └──────────┬──────────┘
                                │
               ┌────────────────┼────────────────┐
               │                │                │
               ▼                ▼                ▼
        ┌─────────────┐  ┌──────────────┐  ┌─────────────┐
        │ SharePoint  │  │ Power        │  │ Power BI    │
        │ Lists       │  │ Automate     │  │ Reports     │
        └─────────────┘  └──────┬───────┘  └─────────────┘
                                 │
                                 ▼
                         ┌────────────────┐
                         │ Manager / HR   │
                         │ Approval       │
                         └────────────────┘
