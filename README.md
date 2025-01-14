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

- Configure Roles (for grouping permissions)
Admin Panel -> Agents -> Roles
Supreme Admin

- Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
Admin Panel -> Agents -> Departments
SysAdmins

- Configure Teams
Admin Panel -> Agents -> Teams (Pull Agents from different Departments)
Online Banking

- Configure Agents (workers)
Admin Panel -> Agents -> Add New
Jane (Dept: SysAdmins)
John (Dept: Support)



<h2>Configuration Steps</h2>

![Screenshot 2025-01-13 210256](https://github.com/user-attachments/assets/f87c273b-8254-429f-8082-3ef6ee6aa38d)

<p>
This is where you can define the permissions and access levels associated with this role. Permissions determine what agents with this role can do within the system (e.g., manage tickets, modify settings, view reports).
</p>
<br />
___________________________________________________________________________________________________________________________


<img width="434" alt="image" src="https://github.com/user-attachments/assets/0ee7f353-4c34-46bd-9546-30d734d31cfe" />
<p>
 Creating a new department, which is used to organize agents and tickets within the osTicket system.
</p>
<br/>
___________________________________________________________________________________________________________________________

![Screenshot 2025-01-13 211919](https://github.com/user-attachments/assets/6e26327f-e24a-4e7e-83c0-4f879f59e9f9)



<p>
Used to create a group of people that are in different departments. 
</p>
<br />
___________________________________________________________________________________________________________________________

![Screenshot 2025-01-13 212356](https://github.com/user-attachments/assets/1da1e6f8-7c1a-44b5-a3ee-c1e4feb0bf9c)

<p>
 Determines the agent's department access and their role within the system.
 <p />

<br />
___________________________________________________________________________________________________________________________
