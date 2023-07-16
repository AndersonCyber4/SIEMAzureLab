<h1>SIEM Azure Home Lab</h1>

<h2>Description</h2>
To create a SIEM in Azure, I utilized PowerShell to automate the provisioning of a virtual machine and the installation of Microsoft Sentinel. Leveraging an API key, I connected Sentinel to relevant data sources, enabling real-time security event monitoring. This robust setup allowed for efficient threat detection and incident response within the Azure environment. My project showcases expertise in cybersecurity implementation using cutting-edge technologies and demonstrates the ability to build a fully functional SIEM solution with seamless integration between Azure services.
<br />


<h2>Programss Used</h2>

- <b>PowerShell</b> 
- <b>Microsoft Azure</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Open the command prompt to ping the VM IP address: <br/>
<img src="https://i.imgur.com/VxNDZUl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Go to this website to obtain a free API key:  <br/>
<img src="https://i.imgur.com/LCZGsm6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the VM and open Powershell ISE and enter the following script with your new API key and press the green play button: <br/>
<img src="https://i.imgur.com/YIVB0Ch.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Navigate to the designated directory, locate the "failed_rdp" files, and seamlessly transfer them to your local system:  <br/>
<img src="https://i.imgur.com/S5fxfjE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Head back to Azure and go to log analytics and create a custom log. Import the "failed_rdp" file:  <br/>
<img src="https://i.imgur.com/zlUkTLs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Go to Microsoft Sentinel to workbooks to create this query. Once this is complete run the query:  <br/>
<img src="https://i.imgur.com/uoXgOrK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Open map settings and apply these settings. This would provide accuracy to your map:  <br/>
<img src="https://i.imgur.com/8Iz4ZEC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Set the auto refresh to 5 minutes. While your API key runs in your VM on Powershell ISE this will update every 5 minutes to show the failed attempts locations:  <br/>
<img src="https://i.imgur.com/az5LcEO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
