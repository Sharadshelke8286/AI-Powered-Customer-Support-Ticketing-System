# AI-Powered Customer Support Ticketing System

## Project Overview

The **AI-Powered Customer Support Ticketing System** is a Salesforce-based solution designed to streamline and automate customer support operations. The system centralizes customer data, manages support requests efficiently, and improves service quality through automation and intelligent case handling.

This project demonstrates how **Salesforce Admin tools, custom objects, record-triggered flows, and reporting capabilities** can be used to build a scalable customer support management system.

The system automatically classifies support cases, assigns priorities, calculates SLA deadlines, and provides suggested actions to support agents, helping reduce manual effort and improve resolution efficiency.

---

## Problem Statement

Customer support teams often face challenges such as:

- Manual case classification
- Delays in assigning case priority
- Difficulty tracking Service Level Agreements (SLAs)
- Limited visibility into support performance
- Lack of centralized support management

These issues can lead to slower response times and poor customer experience.

---

## Solution

The **AI-Powered CST System** solves these problems by:

- Automating **case classification**
- Automatically assigning **priority levels**
- Tracking **SLA deadlines**
- Providing **agent assistance with suggested actions**
- Capturing **agent feedback for continuous improvement**
- Enabling **performance monitoring through reports**

The solution is built entirely using **Salesforce standard configuration and automation tools**.

---

## Key Features

- Customer Account and Contact Management
- Automated Case Classification
- Priority Assignment Automation
- SLA Tracking and Deadline Calculation
- Agent Assistance via Suggested Actions
- AI Feedback Collection Mechanism
- Role-Based Access Control
- Reports and Monitoring Dashboard
- Scalable and Maintainable System Design

---

## Technologies Used

- Salesforce Developer Org
- Salesforce Lightning Experience
- Standard Objects (Account, Contact, Case)
- Custom Objects
- Record-Triggered Flows
- Profiles and Permission Sets
- Reports and Dashboards

---

## System Architecture

The system is structured using both **standard Salesforce objects** and **custom objects**.

### Standard Objects

- **Account** – Stores company or organization details
- **Contact** – Stores customer information
- **Case** – Manages customer support tickets

### Custom Objects

- **Support Category**
  - Defines different types of support issues

- **SLA Policy**
  - Stores service-level agreement rules for case resolution

- **AI Feedback**
  - Captures agent feedback on suggested system actions

---

## Automation Logic

Automation is implemented using **Record-Triggered Flows**.

### Case Classification Flow
Automatically categorizes cases based on issue details.

### Priority Assignment
Determines case priority depending on urgency and issue type.

### SLA Tracking Flow
Automatically calculates SLA due dates when cases are created.

### Agent Assistance
Displays suggested actions on case records to guide support agents.

---

## Security Model

The system uses **role-based access control** to manage user permissions.

### Profiles

- System Administrator
- Support Agent
- Support Manager

### Permission Sets

- AI Feature Access
- Report Access

This ensures users only access the data and features relevant to their responsibilities.

---

## Reporting and Monitoring

Reports and dashboards are used to monitor system performance.

Key reports include:

- Case Status Report
- Case Volume Report
- SLA Compliance Report
- Agent Performance Report

These reports help managers track support efficiency and identify improvement areas.

---

## Project Structure

```
AI-Powered-CST-System
│
├── Step-01-Project-Setup
├── Step-02-Custom-Object
├── Step-03-Fields
├── Step-04-Validation-Rules
├── Step-05-Email-Alerts
├── Step-06-Flows
├── Step-07-Agentforce-AI
├── Step-08-Tabs
├── Step-09-Lightning-App
├── Step-10-Reports
├── Step-11-Profiles
├── Step-12-Permission-Sets
├── Step-13-User-Creation
├── Step-14-Testing
├── Step-15-Deployment
├── Step-16-Documentation
├── Step-17-Maintenance-Monitoring-Troubleshooting
├── Step-18-Documentation-Guidelines
├── Step-19-Demo-Video-Flow
└── Step-20-Project-Conclusion
```

---

## Demo Video

A demonstration video of the project explains:

- App overview
- Case creation and automation
- Flow logic
- Agent assistance
- Security setup
- Reports and monitoring

*(Add your demo video link here)*

Example:

```
Demo Video: https://your-video-link
```

---

## Testing

The system was tested to ensure:

- Cases trigger automation correctly
- Priority assignment works properly
- SLA calculations are accurate
- User access permissions are correctly applied
- Reports display accurate data

---

## Maintenance and Monitoring

Regular maintenance includes:

- Reviewing automation flows
- Updating picklist values
- Monitoring system performance
- Auditing user access permissions
- Reviewing agent feedback data

This ensures the system remains stable and aligned with business requirements.

---

## Learning Outcomes

This project provided hands-on experience with:

- Salesforce Administration
- Data Modeling
- Process Automation with Flows
- Role-Based Security Configuration
- Reporting and Dashboard Creation
- System Monitoring and Maintenance

---

## Conclusion

The **AI-Powered Customer Support Ticketing System** demonstrates how Salesforce can be used to build a scalable and automated support management solution.

By combining **automation, structured data management, security controls, and reporting**, the system improves support efficiency, ensures SLA compliance, and supports continuous improvement through feedback.

This project showcases practical Salesforce implementation skills and serves as a strong example of a real-world support automation solution.

---

## Author

**Sharad Shelke**

Salesforce Administrator Project

GitHub Repository for Learning and Demonstration
