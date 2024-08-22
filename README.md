<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />






<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Allow anyone to create tickets
- Allow anyone to create tickets
- Configure Users (customers)
- Configure SLA
- Configure Help Topics


<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/wIWquT0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Roles
First, go to the Admin Panel in the top right then select agents and then roles. We're going to make the "Supreme Admin" role which gives someone all of the permissions.
</p>
<br />

<p>
<img src="https://i.imgur.com/J1FMYYL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Departments


Next we're going to add a department, which means which area of the company an employee would work in and what permissions are granted to them so they can do their job (Accounting, HR, System Admins etc.)
In the Admin panel go to agents then departments. Name it System Admins
</p>
<br />

<p>
<img src="https://i.imgur.com/2UV4T1S.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Teams

Now we'll make some teams. Usually, a company will have more teams but for now, we can just put Level I and Level II support. Head back to the Agents section in the Admin panel then go to Teams

</p>
<br />

<p>
<img src="https://i.imgur.com/hvIzzF4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Allow anyone to create tickets

Everyone needs to be able to make tickets so we're gonna change the permissions by heading to settings and then user settings. We'll make it so it requires only a to make a ticket




</p>
<br />

<p>
<img src="https://i.imgur.com/Ih0guaX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Agents (workers)


In the admin panel go to users then add new, I added these two tests "agents" Jane and John Doe, they're going to get placed into a department and given permissions




</p>
<br />

<p>
<img src="https://i.imgur.com/KmMkf6p.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Users (customers)


These are just customers' user accounts they won't have permissions outside of being able to send in a ticket
Agent panel > Users > Add New


</p>
<br />

<p>
<img src="https://i.imgur.com/g8IAvU5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure SLA
We're going to make Service Level Agreements or SLAs. Every company has some form of SLA to determine how important each ticket is and in which order or even what time to complete them. For now, we're just going to put the basic ABC model. A good rule of thumb to bring into the workplace if your boss did not specify is to finish boss tickets first then customer tickets and keep going down in order of "importance" and/or deadline
We make SLAs by going to Admin Panel > Manage > SLA
Each severity rating means something different as listed below:

-Sev-A (1 hour, 24/7) 
-Sev-B (4 hours, 24/7)
-Sev-C (8 hours, business hours)



</p>
<br />

<p>
<img src="https://i.imgur.com/hXseV70.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Help Topics


Finally, we're gonna add help topics. These are what a customer or whoever is making a ticket would see while reporting their issue. This makes things much easier to organize when it's time to put a severity rating on a ticket

In the admin panel go to manage and then help topics
You can add as many topics as you feel like you need but common issues such as "Personal Computer Issues" "Equipment Request" or Password Resets are a must

<h1>Now you can configure osTicket!</h1>
<p>The photos in this demonstration are not my own and are only for instructional purposes. (I ran out of free credit hours on Azure) </p>
