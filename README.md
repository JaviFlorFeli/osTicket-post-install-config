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

Set the password to "Password1". Be sure that both boxes are not checked. select the "set" option.

<img src="https://imgur.com/l47YVrD.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>

Select The "Support" department. John's role will be "View only". Create the agent.

<img src="https://imgur.com/QbwhhxO.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>

Click on the highlighted option. It will take you to the agent panel.

<img src="https://imgur.com/ZqzLXex.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>

We will create our "users" for this lab 
  - Karen
  - Ken

Go to the "Users" tab and then click on "User Directory". Select "Add New User".

<img src="https://imgur.com/ihzorGY.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>

Fill the information in the highlighted boxes, Select "Add User"

<img src="https://imgur.com/SfAcQ37.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>

Follow the same steps for Ken as you did for Karen. You have now created both users for the lab.

<img src="https://imgur.com/fh9DzED.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>

The next step is to configure an SLA plan.
  - Head back to the Admin Panel
  - "Manage" tab
  - "SLA"
  - Select "Add New SLA Plan"
    -  SEV-A
    -  SEV-B
    -  SEV-C  

<img src="https://imgur.com/zPrZf5u.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>

Grace period: 1 hour

Schedule: 24/7

<img src="https://imgur.com/C5BayFO.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>

Grace period :4 hours

Schedule: 24/7

<img src="https://imgur.com/UPcCD9r.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>

Grace period: 8 hours

Schedule: Mon-Fri 8am-5pm

<img src="https://imgur.com/gVvLhXU.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>

Next step is to configure help topics to be assigned to the tickets.
- Select "Manage" tab
- "Help Topics" tab
- "Add New Help Topics"

<img src="https://imgur.com/nSJeIBn.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>

  - Business Critical Outage
  - Personal Computer Issues
  - Equipment Reset

<img src="https://imgur.com/RecbCDh.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>



<img src="https://imgur.com/wg3f4m7.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>



<img src="https://imgur.com/yLo5VuH.jpeg" height="40%" width="40%" alt="Disk Sanitization Steps"/>

