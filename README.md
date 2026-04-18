# post-install-config

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

 - Click on specific positions for a better understanding!
 	- [Roles](https://docs.osticket.com/en/latest/Admin/Agents/Roles.html)
	- [Departments](https://docs.osticket.com/en/latest/Admin/Agents/Departments.html)
	- [Teams](https://docs.osticket.com/en/latest/Admin/Agents/Teams.html) 
	- [Agents](https://docs.osticket.com/en/latest/Admin/Agents/Agents.html)
	- [Users](https://docs.osticket.com/en/latest/Agent/Users/User%20Directory.html).
	- [Service Level Agreement(SLA)](https://docs.osticket.com/en/latest/Admin/Manage/SLA%20Plans.html)

<h3>Step 1: Open osTicket and Log in, use the credentials you made during the installation tutorial. </h3>

<p>
<img src="https://i.imgur.com/JgZbVg5.png" height="80%" width="80%" alt="Disk Sanitization Steps]"/>
</p>
<p>

<h3>Step 2: Configure Roles </h3>
Make sure you are in the Admin panel (check the top right of the screen to see which panel you are in. If it says Agent Panel you are in the Admin panel.)

Select the Agent tab, Roles, then Add new role. Name it Supreme Admin, then select the permissions tab and check every box under the tickets, tasks and knowledgebase sections. Now click add role.

</p>
<br />

<p>
<img src="https://i.imgur.com/NPclNBp.png" height="80%" width="80%" alt="Disk Sanitization "/>
</p>
<p>
<p>
<img src="https://i.imgur.com/ng60IFq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/dfEzAAq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/nypR3fA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/u7vzMAW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/rUX6Ir4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h3>Step 3: Configure Departments</h3>
Ensure you are still in the admin panel, select the agent tab, departments, and add new department. 

We'll name it System Administrators. Now select Create Department.

</p>
<br />

<p>
<img src="https://i.imgur.com/K4810m4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/jXdzzlC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/Y2eFzR4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
<img src="https://i.imgur.com/Zs61keM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/uJ9wzf6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/K1IEis4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/0kvxGq1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
<img src="https://i.imgur.com/nBBrl51.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/IpziKtV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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

</p>
<br />
</p>
<br />

<p>
<img src="https://i.imgur.com/oxc03Py.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/UnfoIIE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/L9pjrc4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/5GlKPBc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/mME12aR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/mcvBVqW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

We will now create another agent but their name will be John this time. So

- Name: john.doe(@)osticket.com
- Username: john.doe
- Follow the same steps as above, except make some changes to the Primary Department. Select the department dropdown menu and click support. Then for the Role dropdown menu click View Only.

</p>
<br />
</p>
<br />

<p>
<img src="https://i.imgur.com/mVBs4NU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/mRp9o3N.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/a7GYrDi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/kx62jc4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<h3>Step7: Configure Users</h3>
For this we'll need to be in the agent panel, so click agent panel in the top right. You'll know if your in it if it says Admin Panel top right.

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
<img src="https://i.imgur.com/7Oq6b3M.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/RvG2coe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/SIWHNc8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/IGYVGLR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
<img src="https://i.imgur.com/grAE7bU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/3mKbcLR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/Vo2izJE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/QHV00J7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/Z75MrFE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
<img src="https://i.imgur.com/8ghNqqk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/CD5zBpl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/uK05c0L.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/QQlWdWY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/UKcwWQt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/a8AzSGv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/FOm5zBB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
