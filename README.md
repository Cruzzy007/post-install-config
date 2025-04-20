# post-install-config
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Acknowledge Agent Panel vs Admin Panel
</h2>
<img width="504" alt="post-install-osticket step 1" src="https://github.com/user-attachments/assets/24dbd153-1bb1-4dec-9f58-0eaa1ff86f19" />

- Configure Roles (for grouping permissions)
- Admin Panel -> Agents -> Roles
- Supreme Admin
![post-install-osticket step 2](https://github.com/user-attachments/assets/ee44a0f0-d6bf-4afd-bb4d-a5534c644eea)

- Configure Departments (Ticket Visibility, Help Desk vs SysAdmins, vs Networking)
- Admin Panel -> Agents -> Departments -> add new department 
- SysAdmins

![post-install-osticket step 3](https://github.com/user-attachments/assets/459477d9-0388-47dc-b1a9-cbad1a039dfc)

- Configure Teams
- Admin Panel -> Agents -> Teams (Pull Agents from different Departments)
- Online Banking
  
![post-install-osticket step 4](https://github.com/user-attachments/assets/c41f39b9-5e80-49c3-9b48-47afabbc3eb8)

- Configure Agents (workers)
- Admin Panel -> Agents -> Add New
- Jane (Dept: SysAdmins)
- John (Dept: Support)
![post-install-osticket step 5](https://github.com/user-attachments/assets/c794055c-653c-4f4a-b2eb-98df57b0539b)

- Configure SLA
![post-install-osticket step 8](https://github.com/user-attachments/assets/1262343c-e09f-4879-9d6e-65bdb46323fd)

- Configure Help Topics (For when users create a ticket)
Admin Panel -> Manage -> Help Topics

![post-install-osticket step 9](https://github.com/user-attachments/assets/25c08ebc-8280-4d25-bda5-1bd2f78f3252)










