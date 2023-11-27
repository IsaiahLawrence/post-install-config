<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles (Admin or Agents)
- Configure SLAs
- Add new users


<h2>Configuration Steps</h2>

<p> Here we'll add a new agent this agent can be added as any role. This page can only be accessed from the admin panel, after clicking on agents </p> <img src="https://i.imgur.com/CdsdXVD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
<br />
<p>We can make a new role by clicking roles underneath the agent tab. Here I'll make a role called Team lead the Permisions dropped down will allow me to give team lead the ability to assign tickets, close tickets etc.. We could make an admin account here as well and give it all privileges.  <img src="https://i.imgur.com/DNQkmwt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 

<br />

</p> 
<p>Here I can add a SLA
  
<img src="https://i.imgur.com/ZGkSFx9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> </p>

<br />

<p> Here is what it looks like when defining your SLA on this page we can set severity, schedule, grace period, we can also turn on overdue alerts if they fall out of the grace period window. <img src="https://i.imgur.com/0rGJ9B3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<br />
