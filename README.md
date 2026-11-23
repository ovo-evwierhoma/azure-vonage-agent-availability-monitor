<h1 align="center">Azure Vonage Agent Availability Monitoring</h1>

<p align="center">
<img src="https://img.shields.io/badge/Microsoft-Azure-0078D4?logo=microsoftazure&logoColor=white" />
<img src="https://img.shields.io/badge/Azure-Logic%20Apps-0078D4" />
<img src="https://img.shields.io/badge/Status-Proof%20of%20Concept-green" />
</p>

<h2>Project Overview</h2>

<p>A proof of concept demonstrating automated monitoring of Vonage contact-centre agent availability using Microsoft Azure Logic Apps.</p>

<h2>Business Problem</h2>

<p>Leadership needs visibility when agent availability reaches a critical level to support timely operational decisions.</p>

<h2>Solution</h2>

<p>The Azure Logic App automates the following process:</p>

<ol>
<li>Runs automatically every minute.</li>
<li>Retrieves simulated agent availability data from Excel Online.</li>
<li>Evaluates the available agent count.</li>
<li>Sends an automated email alert through Microsoft Outlook when the count reaches zero.</li>
</ol>

<h2>Technology Used</h2>

<ul>
<li>Microsoft Azure Logic Apps</li>
<li>Microsoft Excel Online</li>
<li>Microsoft 365 Outlook</li>
<li>JSON Workflow Definition</li>
</ul>

<h2>Data Source</h2>

<p>Direct access to the organisation's Vonage agent-status API was unavailable during development. Excel Online was therefore used to simulate agent availability data and demonstrate the intended automation.</p>

<h2>Future Improvements</h2>

<ul>
<li>Direct integration with the Vonage API.</li>
<li>Configurable agent availability thresholds.</li>
<li>Monitoring conditions sustained for more than one minute.</li>
<li>Alert deduplication to prevent repeated notifications.</li>
</ul>

<h2>Security</h2>

<p>All sensitive information, including subscription IDs, connection details, email addresses and credentials, must be removed or replaced with placeholders before publication.</p>

<hr />

<p align="center"><strong>Project Category:</strong> Cloud Engineering | Azure Automation | Operational Monitoring</p>

<p align="center">Built with Microsoft Azure</p>
