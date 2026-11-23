Azure Vonage Agent Availability Monitoring & Alerting
Project Overview

This project is a Proof of Concept (PoC) demonstrating how Microsoft Azure Logic Apps can automate agent availability monitoring and email alerting within a Vonage contact-centre environment.

The solution uses Excel Online as a simulated data source representing Vonage agent availability information.

Direct access to the organisation's Vonage agent-status API was not available during development. Excel Online was therefore used to simulate the agent data and demonstrate the intended automation workflow.

Business Problem

Contact-centre operations depend on having sufficient agents available to manage incoming customer interactions.

When agent availability reaches a critical level, operational leadership needs timely notification to support decision-making and operational response.

Manually monitoring agent availability can introduce delays and requires ongoing human attention.

This project explores how cloud automation can improve operational visibility through scheduled monitoring and automated email notifications.

Solution Architecture

The proof of concept uses three main components:

Azure Logic Apps: Orchestrates the monitoring workflow and executes scheduled checks.
Excel Online: Simulates the Vonage agent availability data source.
Microsoft 365 Outlook: Sends automated email notifications when the configured condition is met.
How It Works
Azure Logic Apps runs on a scheduled recurrence every minute.
The workflow retrieves agent availability information from Excel Online.
A conditional action evaluates the agent count.
If the configured condition is met, an automated email notification is sent through Outlook.

Current implementation: The exported workflow checks whether the agent count equals zero.

The intended business requirement of detecting one or fewer available agents for more than one minute remains subject to implementation and validation.

Technology Stack
Microsoft Azure
Azure Logic Apps
Microsoft Excel Online
Microsoft 365 Outlook
JSON
Workflow automation
Project Status

Proof of Concept – simulated agent data source.

Future enhancement: Integrate directly with the Vonage agent-status API when the required API access becomes available.

Security

Sensitive information has been removed or replaced with placeholders before publication.

No passwords, access tokens, API keys, personal email addresses, subscription identifiers or internal connection details should be included in this repository.

Learning Outcomes
Azure Logic Apps workflow orchestration.
Scheduled cloud automation.
Excel Online integration.
Conditional workflow execution.
Microsoft 365 email integration.
Operational monitoring and alerting.
Cloud project documentation and security awareness.
Future Improvements
Direct Vonage API integration.
Configurable agent availability thresholds.
Sustained-condition monitoring.
Alert deduplication.
Improved error handling and monitoring.

Project Category: Cloud Engineering | Azure Automation | Operational Monitoring
