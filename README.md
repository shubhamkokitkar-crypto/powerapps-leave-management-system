# Leave Management System

A business-oriented **Leave Management System** developed using **Microsoft Power Platform** to manage employee leave requests, approvals, tracking, calendars, administration, and reporting.

> **Portfolio Project:** This repository is a sanitized portfolio/demo representation and does not contain company-confidential data, credentials, production records, or internal configuration.

---

## 📌 Project Overview

The Leave Management System provides a centralized platform for employees, managers, and administrators to manage the complete employee leave process.

The application helps organizations reduce manual work by providing:

- Employee leave submission
- Automated approval workflow
- Leave status tracking
- Manager approval and rejection
- Leave calendar
- Dashboard and reports
- Organization configuration
- User and role management
- Security settings
- Backup and restore management

---

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| **Power Apps** | Canvas application and user interface |
| **Power Automate** | Leave approval and notification automation |
| **SharePoint** | Data storage and attachments |
| **Power BI** | Reporting and analytics |
| **Power Fx** | Application logic, validation, filtering, and calculations |
| **Microsoft 365** | Business application environment |

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
                    │   Canvas Application│
                    └──────────┬──────────┘
                               │
                ┌──────────────┴──────────────┐
                │                             │
                ▼                             ▼
       ┌─────────────────┐          ┌─────────────────┐
       │    SharePoint   │          │  Power Automate │
       │   Data Storage  │◄────────►│ Approval Workflow│
       └────────┬────────┘          └────────┬────────┘
                │                            │
                │                            ▼
                │                   ┌─────────────────┐
                │                   │ Manager Approval│
                │                   └─────────────────┘
                │
                ▼
       ┌─────────────────┐
       │     Power BI    │
       │ Reports & Charts│
       └─────────────────┘
