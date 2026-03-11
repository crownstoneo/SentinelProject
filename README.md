<h1>3️⃣ Sentinel Project: Microsoft Sentinel Detection Engineering & Incident Response</h1>

<h2>Objective</h2>
Create detection rules and investigate security incidents using Microsoft Sentinel.
<br />

<h2>Environments Used</h2>
- <b>Azure Tenant</b>
<br />
- <b>Log Analytics Workspace</b>
<br />
- <b>Windows VM with logs enabled</b>
<br />

<h2>Tools Used</h2>
- <b>Microsoft Sentinel</b>
<br />
- <b>KQL (Kusto Query Language)</b>
<br />
- <b>Defender Logs</b>
<br />

<h2>Methodology</h2>
- <b>Connected data sources:</b> Security Events and Defender logs.
<br />
- <b>Wrote custom KQL queries:</b> Developed logic to detect suspicious logins.
<br />
- <b>Converted queries into Analytic Rules:</b> Automated the detection process.
<br />
- <b>Triggered simulated attacks:</b> Generated real-time security events.
<br />
- <b>Incidents generated automatically:</b> Verified rule triggering.
<br />
- <b>Investigated using logs and timelines:</b> Analyzed attack vectors.
<br />

<h2>Evidence</h2>
<b>KQL Queries:</b> 
<br />
<img width="1463" height="635" alt="Screenshot 2025-12-24 030325" src="https://github.com/user-attachments/assets/2970660d-b32a-4be6-a75b-7697ac6d0254" />
<br />
<br />
<b>Alert Screenshots:</b> 
<br />
<img width="1659" height="340" alt="Screenshot 2025-12-24 033116" src="https://github.com/user-attachments/assets/cf8f4d6b-4c7e-4012-a537-1475eac6a6a4" />
<br />
<br />
<b>Incident Dashboard:</b> 
<br /><img width="857" height="459" alt="Screenshot 2025-12-24 031608" src="https://github.com/user-attachments/assets/70bf4c2b-c1ec-4b4e-b1e0-811a84fa7b8c" />

<h2>Findings</h2>
Manual log review is inefficient. Automated detection rules reduce response time significantly.
<br />

<h2>Remediation</h2>
- Deploy analytic rules
<br />
- Enable alert automation
<br />
- Monitor identity-related events continuously
<br />

<h2>Lessons Learned</h2>
KQL enables powerful, fast threat hunting with minimal overhead.
