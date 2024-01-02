# VacationTimeSys
The Vacation System concept is featured in the third edition of the Object Oriented Analysis And Design textbook, offering insights into the design and functionality of the system for tracking employee leave, managing time-off requests, and related processes.
## Table of Contents 
- [System Features](#system-features)
- [List of Actors](#list-of-actors)
- [System Features](#system-features)
- [List of Actors](#list-of-actors)
- [Use Cases](#use-cases)
  - [Manage Time](#manage-time)
    - [Request State Diagram](#request-state-diagram)
    - [Manage Time Flow Diagram](#manage-time-flow-diagram)
    - [Manage Time Sequence Diagram](#manage-time-sequence-diagram)
    - [Manage Time Pseudo Code](#manage-time-pseudo-code)
  - [Cancel Request](#cancel-request)
     - [Cancel Request Flow Diagram](#cancel-request-flow-diagram)
     - [Cancel Request Sequence Diagram](#cancel-request-sequence-diagram)
  - [Edit Request Use Case Details](#edit-request-use-case-details)
    - [Edit Request Flow Diagram](#edit-request-flow-diagram)
    - [Edit Request Sequence Diagram](#edit-request-sequence-diagram)
- [Database Design](#database-design)


## System Features

**Mission:** The goal of the VTS is to empower individual employees to oversee their leave without the need for an in-depth understanding of company policies.


### Functional Features:

- **Authenticate users internally:**
  - Implement internal user authentication for secure access.

- **Show the number of available vacation days:**
  - Provide users with real-time information on their remaining vacation days.

- **Present a calendar spanning 6 months before and 18 months after:**
  - Display an interactive calendar to facilitate effective leave planning.

- **Showcase historical requests and their current status:**
  - Maintain a record of past requests, including their approval status.

- **Implement a workflow for manager approvals:**
  - Streamline the process of obtaining managerial approval for leave requests.

- **Utilize an email notification mechanism:**
  - Keep users informed through email notifications for request updates.

- **Allow overrides by HR and system admin with logging functionality:**
  - Enable HR and system administrators to intervene when necessary, with detailed logging for accountability.
 
### Non-Functional:
- ease of use
- record all activity logs
- performance

### Constraints
- The utilization of current hardware and middleware is mandatory for the system.
- Integration with the HR department's legacy systems is required for accessing and updating employee information.
- A web service interface must be supplied to enable other internal systems to retrieve summaries of vacation requests.
    
## List of Actors
- Employee
- Manager
- HR Clerk
- System Admin

## Use Cases
- Manage time
- Withdraw Request
- Cancel Approved Request
  
## Database Design







  

