<h1>Security Incident and Event Management Tool
<h2>Description</h2>
This repository describes in detail how i configured the SIEM tools i will be using for incident response and threat analysis.
<br />


<h2>Utilities Used</h2>

- <b>Windows Server</b>
- <b>Windows 11</b>
- <b>PfSense</b>
- <b>Splunk</b>
- <b>Sysmon</b>


<h2>Environments Used </h2>

- <b>Virtual Box</b>

<h2>Program walk-through:</h2>

<h3>Installation Tools</h3>

| Tool Name | Why It Was Used | Download Link |
|-----------|---------------------------|---------------|
| Splunk | a SIEM tool used for incident response and event management | [Download](https://www.splunk.com/en_us/download/splunk-enterprise.html) |
| Sysmon | Sysmon is a Windows tool used for advanced system monitoring and security logging | [Download](https://learn.microsoft.com/en-us/sysinternals/downloads/sysmon) |
| pfSense | Firewall and router used to simulate network segmentation and traffic control in the lab. | [Download](https://www.wireshark.org/) |
| Windows 11 Enterprise | Will be used as our client machine | [Download](https://www.microsoft.com/en-us/evalcenter/download-windows-11-enterprise) |
| Windows Server | The server that'll be used for the Domain Controller | [Download](https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2025) |

## Installing and Configuring Sysmon

Sysmon and splunk is downloaded and installed using the above link. To make better use of both tools, we will add <strong>splunk apps</strong>. This is done by Logging in using your splunk account, not the account you set up on the splunk instance. <br/>
<br/>
You can use this [link](https://splunkbase.splunk.com/app/5709) to add Splunk Apps.<br/>
<br/>
<p align="center">
  Download Splunk Add-on for Sysmon:
<img src="https://github.com/Dalilatu/Project-Page-Dal/blob/main/Home%20lab%20Setup%20diagram.drawio.png?raw=true" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
