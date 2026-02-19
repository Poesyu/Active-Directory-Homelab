up# Active-Directory-Homelab
Active Directory Homelab

<h2>Description</h2>
This project involves building a Windows Server 2019 Active Directory lab in VirtualBox, with a Domain Controller and a Windows 10 client. It uses a PowerShell script to automate the creation of 1,000+ users, simulating a corporate network environment. The setup was made with Tailscale and RustDesk to make a secure remote in.
<br />

<h2>Utilities Used</h2>

<b>PowerShell</b>

<b>Oracle VirtualBox</b>

<b>Tailscale</b>

<b>Rustdesk</b>

<b>Active Directory</b>


<h2>Operating Systems Used </h2>

<b>Windows Server 2019</b> 

<b>Windows 10</b> 



<h2>Setup:</h2>

<p align="center">
using Rustdesk with Tailscale to securely remote into my home server: <br/>
<img src="Images/image.png"/>
<br />
<br />

<p align="center">
Using Oracle VirtualBox I created a Windows 10 Server VM: <br/>
<img src="Images/image (1).png"/>
<br />
<br />

<p align="center">
Finished installing some QOL items to remove the delayed mouse, enable auto sizing on windows and renamed the machine: <br/>
<img src="Images/image (2).png"/>
<br />
<br />

<p align="center">
Investigated which IP was an internal (VM) IP and which was the orignial internet. Then assigned a specific IP to Internal for the VM network: <br/>
<img src="Images/image (3).png"/>
<br />
<br />

<p align="center">
Created a domain: <br/>
<img src="Images/pasted file.png"/>
<br />
<br />

<p align="center">
Started to create the Admin Users group: <br/>
<img src="Images/a.png"/>
<br />
<br />

<p align="center">
Created myself as Admin user, then logged into it: <br/>
<img src="Images/aa.png"/>
<br />
<br />

<p align="center">
Setup of the Roles and Routing wizard: <br/>
<img src="Images/aaa.png"/> <img src="Images/aaaa.png"/>
<br />
<br />

<p align="center">
Added the DHCP Scope: <br/>
<img src="Images/b.png"/>
<br />
<br />

<p align="center">
Used Powershell to automatically create 1000 users: <br/>
<img src="Images/bb.png"/> <img src="Images/bbb.png"/>
<br />
<br />

<p align="center">
Created a 2nd VM, as a User: <br/>
<img src="Images/bbbb.png"/>
<br />
<br />

<p align="center">
The 2nd VM is registered as a User: <br/>
<img src="Images/c.png"/>
<br />
<br />
