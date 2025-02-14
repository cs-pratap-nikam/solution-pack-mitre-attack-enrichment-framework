<h1 style="font-size:2rem;">FortiSOAR MITRE ATT&CK™ Solution Pack – Out-of-the box Playbooks Collections</h1>

The MITRE ATT&CK Playbook Collections demonstrate various MITRE ATT&CK Techniques.

- [13 - MITRE ATT&CK™ - Access Token Manipulation](#13---mitre-attck---access-token-manipulation)
- [13 - MITRE ATT&CK™ - Boot or Logon Autostart Execution](#13---mitre-attck---boot-or-logon-autostart-execution)
- [13 - MITRE ATT&CK™ - Credential Access](#13---mitre-attck---credential-access)
- [13 - MITRE ATT&CK™ - Defense Evasion](#13---mitre-attck---defense-evasion)
- [13 - MITRE ATT&CK™ - Event Triggered Execution](#13---mitre-attck---event-triggered-execution)
- [13 - MITRE ATT&CK™ - Link Techniques to Alerts and Incidents](#13---mitre-attck---link-techniques-to-alerts-and-incidents)
- [13 - MITRE ATT&CK™ - Modulars](#13---mitre-attck---modulars)
- [13 - MITRE ATT&CK™ - Process Execution](#13---mitre-attck---process-execution)
- [13 - MITRE ATT&CK™ - Signed Binary Proxy Execution](#13---mitre-attck---signed-binary-proxy-execution)
- [13 - MITRE ATT&CK™ - System Services](#13---mitre-attck---system-services)


## 13 - MITRE ATT&CK™ - Access Token Manipulation
Following is a table that lists the playbooks that are part of the **“13 - MITRE ATT&CK™ - Access Token Manipulation”** collection in the Solution Pack:

|**SN**|**Playbook Name**|**Description**|
| :- | :- | :- |
|1|HUNTS - SID-History Injection (T1134.005)|Hunts for SID-History injection via mimikatz and other tools. Also hunts for SID-History added to accounts (success and failure). Adding SID-History may allow for escalated privileges if SID filtering is not enabled.|

## 13 - MITRE ATT&CK™ - Boot or Logon Autostart Execution
Following is a table that lists the playbooks that are part of the “**13 - MITRE ATT&CK™ - Boot or Logon Autostart Execution**” collection in the Solution Pack:

|**SN**|**Playbook Name**|**Description**|
| :- | :- | :- |
|1|HUNTS - Winlogon Helper DLL (T1547.004)|Hunts for abnormal DLL loads and processes spawned by Winlogon|

## 13 - MITRE ATT&CK™ - Credential Access
Following is a table that lists the playbooks that are part of the “**13 - MITRE ATT&CK™ - Credential Access**” collection in the Solution Pack:

|**SN**|**Playbook Name**|**Description**|
| :- | :- | :- |
|1|Create and Link Alerts from Hunt (Host-based)|Creates and links the alert from a host-based sensor to a Hunt.|
|2|HUNTS - Credential Dumping (T1003)|Hunts for non-Windows processes accessing the lsass.exe process, which can be indicative of credential dumping.|
|3|HUNTS - Credential Dumping (T1003) Part2|Enriches LSASS.exe access information using Splunk or ElasticSearch.|
  
## 13 - MITRE ATT&CK™ - Defense Evasion
Following is a table that lists the playbooks that are part of the “**13 - MITRE ATT&CK™ - Defense Evasion**” collection in the Solution Pack:

|**SN**|**Playbook Name**|**Description**|
| :- | :- | :- |
|1|HUNTS- Deobfuscate/Decode Files or Information (T1140)|Identifies the use of Certutil or copy /b to deobfuscate data/files.|
|2|HUNTS-DCShadow (T1207)|Hunts for execution of network traffic generated by Mimikatz module ‘DCShadow’. The network-based portion of this playbook requires network detection signatures.|

## 13 - MITRE ATT&CK™ - Event Triggered Execution
Following is a table that lists the playbooks that are part of the “**13 - MITRE ATT&CK™ - Event Triggered Execution**” collection in the Solution Pack:

|**SN**|**Playbook Name**|**Description**|
| :- | :- | :- |
|1|HUNTS - AppInit DLLs (T1546.010)|Hunts for modification to AppInit DLLs registry keys.|
|2|HUNTS - Hidden Files and Directories (T1564.001)|Hunts for the use of attrib.exe to hide files.|
|3|HUNTS - Netsh Helper DLL (T1546.007)|Hunts for abnormal DLL loads and processes spawned by netsh.exe.|
|4|HUNTS - Screensaver (T1546.002)|Hunts for use of Windows Screensaver to enable attacker persistence. Hunts for abnormal screensaver executions, processes spawned by a screensaver, and abnormal modifications to screensaver registry keys.|

## 13 - MITRE ATT&CK™ - Link Techniques to Alerts and Incidents
Following is a table that lists the playbooks that are part of the “**13 - MITRE ATT&CK™ - Link Techniques to Alerts and Incidents**” collection in the Solution Pack:

|**SN**|**Playbook Name**|**Description**|
| :- | :- | :- |
|1|Link ATT&CK technique to Alert |Links MITRE technique or sub-technique to Alert, based on MITRE Attack ID|
|2|Link ATT&CK technique to Alert (On Update) |Links MITRE technique or sub-technique to Alert, based on MITRE Attack ID|
|3|Link ATT&CK technique to Incident |Links MITRE technique or sub-technique to Incident, based on MITRE Attack ID|
|4|Link ATT&CK technique to Incident (On Update) |Links MITRE technique or sub-technique to Incident, based on MITRE Attack ID|
  
## 13 - MITRE ATT&CK™ - Modulars 
Following is a table that lists the playbooks that are part of the “**13 - MITRE ATT&CK™ - Modulars**” collection in the Solution Pack:

|**SN**|**Playbook Name**|**Description**|
| :- | :- | :- |
|1|Create Alert from Network Sensor and Link to Hunt|Creates and links an alert from a network-based sensor to a Hunt.|
|2|Create and Link Alerts from Asset (Host-based)|Creates and links alerts to an asset.|
|3|Create and Link Alerts from Hunt (Host-based)|Creates and links an alert from a host-based sensor to a Hunt.|
|4|Create and Link Indicator from Alert|Creates and links indicators when an alert is created.|
|5|Create and Link User|Creates a user (if it doesn't exist already), and links to specified emails, alerts or incidents.|
|6|Create Asset from Alert|Links an asset to an alert if the hostname is present.|
|7|Create User from Alert (Host)|Retrieves incidents related to the specified alert and creates and links users to that alert.|
|8|Deduplicate Comments (Asset)|Deduplicates comments on asset records.|
|9|Deduplicate Comments (Hunt)|Deduplicates comments on Hunt records.|

## 13 - MITRE ATT&CK™ - Process Execution
Following is a table that lists the playbooks that are part of the “**13 - MITRE ATT&CK™ - Process Execution**” collection in the Solution Pack:

|**SN**|**Playbook Name**|**Description**|
| :- | :- | :- |
|1|HUNTS - Dynamic Data Exchange (T1559.002)|Identifies processes spawned by a Microsoft Office product.|
|2|HUNTS - LSASS Driver (T1547.008)|Identifies process execution via loading an illegitimate LSASS driver (DLL). This technique can be used to execute a binary whenever LSASS executes.|
|3|HUNTS - XSL Script Processing (T1220)|Detects process execution via the use of XSL scripts. XSL scripts can allow a user to bypass application whitelisting by executing code through trusted OS binaries.|
  
## 13 - MITRE ATT&CK™ - Signed Binary Proxy Execution
Following is a table that lists the playbooks that are part of the “**13 - MITRE ATT&CK™ - Signed Binary Proxy Execution**” collection in the Solution Pack:

|**SN**|**Playbook Name**|**Description**|
| :- | :- | :- |
|1|HUNTS - CMSTP (T1218.003)|Identifies processes spawned by CMSTP.exe|
|2|HUNTS - Compiled HTML File (T1218.001)|Identifies processes spawned by hh.exe|
|3|HUNTS - Control Panel Items (T1218.002)|Identifies processes spawned by Control Panel files and execution of non-standard .cpl files|
|4|HUNTS - InstallUtil (T1218.004)|Identifies process execution via InstallUtil and Installutil being passed via the command line (CMD,PS.WMIC)|
|5|HUNTS - Mshta (T1218.005)|Identifies Processes spawned by Mshta.exe|
|6|HUNTS - Regsvcs/Regasm (T1218.009)|Identifies processes spawned by Regsvcs and Regasm.|
|7|HUNTS - Rundll32 (T1218.011)|Identifies Processes spawned by rundll32.exe where the DLL loaded exists outside of System32/SysWOW64 or Program Files. This playbook may require additional tuning to reduce false positives.|

## 13 - MITRE ATT&CK™ - System Services
Following is a table that lists the playbooks that are part of the “**13 - MITRE ATT&CK™ - System Services**” collection in the Solution Pack:

|**SN**|**Playbook Name**|**Description**|
| :- | :- | :- |
|1|ASSETS - Service Execution (Enrichment) (T1569.002)|Enriches service data and query VirusTotal for reputation. Queries SIEM for all instances of any malicious hash observed.|
|2|ASSETS - Service Execution (T1569.002)|Identifies on-OS services on a host and pass information to the next playbook for enrichment.|
