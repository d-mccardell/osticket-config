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

- Roles
- Departments
- Teams
- Agents
- Users
- SLA
- Help Topic

<h2>Configuration Steps</h2>

<img src="https://github.com/d-mccardell/post-install-config/assets/116754993/efbb39b9-8422-417d-81c1-92e36af322fc" height="50%" Width="50%"/>
<p>
Make sure you are logged on to the virtual machine that has osTicket. 
</p>
<br />
<br/>

<img src="https://github.com/d-mccardell/post-install-config/assets/116754993/d79de17c-94b7-44fa-b953-d7ae8617d60c" Height="50%" width="50%"/>
<p>Log in to osTicket with your credentials.</p>
<br/>
<br/>

<img src="https://github.com/d-mccardell/post-install-config/assets/116754993/d8277fcd-8a21-4641-a0cc-87a96adfc27f" height="50%" width="50%"/>
<p>
In the admin panel you can create roles. Roles are the permissions assigned to agents in different departments.. Each role can have different permissions and access depending on department. To create a role click on Admin Panel--> Agents--> Roles--> click on Add a New Role. 
</p>
<br />
<br/>

<img src="https://github.com/d-mccardell/post-install-config/assets/116754993/ffe9502b-fd3c-440d-a39b-96f1d5d8eb11" height="50%" width="50%"/>
<img src="https://github.com/d-mccardell/post-install-config/assets/116754993/ba1be657-f46b-457b-829c-348a8680fa53" height="50%" width="50%"/>
<p>
In this case, we will create a role named "Supreme Admin" with complete access and permissions to all tickets, tasks, and knowledgebase.
</p>
<br />
<br/>

<img src="https://github.com/d-mccardell/post-install-config/assets/116754993/11300ec7-0b58-4223-8632-56f0e881eac8" height="50%" width="50%"/>
<p>Next, we wil add departments. Since tickets can be routed to different departments, each department can have a different set of settings such as SLA and ticket assignment. <br/>
Here, we have created a "systems administrators" departments with default settings.
<br/> To add a department go to Admin Panel--> Agents--> Departments--> Add New Department.</p>
<br/>
<br/>

<img src="https://github.com/d-mccardell/post-install-config/assets/116754993/25d21caa-c836-4110-9bcf-d52992f1d42a" height="50%" width="50%"/>
<p>Next, add a team. Teams allow you to pull agents from different departments to handle certain tickets. In this instance, we have created a Level II Support team. <br/> To add a team go to Admin Panel--> Agents--> Teams--> Add New Team</p>
<br/>
<br/>

<img src="https://github.com/d-mccardell/post-install-config/assets/116754993/64bd72e4-1ff5-44a7-a5c0-a585f280513c" height="50%" width="50%"/>
<p>Now we will add agents. Agents can be given different levels of access when adding them. <br/> To add a new agent go to Admin Panel--> Agents--> Agents--> Add New Agent. </p>
<br/>
<br/>

<img src="https://github.com/d-mccardell/post-install-config/assets/116754993/f5972e91-8622-4bd7-a225-66148ab85612" height="50%" width="50%"/>
<p>Make sure to assign a primary department to the new agent.</p>
<br/>
<br/>

<img src="https://github.com/d-mccardell/post-install-config/assets/116754993/fd87f491-aa18-46f5-9ef1-2b8837fa7207" height="50%" width="50%"/>
<p>Next we will add users. Users are the ticket owners of the tickets in the help desk.
<br/>
To add users got to Agent Panel--> Users--> User Directory--> Add User</p>
<br/>
<br/>

<img src="https://github.com/d-mccardell/post-install-config/assets/116754993/6dff8083-2300-457d-b90c-894c00998523" height="50%" width="50%"/>
<p>Now we will add SLA or Service Level Agreements.The purpose of the SLA Plan is to provide a length of time in which the help desk Administrator expects tickets to be closed.<br/>
To add a SLA go to Admin Panel--> Manage--> SLA--> Add New SLA Plan</p>
<br/>
<br/>

<img src="https://github.com/d-mccardell/post-install-config/assets/116754993/00a5ea8c-9bc1-4f0c-8918-795a4948ed48" height="50%" width="50%"/>
<p>Finally, we will add Help Topics. Help Topics will help streamline your end-user’s help desk experience to ensure proper assignment and prompt response to the ticket.
<br/>
To add Help Topics simply got to Admin Panel--> Manage--> Help topics--> Add New Help Topic</p>


