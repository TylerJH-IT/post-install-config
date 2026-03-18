# post-install-config

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Good Things to Know</h2>

 - Click on specific positions for a better understanding!
 	- [Roles](https://docs.osticket.com/en/latest/Admin/Agents/Roles.html)
	- [Departments](https://docs.osticket.com/en/latest/Admin/Agents/Departments.html)
	- [Teams](https://docs.osticket.com/en/latest/Admin/Agents/Teams.html) 
	- [Agents](https://docs.osticket.com/en/latest/Admin/Agents/Agents.html)
	- [Users](https://docs.osticket.com/en/latest/Agent/Users/User%20Directory.html).
	- [Service Level Agreement(SLA)](https://docs.osticket.com/en/latest/Admin/Manage/SLA%20Plans.html)

<h3>Step 1: Open osTicket and Log in, use the credentials you made during the installation tutorial. </h3>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h3>Step 2: Configure Roles </h3>
Make sure you are in the Admin panel (check the top right of the screen to see which panel you are in. If it says Agent you are in the Admin panel.)

Select the Agent tab, Roles, then Add new role. Name it Supreme Admin, then select the permissions tab and check every box under the tickets, tasks and knowledgebase sections. Now click add role.

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h3>Step 3: Configure Departments</h3>
Ensure you are still in the admin panel, select the agent tab, departments, and add new department. 

We'll name it System Administrators. 

Now select Create Department.

</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h3>Step 4: Configure Teams </h3>
Select the Agent tab again, Teams, and add new team. 

Name it Level II Support. 

Then go to the Members tab and select yourself in the select agent dropdown menu. 

Now select create team.

</p>
<br />
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h3> Step 5: Allow anyone to create tickets.</h3>
Select settings then Users. Make sure the following box is unchecked. 

- Registration Required: Require Registration and login to create tickets.

</p>
<br />
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h3>Step 6: Configure Agents</h3>
Select the agent tab one last time and click new agents. 

For our first agent they will be.

- Name: jane Doe
- Email: kane.doe(@)osticket.com
- Username: jane.doe
- Then click Set Password and uncheck the box that says "Send the Agent a Password Reset Email"
- Set your password to anything you like, and uncheck the box that says "Require Password Change at Next Login", now select Set.
- Then in extended access select department, support, then click add, and then supreme admin in the roles.
- Select Team tab, select the team dropdown menu, Level II support, and select add.
- Now click create.

We will now create another agent but their name will be John this time. So

- Name: john.doe(@)osticket.com
- Username: john.doe
- Follow the same steps as above, except make some changes to the Primary Department. Select the department dropdown menu and click support. Then for the Role dropdown menu click View Only.
- Then for Extended access, select department, support, and save changes.

</p>
<br />
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h3>Step7: Configure Users</h3>
For this we'll need to be in the agent panel, so click agent panel in the top right.

Then select the Users tab then click add user.

- Email Address: Karen(@)osticket.com
- Full Name: Karen Karen
- Select add user.

Select the user tab again to create another user.

- Email Address: Ken(@)osticket.com
- Full Name: Ken Ken
- Select add user

</p>
<br />
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h3>Step 8: Configure Service Level Agreements (SLA) </h3>
Back to the admin panel so first click adimn panel in the top right.

We will be creating three SLA's for this.

Select the manage tab, SLA, add new SLA plan.

- Name: Sev-A
- Grace period: 1
- Schedule dropdown menu: 24/7
- Select Add plan.
- Select the manage tab, SLA, add new SLA plan.
- Name: Sev-B
- Grace Period: 4
- Schedule dropdown menu: 24/7
- Select add plan
- Select the manage tab, SLA, add new SLA plan one last time.
- Name: Sev-C
- Grace Period: 8
- Schedule dropdown menu: Monday - Friday 8AM - 5PM with U.S Holidays
- Select add plan

</p>
<br />
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h3>Step 9: Configure help topics</h3>
We will create four help topics.

Select the Manage tab, Help topics, add new help topic.

- Business Critical Outage. Report a problem.
- Make another one
- Personal Computer issues. Report a problem/ access issue.
- Another one
- Equipment Request. General Inquiry.
- Another
- Password Reset. Report a problem.
- One more
- Other. General Inquiry.

</p>
<br />
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
