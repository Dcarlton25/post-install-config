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

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Resource Group
- Virtual Machine
- Remote Desktop Connection
- Internet Information Services (iis)
- osTicket

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/c4Hr3Ik.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/9AYeN8s.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
</p>
To begin this section of the lab you will need to log into osTicket and make sure you are on the admin panel, which can be toggled near the top right corner of the screen. Next, you will need to click "agents", then "roles", and then click "add new roles". Once you have done that, give your new role a name, then click "permissions", and check all the boxes, then click "tasks" and check all the boxes, then click "knowledgebase" and check the box", and finally click "add role". Now you have created a role for osTicket. Examples above.
</p>
<br />

<p>
<img src="https://i.imgur.com/dLitOD0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
</p>
<p>
Next, we will be creating a Department in osTicket. First, you will need to make sure you are on the admin panel, then click "agents", then click "departments", and then click "add new new department". After that, give your new department a name, then give your department a manager, and then click "create department". Now you have created a department for osTicket. Example above.
</p>
<br />

<p>
<img src="https://i.imgur.com/XUwy8Tq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After that, we will be creating a Team in osTicket. First, you will need to make sure you are on the admin panel, then click "agents", then click "teams", and then click "add new team". Now give your new team a name, then toggle "members" and select a team member, and then click "create team". Now you have created a team in osTicket. Example above.
</p>
<br />

<p>
<img src="https://i.imgur.com/NWuCBsf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, we will be adding agents in osTicket. First, make sure you are on the admin panel, then click "agents", then click "agents" underneath the agents tab, and then click "add new agent". After that, give your agent a first as well as a last name, then give your agent an email address, then give your agent a username, then click "set password", after that uncheck the box "send the agent a password reset email", then set a new password for your agent, then click "set". Next, toggle "access", then click "select department" and select the department you created. Next, click "select role" and select the role that you created. After that, toggle "teams", then click "select team" and select the team that you created, then click "create". You will need to create two agents so repeat all the previous steps, except for this second agent you will need to select "support" for department and "view only" for role. Now you have created two agents in osTicket. Examples above.
</p>
<br />

<p>
<img src="https://i.imgur.com/2HxxjjW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, we will  be adding users for osTicket. First, you will need to switch over to the agent panel, then click "users", and then click "add users". Next, give your new user an email address, then provide a full name for your new user, and then click "add user". You will need two users for this lab so repeat the previous steps for your second user. Now you have created two users for osTicket. Examples above.
</p>
<br />

<p>
<img src="https://i.imgur.com/eEXoOO5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, we will be making Service-Level Agreements (SLAs) for osTicket. First, you will need to go back to the admin panel, then click "manage", then click "SLA, and then click "add new SLA plan". Next, you will need to name your SLA plan "SEV-A", then give your new SLA plan a grace period of 1 hour, then choose a 24/7 time schedule for your new SLA plan, and then click "add plan". After that, click "add new SLA plan" again, then name your new SLA plan "SEV-B", then give your new SLA plan a grace period of 4 hours, then give your new SLA plan a 24/7 time schedule, and then click "add plan". Finally, you will need to click "add new SLA plan" once more, then name your new SLA plan "SEV-C", then give your new SLA plan a grace period of 8 hours, then give your SLA plan a "Monday - Friday 8am - 5 pm with U.S. Holidays" schedule, and then click "add plan". Now you have created 3 SLA plans. Example above.
</p>
<br />
<img src="https://i.imgur.com/kDSvScq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 Next, we will be creating help topics for osTicket. First, you will need to make sure you are on the admin panel, then click "manage", then click "help topics", and then click "add new help topic". After that, name your first help topic "Business Critical Outage, and then click "add topic". Next, you will need to add 3 more help topics, name the second "Personal Computer Issues", name the third "Equipment Request", and name the fourth "Password Reset". Now you have created help topicd for osTicket. Examples above.
