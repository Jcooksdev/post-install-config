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

- Configure Roles and Departments 
- Configure Teams and allow anyone to create ticekts 
- Now we will configure agents/workers and user/customers 
- Configure SLA
- Configure Help Topics 

<h2>Configuration Steps</h2>

<p>

<p>
In this first part of post installation for osTicket, we will create a role called Supreme Admin. To essentially give our "agents" access to everything. Tickets circulate through departments in help desk so we will create one for this project as well. 
</p>
<br />
<p>

 
Creating our teams allows you to pull agents from differnt departments into one team which is demonstrated above. To create said team you will select admin panel, locate the agents tab and click on teams then add new team and fill out information. Adding agents to the team and checking corresponding box next to the team name. Then allow anyone to create tickets through setting, user settings fill out registration and login back in to create tickets. 
</p>
<br/>

</p>
<p>
In this step we will add agents. I created the user (essentially our workers) Jane and John Doe for the activity. We go through the admin panels and under agents to add new agents. With the creation of user through the agent panel you can add the user to an organization of the help desk.
</p>
<br />

</p>
<p>
SLA Plans are placed to provide a length of time in which Admin expects tickets to be closed. They can be creatd by the admin panel, manage, SLA Plans adding a new SLA plan. Finally we will configure help topics, creating topics such as Business Critical Outage, Personal Computer Issues, Equipment Request, and Password Reset to be used in the next project set. 
Now you're finished!
</p>
<br/>
