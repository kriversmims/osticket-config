
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This repository outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Roles
- Departments
- Teams
- Agents
- Users
- SLA's
- Help Topics

<h2>Configuration Steps</h2>

<!--ROLES-->
<p>
<img src="https://github.com/user-attachments/assets/91e314b4-f14b-424f-b42c-181c4aabba22"/>
</p>
<p>
<b>Roles</b> | Roles in osTicket define what actions a staff member (agent) can perform within the helpdesk system. They are tied to departments and help establish permission control for managing tickets, users, and internal workflows. In this instance, I created a new role called "Supreme Admin" and gave all permissions to this role.
</p>
<br />

<!--DEPTs-->
<p>
<img src="https://github.com/user-attachments/assets/8f564b2e-ff52-4157-8c61-eeeaaadcfcc4"/>
</p>
<p>
<b>Departments</b> | Departments in osTicket are organizational units used to categorize and manage incoming tickets. They help route tickets to the right group of staff (agents) and control ticket visibility, access, and workflow based on team responsibilities. In the image above, I added a "SysAdmins" department. A SysAdmin's department in osTicket would typically be responsible for handling system-level support requests and internal infrastructure issues. 
</p>
<br />

<!--TEAMS-->
<p>
<img src="https://github.com/user-attachments/assets/1282be03-920b-4a00-9d5a-846158ddc871"/>
</p>
<p>
<b>Teams</b> | Teams in osTicket are groups of staff members (agents) organized to collaborate on tickets across departments. Unlike departments, which define ticket ownership and access boundaries, teams offer flexibility by allowing staff to work together regardless of their departmental assignment. In addition to the default "Level 1 Support", I added three new teams: the Incident Response team, the Network Support Team, and the Onboarding Team.
</p>
<br />

<!--AGENTS-->
<p>
<img src="https://github.com/user-attachments/assets/c1315768-2f55-4bc9-a6b1-16af5ed0350b"/>
</p>
<p>
<b>Agents</b> | Agents (aka staff members) in osTicket are the users responsible for managing, responding to, and resolving support tickets. They form the operational core of the helpdesk, interacting directly with users to provide assistance and support. I created Jane as a system admin, and John as a support team member.
</p>
<br />

<!--USERS-->
<p>
<img src="https://github.com/user-attachments/assets/85950b06-0e58-4d2e-83b6-18d3da80164e"/>
</p>
<p>
<b>Users</b> | In osTicket, users are the end customers or requesters who submit tickets. In this scenario, I created two, Karen and Kendrick.
</p>
<br />

<!--SLAs-->
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>SLA's</b> Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<!--HELP TOPICS-->
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<b>Help Topics</b> Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
