<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket Post-Install Configuration
  
  
  Creating/Configuring Roles, Departments, Teams</h1> 
This tutorial outlines the post-install of the open-source help desk ticketing system osTicket as an "Agent"<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Configuration Objectives</h2>

"Agents" are given access to the help desk with the intent to respond and resolve the tickets. 
When adding an Agent to the help desk, they will need to be assigned to a Primary Department and
given a Primary Role for the Tickets/Tasks routed to that department. Agents can be given Extended
Access to additional departments of the help desk as well as assigned different Roles to those departments.
- What are Roles? 
- What are Departments? 
- What are Teams? 
  


<h2>Configuration Steps</h2>

<p>

 ![configure roles1](https://github.com/user-attachments/assets/001beca8-4edc-4323-bee7-ecc3a153dc68)
 

</p>
<p>

Under the Agent Panel > Click Roles > Click Add New Role > Fill Out the Appropriate Information

Roles are the permissions granted to agents per department that they have access to. Role permissions include: 

Ability to assign tickets, close tickets, create/open tickets on behalf of others, delete tickets, edit tickets, and more.
</p>
<br />

<p>


![Add Departments](https://github.com/user-attachments/assets/15452a99-5ee6-469a-9560-99f1ad70372b)

</p>
<p>
Under the Agent Panel > Click Department > Click Add New Department > Fill Out the Appropriate Information

Since tickets are routed through departments in help desk, there are many settings that can be set for each department.
</p>
<br />

<p>


![Add Team ](https://github.com/user-attachments/assets/65fdca12-1031-4025-98ae-d320adfcf2a8)

</p>
<p>

 
Under the Agent Panel > Click Team > Click Add New Team > Fill Out the Appropriate Information

Teams allow you to pull agents from different departments and organize them to handle a specific issue or user 

via a help topic or ticket filter. Having Agents from different Departments assigned to a Team will supersede 

the parameters of the Agents’ Department rules. For example, you can create a Help Topic associated with a 

particular product you produce, and assign it to a Team of specialist Agents from different Departments.
</p>
<br />
