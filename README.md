# Automatic Leave Request System

An automated leave request workflow built using **Power Automate**, **SharePoint**, and **Outlook** to streamline the leave approval process.

---

## Project Overview

This system automates employee leave requests by routing approvals through supervisor while automatically updating internal systems.

The workflow reduces manual processing and improves communication between employees, supervisors, and workforce.

---

## Workflow Diagram

![Workflow](AutomaticLeaveRequestDiagram.png)

---

## How the System Works

1. Employee submits leave request via SharePoint.
2. Supervisor reviews the request.
3. Supervisor approves or rejects the request thru Microsoft Teams Approval.
4. If approved:
   - Workforce receives email alert indicating that the leave has been approved including the employee. 
   - Leave is logged in the Sharepoint team calendar.
   - Data is stored in the internal database (Microsoft Excel).
5. If rejected:
   - Employee receives rejection email notification.

---

## Technologies Used

- Power Automate
- SharePoint
- Outlook
- Microsoft Teams Approval

---

## Key Features

- Automated approval workflow
- Email notifications
- Leave tracking
- Calendar integration
- Centralized leave database

---

## Business Impact

This automation improves efficiency by:

- Reducing manual approval processes
- Ensuring faster leave approvals
- Automatically notifying relevant teams
- Keeping accurate leave records

---

## Author

Michael John Orbino
