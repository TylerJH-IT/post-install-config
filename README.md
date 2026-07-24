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

<h2>Good Things to Know</h2>

 - Links needed for this
	- http://localhost/osTicket/scp/login.php

 - Click on specific positions for a better understanding!
 	- [Roles](https://docs.osticket.com/en/latest/Admin/Agents/Roles.html)
	- [Departments](https://docs.osticket.com/en/latest/Admin/Agents/Departments.html)
	- [Teams](https://docs.osticket.com/en/latest/Admin/Agents/Teams.html) 
	- [Agents](https://docs.osticket.com/en/latest/Admin/Agents/Agents.html)
	- [Users](https://docs.osticket.com/en/latest/Agent/Users/User%20Directory.html).
	- [Service Level Agreement(SLA)](https://docs.osticket.com/en/latest/Admin/Manage/SLA%20Plans.html)

<h2> Using the admin panel to create roles and departments </h2>

<h3>Step 1: Open osTicket and Log in, use the credentials you made during the installation tutorial. </h3>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h3>Step 2: Configure Roles </h3>
Make sure you are in the Admin panel (check the top right of the screen to see which panel you are in. If it says Agent Panel you are in the Admin panel.)

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h3>Step 3: Making the admin roles</h3>
Select the Agent tab, Roles, then Add new role. Name it Supreme Admin, then select the permissions tab and check every box under the tickets, tasks and knowledgebase sections. Now click add role.

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h3>Step 4: Configure Departments</h3>
Ensure you are still in the admin panel, select the agent tab, departments, and add new department. 

We'll name it System Administrators. Now select Create Department.

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h2> Creating teams and allowing users to create tickets.</h2>

<h3>Step 5: Configure Teams </h3>
Select the Agent tab again, Teams, and add new team. 

Name it Level II Support. 

Then go to the Members tab and select yourself in the select agent dropdown menu. 

Now select create team.

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h3> Step 6: Allow anyone to create tickets.</h3>
Select settings then Users. Make sure the following box is unchecked. 

- Registration Required: Require Registration and login to create tickets.

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h2> Creating agents that can work on tickets. </h2>

<h3>Step 7: Configure Agents part 1</h3>
Select the agent tab one last time and click new agents. 

For our first agent they will be.

- Name: jane Doe
- Email: kane.doe(@)osticket.com
- Username: jane.doe
- Then click Set Password and uncheck the box that says "Send the Agent a Password Reset Email"
- Set your password to anything you like, and uncheck the box that says "Require Password Change at Next Login", now select Set.

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h3> Step 8: Configure agents part 2</h3>

Once you've made Jane's password we'll be giving her roles and put her in a team.

- In access select department, support, then select supreme admin in the roles.
- Select Team tab, select the team dropdown menu, Level II support, and select add.
- Now click create.

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h3>Step 9: Configure Agents part 3</h3>

We will now create another agent but their name will be John this time. So

- Select Agents then Add New Agent
- Name: john.doe(@)osticket.com
- Username: john.doe
- Make sure the password is different from Janes
- Follow the same steps as Jane Doe, except make some changes to the Primary Department. Select the department dropdown menu and click support. Then for the Role dropdown menu click View Only. Do not assign him to a team

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h2> Creating users for tickets.</h2>

<h3>Step 10: Configure Users part 1</h3>
For this we'll need to be in the agent panel, so click agent panel in the top right. You'll know if your in it if it says Admin Panel top right.

Then select the Users tab then click add user.

- Email Address: Karen(@)osticket.com
- Full Name: Karen Karen
- Select add user.

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h3> Step 11: Configure Users part 2</h3>

Select the users tab again to create another user.

- Email Address: Ken(@)osticket.com
- Full Name: Ken Ken
- Select add user

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h2> Creating SLA's</h2>

<h3>Step 12: Configure Service Level Agreements (SLA) part 1</h3>
Back to the admin panel so first click adimn panel in the top right.

We will be creating three SLA's for this.

Select the manage tab, SLA, add new SLA plan.

- Name: Sev-A
- Grace period: 1
- Schedule dropdown menu: 24/7
- Select Add plan.
- Select the manage tab, SLA, add new SLA plan.

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h3> Step 13: Configure Service Level Agreements (SLA) part 2 </h3>

- Name: Sev-B
- Grace Period: 4
- Schedule dropdown menu: 24/7
- Select add plan
- Select the manage tab, SLA, add new SLA plan one last time.

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h3> Step 14: Configure Service Level Agreements (SLA) part 3 </h3>

- Name: Sev-C
- Grace Period: 8
- Schedule dropdown menu: Monday - Friday 8AM - 5PM with U.S Holidays
- Select add plan

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h2> Configuring help topics</h2>

<h3>Step 15: Configure help topics</h3>
We will create five help topics.

Select the Manage tab, Help topics, add new help topic.
After making each help topic, you'll need to click Help Topics then Add New Help Topic each time.

- Business Critical Outage. Report a problem.
- Make another one
- Personal Computer issues. Report a problem/ access issue.
- Another one
- Equipment Request. General Inquiry.
- Another
- Password Reset. Report a problem.
- One more
- Other. General Inquiry.

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
</p>
<p>
