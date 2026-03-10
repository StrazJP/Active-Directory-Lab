# Active-Directory-Lab
<h1>JWipe - Disk Sanitization</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
This homelab project demonstrates the deployment and administration of a Windows Server Active Directory environment in Microsoft Azure using a cost-optimized virtual machine. The lab involves deploying a Windows Server VM, installing Active Directory Domain Services (AD DS), and promoting the server to a Domain Controller to create a centralized domain. A logical Organizational Unit (OU) structure is designed to simulate an enterprise environment, where users and security groups are created and managed to demonstrate identity and access management through group membership. A Windows client is joined to the domain to test user authentication and domain login, while administrative tasks such as user management, group configuration, and system monitoring are performed using both GUI tools and PowerShell. The project also includes basic Active Directory troubleshooting, reinforcing practical skills in diagnosing authentication issues, configuration errors, and common directory service problems.
<br />


<h2>Utilities Used</h2>

- <b>Microsoft Azure</b> 
- <b>Remote Desktop (RDP)</b>
- <b>Server Manager</b>
- <b>Active Directory Users and Computers</b>
- <b>Group Policy Management</b> 




<h2>Environments Used </h2>

- <b>Windows Server 2022 Datacenter: Azure Edition Hotpatch - X64 Gen2</b>

<h2>Program walk-through:</h2>

<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
