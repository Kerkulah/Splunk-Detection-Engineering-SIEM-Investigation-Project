<h1> Splunk Detection Engineering & SIEM Investigation Project
</h1>



<h2>Description</h2>
Hands on detection engineering project focused on understanding Splunk from the ground up, including its architecture, data ingestion pipeline, and field extraction process. Used real world datasets to investigate security incidents, analyze adversary behaviors, and operationalize Splunk as a SIEM for threat detection and response. Developed high fidelity SPL detections both TTP driven and analytics driven to surface anomalies, abnormal patterns, and attacker techniques aligned with MITRE ATT&CK. Gained practical experience navigating fields, validating log sources, tuning queries, and creating precise, actionable detections. 

<h2> Quick walk through::</h2>
<br />
Splunk architecture & core components
<br />
SPL (Search Processing Language) detection creation
<br />
Incident investigation using real-world data
<br />
TTP driven and anomaly-based detection engineering
<br />
Analyzing ingested fields/log structures
<br />






<p align="center">
Intrusion Detection With Splunk  <br/>

Using self generated and dummy data, I retrieved all accessible events in Splunk by setting the time picker to All Time and running the query:
index="main" earliest=0
This query returns all events available within the specified index

<br />
<br />
<img src="https://imgur.com/C3ckAo6.jpg"  height="80%" width="80%">
<br />
Exploring the Sysmon data begins with understanding the environment. Since we are approaching it as an unknown environment, the first step is to list all available sourcetypes using (index="main" | stats count by sourcetype) to identify what data sources are present. Query Sysmon sourcetype and take a look at the incoming data using (index="main" sourcetype="WinEventLog:Sysmon") <br/>
<img src="https://imgur.com/SCHzOLY.jpg"  height="80%" width="80%">
<br />
<br />

<p align="center">
Copy agent to Clipboard and deploy into Kali  <br/>

<br />
<br />
<img src="https://imgur.com/xbPDnoi.jpg"  height="80%" width="80%">
<br />
 AFTER AGENT ENROLLMENT CONFORMED <br/>
<img src="https://imgur.com/fg34aDu.jpg"  height="80%" width="80%">
<br />
<br />
  
<br />
Elastic dashboard showing top users/hosts for Windows Event 4625 authentication failures <br/>
<img src="https://imgur.com/K7kftdh.jpg"  height="80%" width="80%">
<br />
<br />

<img src="https://imgur.com/Q1tC0Zg.jpg"  height="80%" width="80%">
<br />

<img src="https://imgur.com/jnwRWam.jpg"  height="80%" width="80%">
<br />
<br />

<img src="https://imgur.com/R0ZiSiw.jpg"  height="80%" width="80%">
<br />
<br />
<br />
Monitoring authentication anomalies: failed logons across all users and admin accounts, disabled user activity, service account RDP usage, and real time group membership changes  <br/>
<img src="https://imgur.com/ixCzoN2.jpg"  height="80%" width="80%">

<br />
<br />
<br />
Successful RDP logon related to service accounts
<img src="https://imgur.com/LXSyFxL.jpg"  height="80%" width="80%">
<br />
<br />
Users add or removed from a local group within a specific timeframe (2023-03-05) 
<img src="https://imgur.com/hSHLJWB.jpg"  height="80%" width="80%">
<br />
<br />


<img src="https://imgur.com/D5xWhfS.jpg"  height="80%" width="80%">
<br />
<br />

<img src="https://imgur.com/VmP6tx2.jpg"  height="80%" width="80%">
<br />
<br />
<br />
<br />
