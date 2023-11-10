<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles, Departments and Teams
- Configure Agents and Users
- Configure SLA based on company needs
- Configure Help Topics for company needs


<h2>Configuration Steps</h2>

<p> 
<img src="https://i.imgur.com/dsXO3fk.png"/>


</p>
<p>
- Configuring the "Supreme Admin" role in osticket from the Admin Panel. All agents placed under the "Supreme Admin" role will now be granted permission to have access to any department associated with the "Supreme Admin" role. 
</p>
<br /> 

<p> 
<img src="https://i.imgur.com/DElnV6X.png"/> 
</p> 
<img src="https://i.imgur.com/sLfglbG.png"/>
</p> 
<p>
- Configuring the "Support" Department in osTicket from the Admin panel. Different agents can now be assigned to the various different departments within the system so tickets can be resolved accordingly. 
</p>
<br />

<p>
<img src="https://i.imgur.com/S5VBRv7.png"/>
</p>
<p>
- Configuring "Level II spport" as another "Team" within the sysytem. This will allow different agents to be organized within the different teams to resolve speceific tickets that are placed in different levels in the system. 
</p>
<br /> 

<p> 
<img src="https://i.imgur.com/iS8UEbC.png"/> 
</p> 
<img src="https://i.imgur.com/42owwvP.png"/> 
</p> 
<p> 
- Configure an "Agent" as "Jane Sinclair" within the Admin Panel. "Jane Sinclair" was then assigned to "System Administrator" Department to be given primary role of that department. 
</p> 
<br /> 

<p> 
<img src="https://i.imgur.com/OeQBJwl.png"/> 
<p>
<img src="https://i.imgur.com/7yalCMp.png"/> 
</p> 
<p> 
- Configure a "User" as "Kathy Stewart" within the Admin Panel. As a user, "Kathy Stewart" can now create tickets within the help desk user portal. 


<p> 
<img src="https://i.imgur.com/A0hPTsU.png"/> 
<p> 
<img src="https://i.imgur.com/uiDb1BW.png"/> 
</p> 
<p> 
- Configure "SLA (Service Level Agreement)" within the Admin Panel based on company requirements. Three SLA'S were added for the level of severity of each ticket in the osTicket System. The SLA above ranges from SEV A-SEV C (SEV A being highly critical). Each SLA was also given different grace periods based on severity in which they must be resolved by. The SLA can now be added to each ticket that comes in by the Administrator. 
</p> 
<br /> 

<p> 
<img src="https://i.imgur.com/2h5HMK9.png"/> 
<p> 
<img src="https://i.imgur.com/ryjBL0E.png"/> 
</p> 
<p> 
- Configure different "Help Topics" within the Admin Panel and assigning the different departments to it. The various "Help Topics" will be used to determine what department and Agent tickets will be routed to. "Help Topics" will also list SLA and any other priority of each ticket.

