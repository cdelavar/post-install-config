<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

Configure:
- Roles
- Departments
- Teams
- Agents
- Users
- SLA's
- Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://imgur.com/Z93dxEy.png" height="80%" width="80%" alt="Configure Roles"/>
</p>
<p>
The first step is to asign roles to the help desk agents, which will grant them permissions to work with user tickets in various capacities.
Click on Admin Panel - Agents - Roles
</p>
<br />

<p>
<img src="https://imgur.com/K8ZQjtP.png" height="80%" width="80%" alt="Supreme Admin"/>
</p>
<p>
Name the role - in this case, we'll create a role called "Supreme Admin"
</p>
<br />

<p>
<img src="https://imgur.com/ewDK4xR.png" height="80%" width="80%" alt="Supreme Admin Permissions"/>
</p>
<p>
Check the boxes for each permission you'd like to grant to the role. Let's give the Supreme Admin all the permissions. Permissions types are organized by each tab: Tickets, Tasks, Knowledgebase. Click on each tab and grant the permissions. When finished adding permissions, click Add Role.
</p>
<br />

<p>
<img src="https://imgur.com/ef8W8qm.png" height="80%" width="80%" alt="Configure Departments"/>
</p>
<p>
Since tickets are routed through departments, next up in creating and configuring Departments. While in th Admin Panel, click on Agents - Departments - Add New Department. Let's add a department called "System Administrators". Configure the settings and then click Create Dept.
</p>
<br />

<p>
<img src="https://imgur.com/Eeys3Ve.png" height="80%" width="80%" alt="Configure Teams"/>
</p>
<p>
Teams allow you to pull agents from the departments in order to work on tickets that require the department permissions to be superceded. To create a team, while in the Admin Panel, click on Agents - Teams - Add New Team. OsTicket comes packaged with a default "Level I Support" team. Let's create a new team called "Level II Support". Configure the team settings and click Create Team.
</p>
<br />

<p>
<img src="https://imgur.com/blKuyZq.png" height="80%" width="80%" alt="Configure Agents"/>
</p>
<p>
Now let's create the Agents that will be our help desk support professionals that work on the tickets. While in the Admin Panel, click on Agents - Agents - Add New Agent. Enter a name, email, set their password, grant them access and permissions, and assign them to teams. 
</p>
<br />

<p>
<img src="https://imgur.com/impc9ew.png" height="80%" width="80%" alt="Configure Users"/>
</p>
<p>
To add users that can create tickets, navigate to the Agent Panel and click on Users - Add User. 
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />


