<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>

<p>

  The first step is to verify that you are on the "Admin Panel" page. You will do so by clicking on the red highlighted section and your screen you should look similar to the one below.
 

<img src="https://i.imgur.com/wD1C0UR.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next step is to create the roles, You will want to click on the "Agents" tab, then the "roles" tab, and click on the "Add new role" option.

  <img src="https://imgur.com/QY7jIwj.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>

From there, you will go ahead and name the role "Supreme Admin".

<img src="https://imgur.com/MKPJtwj.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>

Make sure all boxes are checked on the "Tickets", "Tasks", and "Knowledgebase" tabs. Select "Add Role".

<img src="https://imgur.com/ATNLc7L.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>

<img src="https://imgur.com/Qo8CM87.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>

<img src="https://imgur.com/QBbWdtU.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>

Create a new department. You will do so by going to the "Agents" tab and then clicking on the "Departments" tab. Select the " Add New Department" option.

<img src="https://imgur.com/vheKn0Y.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>

You will name the new department "System Administrators". Leave SLA option default. Once an SLA is configured we will go back and update. Select " Create Dept".

<img src="https://imgur.com/7ZxZlUD.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>

Create a new Team. go to the "Agents" tab, then go to "Teams". Select the "Add New Team" option. Name the team "Level II Support"

<img src="https://imgur.com/Mf5HU4d.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>



<img src="https://imgur.com/5hwpgLx.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>

Go over to the "Members" tab. As you are the only existing member at this point, add yourself to the team. Select "Create Team".

<img src="https://imgur.com/kDj0Ysc.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>

Go to the "Settings" tab, Click on "Users". Verify that the "Registration Required" option is not checked, to allow other users to create tickets.

<img src="https://imgur.com/eLHnxYe.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>

Next step is to create the agents
  - Jane Richards
  - John Richards

Go to the "Agents" tab, Then Click on the " Add New Agent" option

<img src="https://imgur.com/v5UsGGw.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>

Fill in the information below. Select "set password".

<img src="https://imgur.com/bxyG8xU.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>

Make sure that both boxes are not checked. Set the password to "Password1". Select "set"

<img src="https://imgur.com/l47YVrD.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>

For Jane, select the "System Administrators" department. Apply the "Supreme Admin" role

<img src="https://imgur.com/9LICNKA.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>

Go to the "teams" tab. Select the "Level II Support" team. Create the agent.

<img src="https://imgur.com/oC51wGh.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>

Create the agent "John"
Fill in the information

<img src="https://imgur.com/c6lGrSg.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>

Set the password to "Password1". Be sure that both boxes are not checked. select the "set" option

<img src="https://imgur.com/l47YVrD.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>

Select The "Support" department. John's role will be "View only". Create the agent.

<img src="https://imgur.com/QbwhhxO.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>

