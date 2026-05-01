<h1>Active Directory - Installation & Initial Configuration</h1>

<h2>Overview</h2>
This project demonstrates the installation and initial configuration of an Active Directory environment in a virtual lab. The goal is to simulate a basic enterprise network setup, including domain services, user management, and domain-joined endpoints.

This lab is designed to build foundational skills required for an entry-level IT Help Desk role.
<br />

<h2>Objectives</h2>
- <b>Install and configure Active Directory Domain Services (AD DS)</b>
- <b>Promote a Windows Server to a Domain Controller</b>
- <b>Configure DNS for domain functionality</b>
- <b>Create Organizational Units (OUs)</b>
- <b>Create and manage user accounts</b>
- <b>Join client machines to the domain</b>
- <b>Validate domain communication</b>
<br />


<h2>Lab Environment</h2>

- <b>Hypervisor: VirtualBox</b> 
- <b>Server OS: Windows Server 2025</b>
- <b>Client OS: Windows 11 (Helpdesk and Client)</b>
- <b>Domain Name: DanLab.local</b>


<h2>Installation & Configuration Steps</h2>

<h3>1. Install Windows Server</h3>
<br />
- <b>Set up base OS</b>
- <b>Configure hostname</b>
- <b>Assign Static IP Address</b>
<br>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<h3>2. Install Active Directory Domain Servicesr</h3>
<br />
- <b>Add AD DS role via Server Manager</b>
- <b>Include required features</b>
<br>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<h3>3. Promote to Domain Controller</h3>
<br />
- <b>Create new forest (DanLab.local</b>
- <b>Configure Directory Services Restore Mode (DSRM) password</b>
- <b>Restart server</b>
<br>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<h3>4. Verify AD Installation</h3>
<br />
- <b>Open Active Directory Users and Computers</b>
- <b>Confirm domain structure</b>
<br>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<h3>5. Configure Organization Units (OUs)</h3>
<br />
- <b>IT</b>
- <b>HR</b>
- <b>Sales</b>
<br>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<h3>6. Create User Accounts</h3>
<br />
- <b>Create Help Desk Admin account</b>
- <b>Create standard test user account</b>
<br>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<h3>7. Join Client Machines to Domain</h3>
<br />
- <b>Configure client DNS to point to Domain Controller</b>
- <b>Join machines to domain (DanLab.local)</b>
- <b>Restart and log in with domain credentials</b>
<br>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<h3>8. Validate Environment</h3>
<br />
- <b>Log into domain-joined machines</b>
- <b>Confirm users can authenticate</b>
- <b>Verify machines appear in Active Directory</b>
<br>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<h2>Skills Demonstrated</h2>

- <b>Active Directory setup and configuration</b> 
- <b>Basic network configuration (IP, DNS)</b>
- <b>User and computer management</b>
- <b>Domain environment validation</b>
<br />
<br />
<h2>Next Steps</h2>

<p>The next phase of this project will focus on real-world help desk tasks and troubleshooting, including:</p>

- <b>Password resets</b> 
- <b>Account lockouts</b>
- <b>Group membership changes</b>
- <b>Remote support</b>
- <b>Basic troubleshooting scenarios</b>
<br />
<br />
<h2>Notes</h2>
<p>This lab is part of a larger effort to simulate real-world IT support scenarios and develop hands-on experience for IT support roles</p>
