<h1>How to setup an Active Directory Lab at home</h1>



<h2>Description</h2>
In this project, I learned how to create an Active Directory home lab Environment using Oracle Virtual Box. I configured and ran this lab to help develop my understanding of how active directory and windows networking works.  
<br />


<h2>Languages and Utilities Used</h2>

- <b>Oracle Virutal Box</b> 
- <b>Windows Powershell</b>

<h2>Environments Used </h2>

- <b>Windows 10</b>

<h2>Program walk-through:</h2>

<p align="center">
First, download Virtual Box: <br/>
<img src="https://i.imgur.com/ff5SfxA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Next, you want to head over to microsoft and download the Windows 10 ISO (64 bit) <br/>
<img src="https://i.imgur.com/tV6CfAi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
After installing the virtual machine manager, open it up and add your ISO <br/>
<img src="https://i.imgur.com/pm9Cf1J.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Next, install Windows 10 <br/>
<img src="https://i.imgur.com/5CS1yL6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/ZaMH1HE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Assign IP address to internal adapter <br/>
<img src="https://i.imgur.com/YUG8uBm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
After that, using Mydomain.com, go ahead and promote the domain controller <br/>
<img src="https://i.imgur.com/fHzTymw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br />
<br />
Next, Install and configure Routing and Remote Access (also known as RAS/NAT) <br/>
<img src="https://i.imgur.com/LUFMDPX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Install and configure DHCP <br/>
<img src="https://i.imgur.com/4lAheG1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enable browsing on the machine <br/>
<img src="https://i.imgur.com/w4gzjVT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Add users to your network using a Powershell script (https://github.com/MLake11/Create-Users-Powershell-Script/blob/main/README.md)  <br/>
<img src="https://i.imgur.com/A5kvm2Y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for all users to be added  <br/>
<img src="https://i.imgur.com/jDta2zq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Create Windows 10 VM <br/>
<img src="https://i.imgur.com/I6KhoKD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 Install Windows 10 OS <br/>
<img src="https://i.imgur.com/0MqfpNm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br /> 
 
 Join Windows 10 to domain <br/>
<img src="https://i.imgur.com/qugYksq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

 Login to Client1 with Domain Credentials
 <img src="https://i.imgur.com/hmTkK1F.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
