# VacationTimeSys

The Vacation System concept is featured in the third edition of the Object Oriented Analysis And Design textbook, offering insights into the design and functionality of the system for tracking employee leave, managing time-off requests, and related processes.

## Scope

- Build a new system for vacation requests, including related workflow
- Integrate with the HR system using APIs

## Table of Contents

- [System Features](#system-features)
- [List of Actors](#list-of-actors)
- [Use Cases](#use-cases)
  - [Manage Time](#manage-time)
    - [Sequence Diagram per Emp and Manager](#sequence-diagram-per-emp-and-manager)
    - [Sequence Diagram per Emp](#sequence-diagram-per-emp)
    - [Sequence Diagram per Manager](#sequence-diagram-per-manager)
    - [Request State Diagram](#request-state-diagram)
    - [Flow Diagram](#flow-diagram)
    - [Pseudo Code](#pseudo-code)
  - [Cancel Request](#cancel-request)
    - [Flow Diagram](#flow-diagram-cancel-request)
    - [Sequence Diagram](#sequence-diagram-cancel-request)
  - [Edit Request](#edit-request)
    - [Flow Diagram](#flow-diagram-edit-request)
    - [Sequence Diagram](#sequence-diagram-edit-request)
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

- Ease of use
- Record all activity logs
- Performance

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

- **Manage Time**
  - [Sequence Diagram per Emp and Manager](#sequence-diagram-per-emp-and-manager)
    ![Sequence Diagram per Emp and Manager](https://github.com/tawfik-ops/VacationTimeSys/assets/83514768/bad42ef0-6939-42a0-8c6d-f110f45acbf0)
  - [Sequence Diagram per Emp](#sequence-diagram-per-emp)
    ![Sequence Diagram per Emp](https://github.com/tawfik-ops/VacationTimeSys/assets/83514768/86430546-e549-4c7b-abd1-9b3434a75e19)
  - [Sequence Diagram per Manager](#sequence-diagram-per-manager)
    ![Sequence Diagram per Manager](https://github.com/tawfik-ops/VacationTimeSys/assets/83514768/c36d177e-c339-43b5-b31e-9a60ecd8383e)
- **Withdraw Request**
- **Cancel Approved Request**

## Architecture Database Design

- **Structure Design**
  ![Integration](https://github.com/tawfik-ops/VacationTimeSys/assets/83514768/7020201e-cd05-4c1e-ba34-8098dc5fbc6f)
- **Data Base Design**

Fix the issue that is related by navigating from content to the rest of the readme file content.
