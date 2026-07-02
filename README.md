# Smart Campus Resource Booking System

## Project Overview

The Smart Campus Resource Booking System is a custom ServiceNow application developed to simplify the management of campus resources and maintenance requests. The application provides a centralized platform where users can reserve campus resources, submit maintenance requests, and track the status of their requests. It automates approval workflows, sends email notifications, and provides dashboards for monitoring resource utilization.

---

## Problem Statement

Educational institutions often manage classrooms, laboratories, seminar halls, and other campus resources manually. This process can lead to booking conflicts, inefficient resource utilization, delayed approvals, and poor maintenance tracking.

The Smart Campus Resource Booking System addresses these challenges by automating the entire booking and maintenance process using the ServiceNow platform.

---

## Objectives

- Automate campus resource booking
- Prevent duplicate bookings
- Simplify maintenance request management
- Reduce manual approval efforts
- Improve resource utilization
- Provide real-time reporting and dashboards
- Enhance user experience through automation

---

## Key Features

### Resource Management
- Create and manage campus resources
- Update resource availability
- Maintain resource details

### Booking Management
- Submit booking requests
- Approval and rejection workflow
- Booking status tracking

### Maintenance Management
- Raise maintenance requests
- Track maintenance progress
- Notify resource managers

### Automation
- Flow Designer workflows
- Business Rules
- Client Scripts
- UI Policies
- Email Notifications

### Reporting
- Resource utilization reports
- Booking status reports
- Dashboard visualization

---

## Technologies Used

- ServiceNow App Engine Studio
- Flow Designer
- Business Rules
- Client Scripts
- UI Policies
- Email Notifications
- Reports
- Dashboards
- Update Sets

---

## Database Design

The application consists of three custom tables:

### Resource
Stores information about campus resources.

Fields include:
- Resource Name
- Resource Type
- Building
- Floor
- Capacity
- Status
- Description

### Booking

Stores booking requests.

Fields include:
- Booking Number
- Resource
- Requested By
- Booking Date
- Start Time
- End Time
- Purpose
- Status
- Rejection Reason

### Maintenance Request

Stores maintenance requests.

Fields include:
- Resource
- Issue Title
- Description
- Priority
- Assigned To
- Status

---

## Workflow

1. User submits a booking request.
2. Booking request is validated.
3. Business Rules prevent duplicate bookings.
4. Administrator reviews the request.
5. Booking is approved or rejected.
6. Email notification is sent.
7. Reports and dashboards are updated automatically.

---

## Business Rules

- Prevent duplicate resource bookings.
- Validate booking information.
- Ensure data consistency.

---

## Client Scripts

- Validate start and end times.
- Display messages based on user input.
- Improve user experience through client-side validation.

---

## UI Policies

- Make rejection reason mandatory when booking is rejected.
- Dynamically control field visibility and mandatory conditions.

---

## Flow Designer

Automates:

- Maintenance request notification
- Email notifications
- Workflow execution
- Approval processes

---

## Reports and Dashboard

The application provides:

- Booking Summary
- Resource Availability
- Booking Status Report
- Maintenance Report
- Dashboard with graphical visualization

---

## Future Enhancements

- Mobile application integration
- Calendar synchronization
- QR Code-based resource check-in
- AI-powered booking recommendations
- Real-time availability tracking

---

## Benefits

- Eliminates manual booking conflicts
- Improves operational efficiency
- Reduces paperwork
- Provides centralized resource management
- Enhances transparency
- Supports data-driven decision making

---

## Author

**Thammineni Venkata Sravanthi**

B.Tech – Computer Science and Engineering

ServiceNow Certified System Administrator (CSA)
