<h1>Testing and Validation</h1>

<h2>Project Testing</h2>

<p>The following scenarios are designed to validate the Azure Logic Apps workflow.</p>

<table>
<tr>
<th>Test Scenario</th>
<th>Expected Result</th>
</tr>
<tr>
<td>Agent count above zero</td>
<td>No alert generated</td>
</tr>
<tr>
<td>Agent count equals zero</td>
<td>Email alert generated</td>
</tr>
<tr>
<td>Excel data retrieved successfully</td>
<td>Workflow continues</td>
</tr>
<tr>
<td>Outlook connector succeeds</td>
<td>Email notification delivered</td>
</tr>
</table>

<h2>Monitoring Frequency</h2>

<p>The Logic App is configured to execute every minute.</p>

<h2>Current Limitations</h2>

<ul>
<li>Excel Online is used as simulated Vonage agent availability data.</li>
<li>Direct Vonage API integration has not been implemented.</li>
<li>Monitoring for a sustained low-availability condition is a future enhancement.</li>
</ul>

<h2>Validation Evidence</h2>

<p>Azure workflow screenshots and email notification evidence will be maintained in the repository.</p>

<h2>Project Status</h2>

<p><strong>Proof of Concept.</strong></p>
