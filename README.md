<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>Ticketing Systems: osTicket Post-Install and Setup 🪟</h1>
In this section I go through the process of setting up the "Company" Helpdesk Structure. This includes configuring roles, departments, teams, SLA configuration and help topics.

(Link Back to Main Project Contents Page is at the Bottom of this Repo)
<h2>Environments and Technologies Used</h2>

- Lenovo Ideapad 5 Pro 16gb AMD Ryzen 7
- Microsoft Azure Resource Group
- Microsoft Azure Windows 10 Pro version 22H2 - x64 Gen2 Virtual Machine
- osTicket Software and File Dependencies

<h2>Operating Systems Used </h2>

- Local Windows 11 Home Version 21H2</b>
- Windows 10 Pro version 22H2 Virtual Machine
  
<h2>List of Prerequisites</h2>

- Microsoft Azure Subscription
- Microsoft Azure Subscription Credit 

<h2>Installation, Setup, Resource Setup, Executing Functions</h2>

1. After successfully installing osTicket, below we can see our Agent/Admin Panel on the left and the User Panel on the right. The Agent and Admin Panels are used by the organisation internally to configure the Helpdesk structure, communicate and work through tickets. The "Support Center" or User Panel is used by the end user (whether this is an end-user as a customer or an internal department user) to create a support request and communicate with the agent dealing with their request.
</p>
<br />

<p>
<img src="https://imgur.com/pcdKKpB.png" alt="Image"/>
</p>
<p>
2. Within the Admin Panel, I configured permissions for the Main Admin in the Admin Panel. This allows this specific Agent to undertake the chosen tasks in the image. An Admin User who has access to this section can choose what permissions to give a certain Agent, depending on different factors such as their department, or position within the company. 
</p>
<br />

<p>
<img src="https://imgur.com/FEUltAL.png" alt="Image"/>
</p>
<p>
3. In this section we can see the Departments that are currently configured within our organisation. There are only 2 Departments so far which we can see are Maintenance and Support.
</p>
<br />

<p>
<img src="https://imgur.com/8V2Wn5n.png" alt="Image"/>
</p>
<p>
4. Below I created a Top Level Department for SysAdmins and assigned a Manager.
</p>
<br />

<p>
<img src="https://imgur.com/loJRTQo.png" alt="Image"/>
</p>
<p>
5. Next I created a Team called Finance.
</p>
<br />

<p>
<img src="https://imgur.com/TUzWyCl.png" alt="Image"/>
</p>
<p>
6. In this section I configured the settings to not have to allow End-Users to register in order to create a ticket. This would be ideal as it would allow customers and end-users to easily request support with little friction or having to create an account.
</p>
<br />

<p>
<img src="https://imgur.com/XC5fISn.png" alt="Image"/>
</p>
<p>
7. At this stage I created an Agent and assigned an email address to them. Permissions, teams and access were assigned to each Agent at a later stage. 
</p>
<br />

<p>
<img src="https://imgur.com/MaY2FqO.png" alt="Image"/>
</p>
<p>
8. Next I created a User and inputted information into the following fields. 
</p>
<br />

<p>
<img src="https://imgur.com/icRncWi.png" alt="Image"/>
</p>
<p>
9. Below is our User created with the displayed details.
</p>
<br />

<p>
<img src="https://imgur.com/yziscbe.png" alt="Image"/>
</p>
<p>
10. Next I created custom SLA Agreements. Creating SLA Agreements (Service Level Agreements Agreements) allow Agents to assign prioritise and categorise different tickets based on the level of service required to complete them. 
</p>
<br />

<p>
<img src="https://imgur.com/o9qpN5G.png" alt="Image"/>
</p>
<p>
11. Here we can see our SLA Agreements labeled as A, B and C and assigned with different grace periods in hours.
</p>
<br />

<p>
<img src="https://imgur.com/yNEdnzi.png" alt="Image"/>
</p>
<p>
12. Help Topics are categories that End-Users can choose to assign their Support Requests to. This helps Agents understand the End-Users problems better and work through tickets more efficiently.
</p>
<br />

<p>
<img src="https://imgur.com/bdP5hBg.png" alt="Image"/>
</p>
<p>
13. This is a list of possible Help Topics that represent categories of problems that End-Users may be experiencing. 
</p>
<br />

<p>
<img src="https://imgur.com/1Skq7Wg.png" alt="Image"/>
</p>
<p>
LINK BACK TO THE MAIN PROJECT CONTENTS PAGE - https://github.com/cyberwahid01/Azure-Compute-and-Networking
