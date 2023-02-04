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
<b>The first step is to asign roles to the help desk agents, which will grant them permissions to work with user tickets in various capacities.
Click on Admin Panel - Agents - Roles</b>
</p>
<br />

<p>
<img src="https://imgur.com/K8ZQjtP.png" height="80%" width="80%" alt="Supreme Admin"/>
</p>
<p>
<b>Name the role - in this case, we'll create a role called "Supreme Admin"</b>
</p>
<br />

<p>
<img src="https://imgur.com/ewDK4xR.png" height="80%" width="80%" alt="Supreme Admin Permissions"/>
</p>
<p>
<b>Check the boxes for each permission you'd like to grant to the role. Let's give the Supreme Admin all the permissions. Permissions types are organized by each tab: Tickets, Tasks, Knowledgebase. Click on each tab and grant the permissions. When finished adding permissions, click Add Role.</b>
</p>
<br />

<p>
<img src="https://imgur.com/ef8W8qm.png" height="80%" width="80%" alt="Configure Departments"/>
</p>
<p>
<b>Since tickets are routed through departments, next up in creating and configuring Departments. While in th Admin Panel, click on Agents - Departments - Add New Department. Let's add a department called "System Administrators". Configure the settings and then click Create Dept.</b>
</p>
<br />

<p>
<img src="https://imgur.com/Eeys3Ve.png" height="80%" width="80%" alt="Configure Teams"/>
</p>
<p>
<b>Teams allow you to pull agents from the departments in order to work on tickets that require the department permissions to be superceded. To create a team, while in the Admin Panel, click on Agents - Teams - Add New Team. OsTicket comes packaged with a default "Level I Support" team. Let's create a new team called "Level II Support". Configure the team settings and click Create Team.</b>
</p>
<br />

<p>
<img src="https://imgur.com/blKuyZq.png" height="80%" width="80%" alt="Configure Agents"/>
</p>
<p>
<b>Now let's create the Agents that will be our help desk support professionals that work on the tickets. While in the Admin Panel, click on Agents - Agents - Add New Agent. Enter a name, email, set their password, grant them access and permissions, and assign them to teams.</b> 
</p>
<br />

<p>
<img src="https://imgur.com/impc9ew.png" height="80%" width="80%" alt="Configure Users"/>
</p>
<p>
<b>To add users that can create tickets, navigate to the Agent Panel and click on Users - Add User. </b>
</p>
<br />

<p>
<img src="https://imgur.com/xf5HJnI.png" height="80%" width="80%" alt="Configure SLA's"/>
</p>
<p>
<b>Service level agreements need to be added which will define when tickets are expected to be closed based on severity of issues. To configure a SLA, navigate to the Admin Panel and click on Manage - SLA - Add New SLA Plan. Let's create three SLA's: SEV-A for emergency issues with an agent response required 24 hours a day/ 7 days a week and grace period of 1 hour, SEV-B for 24 hours/5 days a week and 4 hour grace period, and SEV-C for low priority tickets that need a response only during business hours with an 8 hour grace period.</b>
</p>
<br />

<p>
<img src="https://imgur.com/dk3rVrO.png" height="80%" width="80%" alt="SLA's"/>
</p>

<p>
<img src="https://imgur.com/aUIrTRN.png" height="80%" width="80%" alt="Configure Help Topics"/>
</p>
<p>
<b>Finally, we'll create Help Topics which will allow users to choose a category their issue falls under, and this will also help to assign the ticket to the appropriate department. While in the Admin Panel, click on Manage - Help Topic - Add New Help Topic. Name the help topic and configure based on the SLA it falls under. For example, a help topic of "Business Critical Outage" configured with the emergency SEV-A SLA.</b>
</p>
<br />

<p>
<img src="https://imgur.com/EyrpHP4.png" height="80%" width="80%" alt="Help Topic SLA"/>
</p>


