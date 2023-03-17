<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Create Resource Group
- Configure your VMs with the necessary tools and resources
- Setup and enable Remote Desktop
- Ping Virtual Machines

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/0B5lW29.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 You must enable remote desktop before you can have the abilty to connect with and/or use a faraway desktop computer with a second computer. 
</p>
<br />

<p>
<img src="https://i.imgur.com/TzVZfSV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Virtual machines are compute resources that allow use of software and remote access without the need of having to have an actual physical computer present.
</p>
<br />

<p>
<img src="https://i.imgur.com/FZKZQXP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the display above, there is a ping command being sent from VM "OsTicket" to VM "VM-2". A ping is a utility used between CPUs to communicate with one another. 
</p>
<br />
