<h1>Active Directory - Installation & Initial Configuration</h1>

<h2>Overview</h2>
<p>This project demonstrates the installation and initial configuration of an Active Directory environment in a virtual lab. The goal is to simulate a basic enterprise network setup, including domain services, user management, and domain-joined endpoints.</p>
<p>Active Directory is used in most enterprise environments to manage users, devices, and security policies centrally.</p>
<h2>Objectives</h2>

- <b>Install and configure Active Directory Domain Services (AD DS)</b>
- <b>Promote a Windows Server to a Domain Controller</b>
- <b>Configure DNS for domain functionality</b>
- <b>Create Organizational Units (OUs)</b>
- <b>Create and manage user accounts</b>
- <b>Join client machines to the domain</b>
- <b>Validate domain communication</b>
- <b>Create and apply basic Group Policy Objects (GPOs)</b>
- <b>Demonstrate OU-based policy targeting</b>
<h2>Lab Environment</h2>

- <b>Hypervisor: VirtualBox</b> 
- <b>Server OS: Windows Server 2025</b>
- <b>Client OS: Windows 11 (Helpdesk and Client)</b>
- <b>Domain Name: DanLab.local</b>


<h2>Installation & Configuration Steps</h2>

<h3>1. Install Windows Server</h3>

- <b>Set up base OS</b>
- <b>Configure hostname</b>
- <b>Assign static IP address</b>
<br>
<img src="https://i.imgur.com/sbe6eCj.png" height="80%" width="80%" alt="Server Manager"/>
<br>
<img src="https://i.imgur.com/15Xb28j.png" height="80%" width="80%" alt="Static IP Settings"/>
<h3>2. Install Active Directory Domain Services</h3>

- <b>Add AD DS role via Server Manager</b>
- <b>Include required features</b>
<br>
<img src="https://i.imgur.com/FVhP9kx.png" height="80%" width="80%" alt="AD DS Installation"/>
<br />
<h3>3. Promote to Domain Controller</h3>

- <b>Create new forest (DanLab.local)</b>
- <b>Configure Directory Services Restore Mode (DSRM) password</b>
- <b>Restart server</b>
<br>
<img src="https://i.imgur.com/DwurW2r.png" height="80%" width="80%" alt="Adding new forest"/>
<br />
<h3>4. Verify AD Installation</h3>

- <b>Open Active Directory Users and Computers</b>
- <b>Confirm domain structure</b>
<br>
<img src="https://i.imgur.com/zAZh3EO.png" height="80%" width="80%" alt="Users and Computers Structure"/>
<br />
<h3>5. Configure Organization Units (OUs)</h3>

- <b>IT</b>
- <b>HR</b>
- <b>Sales</b>
<br>
<img src="https://i.imgur.com/rQ7k4ZT.png" height="80%" width="80%" alt="Organizational Units"/>
<br />
<h3>6. Create User Accounts</h3>

- <b>Create Help Desk Admin account</b>
- <b>Create standard test user account</b>
<br>
<img src="https://i.imgur.com/GKjeLd4.png" height="80%" width="80%" alt="Users Created"/>
<br />
<h3>7. Join Client Machines to Domain</h3>

- <b>Configure client DNS to point to Domain Controller</b>
- <b>Join machines to domain (DanLab.local)</b>
- <b>Restart and log in with domain credentials</b>
<br>
<img src="https://i.imgur.com/EaVzpH4.png" height="80%" width="80%" alt="Joined to Domain"/>
<br />
<h3>8. Validate Environment</h3>

- <b>Log into domain-joined machines</b>
- <b>Confirm users can authenticate</b>
- <b>Verify machines appear in Active Directory</b>
<br>
<img src="https://i.imgur.com/TALMeWs.png" height="80%" width="80%" alt="User Login"/>
<br />
<img src="https://i.imgur.com/rDA4cyg.png" height="80%" width="80%" alt="Computers Present"/>
<br />
<h3>9. Configure Group Policy (GPO) for User Restrictions</h3>

- <b>Create a Group Policy Object to manage user restrictions</b>
- <b>Configure policy to restrict Control Panel access</b>
- <b>Link GPO to specific Organizational Units (HR and Sales)</b>
- <b>Apply and validate policy on domain-joined machines</b>
<br>
<img src="https://i.imgur.com/UqAiHB0.png" height="80%" width="80%" alt="Edit GPO"/>
<br />
<img src="https://i.imgur.com/7Xvb1rz.png" height="80%" width="80%" alt="Link GPO"/>
<br />
<img src="https://i.imgur.com/NDvnBWS.png" height="80%" width="80%" alt="Update Group Policy"/>
<br />
<img src="https://i.imgur.com/lwKZoHk.png" height="80%" width="80%" alt="Policy Applied on Client Machine"/>
<br />
<h2>Skills Demonstrated</h2>

- <b>Active Directory setup and configuration</b> 
- <b>Basic network configuration (IP, DNS)</b>
- <b>User and computer management</b>
- <b>Domain environment validation</b>
- <b>Basic Group Policy creation and management</b>
- <b>Applying user restrictions using GPOs</b>
- <b>OU-based policy targeting</b>
- <b>Policy validation on client machines</b>
<h2>Next Steps</h2>

<p>The next phase of this project will focus on real-world help desk tasks and troubleshooting, including:</p>

- <b>Password resets</b> 
- <b>Account lockouts</b>
- <b>Group membership changes</b>
- <b>Remote support</b>
- <b>Basic troubleshooting scenarios</b>
<h2>Notes</h2>
<p>This lab is part of a larger effort to simulate real-world IT support scenarios and develop hands-on experience for IT support roles</p>
