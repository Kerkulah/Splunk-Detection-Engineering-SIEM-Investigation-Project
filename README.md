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
VM SetUP <br/>

Open VirtualBox and click New  → || Name the VM  and choose Type and ISO file → After VM Setup
Start the VM
<br />
<br />
<img src="https://imgur.com/KfKxyeG.jpg"  height="80%" width="80%">
<br />
login to Elastic and setup defend intergration  <br/>
<img src="https://imgur.com/eEtAYJk.jpg"  height="80%" width="80%">
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
