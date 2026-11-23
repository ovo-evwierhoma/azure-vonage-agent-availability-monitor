Solution Overview
Purpose

Demonstrate automated monitoring of Vonage contact-centre agent availability using Azure Logic Apps.

How the Solution Works
Logic Apps runs every minute.
Excel Online provides simulated agent availability data.
The workflow checks the agent count.
Microsoft Outlook sends an email if the count reaches zero.
Architecture Components
Component	Function
Azure Logic Apps	Workflow automation
Excel Online	Simulated agent data
Microsoft Outlook	Email notifications
Data Source Limitation

Direct access to the organisation's Vonage agent-status API was unavailable during development. Excel Online was used to simulate the data source.

Current Status

Proof of Concept. Direct Vonage API integration and sustained-condition monitoring remain future enhancements.
