# Documentation
When nearing the end of your shifts you have to think about handing the issue over to someone on the next support shift. You'll likely log into the support ticket system and begin making notes about what you have done to troubleshoot the issue so far. Since we cannot be on shift 24/7/365, your documentation of your steps will allow the next shift to pick up where you left off and continue to work toward a solution.

## Learning Outcomes:
As you study this lesson, answer the following:
- What is an SOP and how is it different from a policy?
- How do ticketing systems assist in documentation of issues?
- How are support tickets prioritized?
- What are the characteristics of good documentation?

## A+ Core 2 Objectives:
- 4.1: Given a scenario, implement best practices associated with documentation and support systems information management.
- 4.6: Explain the importance of prohibited content/activity and privacy, licensing, and policy concepts. (Acceptable Use Policy)

# Standard Operating Procedure
Employees must understand how to use computers and networked services securely and safely and be aware of their responsibilities. To support this, the organization needs to create written policies and procedures to help staff understand and fulfill their tasks and follow best practices:
- A policy is an overall statement of intent
- A **Standard Operating Procedure (SOP)** is a step-by-step list of the actions that must be completed for any given task to comply with policy. Most IT procedures should be governed by SOPs
- **Guidelines** are for areas of policy where there are no procedures, either because the situation has not been fully assessed or because the decision-making process is too complex and subject to variables to be able to capture it in an SOP. Guidelines may also describe circumstances where it is appropriate to deviate from a specified procedure

Typical examples of SOPs are as follows:
- Procedures for custom installation of software packages, such as verifying system requirements, validating download/installation source, confirming license validity, adding the software to change control/monitoring processes, and developing support/training documentation
- New-user setup checklist as part of the on-boarding process for new employees and employees changing job roles. Typical tasks include identification/enrollment with secure credentials, allocation of devices, and allocation of permissions/assignment to security groups
- End-user termination checklist as part of the off-boarding process for employees who are retiring, changing job roles, or have been fired. Typical tasks include returning and sanitizing devices, releasing software licenses, and disabling account permissions/access

# Service Level Agreements
**Service Level Agreements (SLAs)** define the level of service requirements from an internal department or external, third-party vendor. Examples of services that most likely have an SLA in place include:
- Internal departments of the company that are providing resources to one another such as access to hardware resources; a company's maintenance department may also have a SLA that details how they are to provide support to the other departments within the company when it comes to building maintenance, etc.
- External agreements will normally be provided by the ISP as to the metrics of throughput they will provide a company for the internet connection; a cloud service provider will also have a SLA in place that details the service delivery metrics of the organizations cloud resources. 

## The Rule of Nines
SLAs normally include a description of the service being provided, along with the metrics that are used to measure the level of service being provided. The Rule of Nines is a very popular metric used to dictate the expected up time, when the service is available, and what is not considered down time (service not available) for the service. For example, the **Rule of 4 Nines** means the service or system will be available 99.99% of the time. This allows for a maximum of 52 minutes of downtime per year. Whereas a service with the **Rule of 11 Nines** means the service will be up 99.999999999% of the time, would only be allowed 315.58 microseconds of downtime.

The Rule of Nines can also be used to calculate the durability of file and data storage services. For example, the Rule of 11 Nines for durability means that even with 1 billion objects in storage, you would be able to go 100 years without losing a single object.

| # of Nines | Uptime | Downtime per Year | Downtime per Month | Downtime per Day |
|:---:|:---|:---:|:---:|:---:|
|  1 Nine  | 90%            |  36.53 days         |  73.05 hours        |   2.4 hours         |
|  2 Nines | 99%            |   3.65 days         |   7.31 hours        |  14.4 minutes       |
|  3 Nines | 99.9%          |   8.77 hours        |  43.84 minutes      |   1.44 minutes      |
|  4 Nines | 99.99%         |  52.60 minutes      |   4.38 minutes      |   8.64 seconds      |
|  5 Nines | 99.999%        |   5.26 minutes      |  26.30 seconds      | 864.00 milliseconds |
|  6 Nines | 99.9999%       |  31.56 seconds      |   2.63 seconds      |  86.40 milliseconds |
|  7 Nines | 99.99999%      |   3.16 seconds      | 262.98 milliseconds |   8.64 milliseconds |
|  8 Nines | 99.999999%     | 315.58 milliseconds |  26.30 milliseconds | 864.00 microseconds |
|  9 Nines | 99.9999999%    |  31.56 milliseconds |   2.63 milliseconds |  86.40 microseconds |
| 10 Nines | 99.99999999%   |   3.16 milliseconds | 262.80 microseconds |   8.64 microseconds |
| 11 Nines | 99.999999999%  | 315.68 microseconds |  26.28 microseconds | 864.00 nanoseconds  |
| 12 Nines | 99.9999999999% |  31.56 microseconds |   2.63 microseconds |  86.40 nanoseconds  |

Should the delivery metrics not be met by the provider, the SLA will detail the recourse process to make a complaint against the service provider. It may also detail the amount of money the customer may be able to recover since the service is not meeting the requirements of the SLA.

# Incident and Ticketing Systems
A **ticketing system** manages requests, incidents, and problems. Ticketing systems can be used to support internal end-users and external customers.

The general process of ticket management is as follows:
1. A user contacts the help desk, by phone or email or directly via the ticketing system. A unique job ticket ID is generated, and an agent is assigned to the ticket. The ticket will also need to capture some basic details:
   - User Information: The user's name, contact details, and other relevant information, such as department or job role. It may be possible to link the ticket to an employee database or **Customer Relation Management (CRM)** database
   - Device Information: If relevant, the ticket should record information about the user's device. It might be possible to link the relevant inventory record via a service tag or asset ID
2. The user supplies a description of the issue. An again might then ask clarifying questions to ensure an accurate initial description
3. The agent categorizes the support case, assesses how urgent or severe it is, and determines how long it will take to fix
4. The agent may take the user through initial troubleshooting steps. If these do not work, the ticket may be escalated to desk-side support or a senior technician

# Categories and Severity
## Categories
**Categories** and **subcategories** group related tickets together. This is useful for assigning tickets to the relevant support section or technician and for reporting and analysis.

Service management standards distinguish between the following basic ticket types:
- **Requests**: Provision things that the IT department has a SOP for, such as setting up new user accounts, purchasing new hardware or software, deploying a web server, etc. Complex requests that aren't covered by existing procedures are better treated as projects rather than handled via the ticketing system
- **Incidents**: Related to any errors or unexpected situations faced by end-users or customers. Incidents may be further categorized by severity (impact and urgency), such as minor, major, and critical.
- **Problems**: Causes of incidents and will probably require analysis and service reconfiguration to solve. This type of ticket is likely to be generated internally when the help desk starts to receive many incidents of the same type

Using these types as top-level categories for an end-user facing system is not always practical, however. End-users are not likely to know how to distinguish incidents from problems, for example. Devising categories that are narrow enough to be useful but not so numerous as to be confusing or to slow down the whole ticketing process is a challenging task.

One strategy is for a few simple, top-level categories that end-users can self-select, such as New Device Request, New App Request, Employee Onboarding, Employee Offboarding, Help/Support, and Security Incident. Then, when assigned to the ticket, the support technician can select from a longer list of additional categories and subcategories to help group related tickets for reporting and analysis purposes. Alternatively, or to supplement categories, the system might support adding standard keyword tags to each ticket. A keyword system is more flexible but does depend on each technician tagging the ticket appropriately.

## Severity
A **severity level** is a way for classifying tickets into a priority order. As with categories, these should not be overly complex. Three severity levels based on impact might be considered sufficient:
- **Critical**: Incidents that have a widespread affect on end-users or involve potential or actual data breach
- **Major**: Incidents that affect a limited group of end users or involve a suspected security violation
- **Minor**: Incidents that are not having a significant effect on end users

More discrete levels may be required if the system must prioritize hundreds or thousands of minor incidents per week. A more sophisticated system that measures both impact and urgency might be required. Severity levels can also drive a notification system to make senior technicians and managers immediately aware of major and critical incidents as they arise.

# Ticket Management

# Support Documentation and Knowledge Base Articles

# Lessons Learned

# Clear Written Communication

# Knowledge Base

# Policy Documentation
