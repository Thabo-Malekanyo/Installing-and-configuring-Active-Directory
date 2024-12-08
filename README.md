<p align="center">
<img src="https://i.imgur.com/68z3394.png" alt="osTicket logo"/>
</p>

<h1>Installing and Configuring Microsoft Active Directory</h1>
This tutorial outlines the prerequisites and installation of Microsoft Active Directory on a Windows Server 2022 VM.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop


<h2>Operating Systems Used </h2>

- Windows Server 2022

<h2>List of Prerequisites</h2>

-Microsoft Azure Subscribtion
- Installed Windows Server 2022
  

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/pvzDb4z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to 'ADD ROLES AND FEATURES', choose Active Directory Domain Services,then click next,add features and click next and INSTALL.
</p>
<br />

<p>
<img src="https://i.imgur.com/qsseRGM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After successfully installing Active Directory, go ahead and promote this server to a domain controller.
</p>
<br />


p>
<img src="https://i.imgur.com/EtSJUV2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Click on "add a new forest" and choose the ROOT DOMAIN NAME of your choice,it can be "mydomain.com" or any name you like. Go ahead and click next and then INSTALL...
</p>
<br />




p>
<img src="https://i.imgur.com/81hvlLy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once the Installation is complete, the VM is going to restart and terminate the RDP connection and you will have to reconnect again....
</p>
<br />


<p>
<img src="https://i.imgur.com/MuSM3qR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Reconnecting back to the Windows Server 2022 VM, you should type your Root Domain name\Username and enter your password....example: mydomain.com\tash and then enter your password.This is how you are going to log-in to Windows Server 2022 VM now with RDP. 

</p>
<br />


