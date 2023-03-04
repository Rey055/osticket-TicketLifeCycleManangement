# osticket-TicketLifeCycleManangement


<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS Enabled on Virtual Machine)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Admin roles and permissions
- Setting SLA's and Help topics
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
<img src="https://i.imgur.com/x71ivC4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First we start with our freshly installed osTicket agent dashboardpage. Here we have many Options first we want to set up our ticket systems, roles, teams, SLA's etc.
</p>
<br />

<p>
<img src="https://i.imgur.com/512sQ5k.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now we wil have to confiure our roles. First, we will creat our admin role. On the upper right be sure to click on admin panel. Once there click on the agent tab. once on here click on the roles sub menu. once here Name your role and add your preferred permissions. In this example a Supreme Admin role was created, this role has all permmissions from answer tickets, editing them and closing them. 
</p>
<br />

<p>
<img src="https://i.imgur.com/FwLQmtQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now we will create our department. To do this its still whith inn the admin panel, right next to the roles sub tab, to the right. Once you click on dpeartment sub tab. click create addd new department. In my example it will be named System Administrators. On this department creation screen, you set various things, such as what SLA, to assign to it, Its schdule, its manager, etc. 
</p>
<br />

<p>
<img src="https://i.imgur.com/Cre9R5z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now we will need to create a team or teams. This is located in the same agent panel. Its located in the teams icon. Now a similar menu related to the other two tabs is presented.We will be creating two teams, One support Level 1 and support Level 2. So for any of them be sure give it an apporiate name. whith in this menu you can give it its own status either closed or open, what lead is for each team, and the members a part of the team.
</p>
<br />

<p>
<img src="https://i.imgur.com/vMrAieA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
We need to enable tickets to be submitted by users. This is perhaps one of the most importsnt feature to ensure it's created. This is found in the settings tab then sub tab of user settings. Be very sure to have Registration Required is checked. So tickets can be logged and easier to organize and keep track of.
</p>
<br />

<p>
<img src="https://i.imgur.com/jfDt4jW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
since all of this is done we need to configure our agents, to allow them to respond to client tickets to give feedback and technical advise. Then we return to the agent panel. We then head over to users sub menu we then click add new. Here wer are gonna add two agents one Jane and one Ken.
</p>
<br />

<p>
<img src="https://i.imgur.com/mPaQ6jd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
its time to setup our test users to ensure our ticketing system is in working condition. To do this wee need to create test users. to create these, click on the upper right and switch to agent panel. Once your there click on user tab then click on add user. we will be adding one, for this example, named joe. We will need to add an email, password and Name for our user. 
</p>
<br />

<img src="https://i.imgur.com/qvx4jTQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now it's time to set our SLA. it is located in the admin panel, mange sub menu, then sla, click on add an SLA. Here on will be made. Its grace period will be set and its schdule.
</p>
<br />

<img src="https://i.imgur.com/c66Wt0U.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Latly, But not least, we nned to add some helptopic area, so our users will be able to troubleshoot and see possible solutions. Solutions for issues that have already been solved and such.It located within the same tab of manage, click on help topics and then add new help topic. for "Password recovery" and "business critical outage."</p>
<br />
