<h1>Solution Overview</h1>

<h2>1. Project Purpose</h2>

<p>This project demonstrates a Proof of Concept (PoC) for automated monitoring of Vonage contact-centre agent availability using Microsoft Azure Logic Apps.</p>

<p>The objective is to improve operational visibility by automatically checking agent availability and sending email notifications when a predefined condition is met.</p>

<h2>2. Solution Components</h2>

<table>
<tr>
<th>Component</th>
<th>Purpose</th>
</tr>
<tr>
<td>Azure Logic Apps</td>
<td>Orchestrates the scheduled monitoring workflow.</td>
</tr>
<tr>
<td>Excel Online</td>
<td>Simulates Vonage agent availability data.</td>
</tr>
<tr>
<td>Microsoft 365 Outlook</td>
<td>Delivers automated email notifications.</td>
</tr>
</table>

<h2>3. Workflow Process</h2>

<ol>
<li>Azure Logic Apps executes automatically every minute.</li>
<li>Excel Online provides the simulated agent availability data.</li>
<li>The workflow retrieves the relevant agent record.</li>
<li>A conditional action evaluates the agent count.</li>
<li>If the agent count equals zero, an automated email alert is sent through Outlook.</li>
</ol>

<h2>4. Data Source and Integration</h2>

<p>Direct access to the organisation's Vonage agent-status API was unavailable during development.</p>

<p>Excel Online was therefore used as a simulated data source to represent agent availability and demonstrate the intended automation workflow.</p>

<p>Direct Vonage API integration is identified as a future enhancement once the required API access becomes available.</p>

<h2>5. Current Implementation</h2>

<ul>
<li>Monitoring frequency: Every one minute.</li>
<li>Data source: Excel Online.</li>
<li>Alert condition: Agent count equals zero.</li>
<li>Notification channel: Microsoft 365 Outlook email.</li>
</ul>

<h2>6. Future Enhancements</h2>

<ul>
<li>Integrate directly with the Vonage agent-status API.</li>
<li>Introduce configurable availability thresholds.</li>
<li>Monitor sustained low-availability conditions.</li>
<li>Prevent repeated notifications for ongoing incidents.</li>
<li>Improve workflow error handling.</li>
</ul>

<h2>7. Project Status</h2>

<p><strong>Proof of Concept – Excel-based simulated agent availability monitoring.</strong></p>

<p>The current implementation demonstrates scheduled monitoring and automated email alerting. Production integration with Vonage remains a future enhancement.</p>
