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

- Configure roles, departments, and teams
- Allow users to create tickets
- Configure Agents and Users
- Configure SLA 
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/5EWBLpb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In my OSticket account I’m starting at roles. Which are permissions given out to users depending on their position depending on what department they’re in. I’m acting agent in OS ticket, so I go to the role tab and create a new role called, “Supreme Admin”. From there I can enable or disable permissions at my discretion. From there I click on the agent’s tab, then departments, where I am shown existing departments such as Maintenance and Support. I have created a new department called System Administrators. I then want to create a team, so I click the Teams tab that displays all teams, which only consists of Level I Support. So, I added a team called Level II Support where I made myself the Team Lead as you can see in the screenshot above. 
</p>
<br />

<p>
<img src="https://i.imgur.com/gJKCrJ2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I then want to allow anyone the ability to create tickets. So, I go to the user’s settings where I can confirm that “require registration and login to create tickets” is unchecked, which allows anyone to create tickets. I then created agents to answer incoming tickets, so I clicked the agent tab and typed in basic information to create Jane and John. I can put them into any department I choose, as well as dictate their permissions. I then create users that can send tickets to my agents when encountering a work-related computer issue, which are named Karen and Ken. I now want to create SLA (Service Level Agreement) plans to dictate the priority and timely manner that a ticket needs to be resolved per the company protocols. As you can see from the screenshot above. 
</p>
<br />

<p>
<img src="https://i.imgur.com/IQe8WS3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Help Topics will help decide what department your ticket is going to. Here I have added 4 new help topics to the 4 default help topics. The first one being Business Critical Outage. The second being Personal Computer Issues. The third being an Equipment Request. And the fourth being Password Reset. In these help topics I’ve created, I can put internal notes to help specify what the issue is. That might help the receiving agent in the appropriate department to figure out the issue faster, which is best for overall work efficiency. I am also able to set the status of the help topic, which can indicate to the receiving agent whether it’s ranging from high priority to low priority. As you can see from the screenshot above. 
</p>
<br />
