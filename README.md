<p align="center">
    <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Installation Configuration Guide</h1>
This guide outlines the key steps to configure osTicket for use as an effective ticketing system.<br />

<h2>Tools and Technologies Used</h2>

- **Microsoft Azure** (Virtual Machines/Compute)
- **Remote Desktop Connection**
- **osTicket**

<h2>Operating System Used</h2>

- **Windows 10 Pro** (21H2)

<h2>Configuration Process</h2>

<p>
    <img src="https://i.imgur.com/S33TPEZ.png" height="80%" width="80%" alt="osTicket Configuration"/>
    <img src="https://i.imgur.com/7HyoONM.png" height="80%" width="80%" alt="osTicket Configuration"/>
</p>
<p>
After installing osTicket, the next step is to configure it for efficient ticket management. Switching between the Admin and Agent panels is necessary for specific configurations. The panel in use is indicated in the top-right corner of the osTicket interface. If it says "Agent Panel," the Admin panel is being accessed, and vice versa.
</p>

<h3>Step 1: Create a New Role</h3>
<p>
    <img src="https://i.imgur.com/EQnl5rh.png" height="80%" width="80%" alt="Create Role"/>
</p>
<p>
Start by creating a "Supreme Admin" role with all permissions. In the Admin panel, navigate to the *Agents* menu, click *Roles,* and create the new role.
</p>

<h3>Step 2: Add a New Department</h3>
<p>
    <img src="https://i.imgur.com/d7WuRn8.png" height="80%" width="80%" alt="Create Department"/>
</p>
<p>
Create a "System Administrators" department. In the Admin panel, open the *Agents* menu, select *Departments,* and add a new department.
</p>

<h3>Step 3: Set Up Teams</h3>
<p>
    <img src="https://i.imgur.com/UnYyh3B.png" height="80%" width="80%" alt="Create Teams"/>
    <img src="https://i.imgur.com/k0lElHH.png" height="80%" width="80%" alt="Create Teams"/>
</p>
<p>
Add a "Level II Support Team" to complement the existing Level I team. Navigate to the *Agents* menu, click *Teams,* and create any required teams.
</p>

<h3>Step 4: Create New Agents</h3>
<p>
    <img src="https://i.imgur.com/gHvbfS3.png" height="80%" width="80%" alt="Add Agents"/>
</p>
<p>
Add agents to handle incoming tickets. In the Admin panel, go to the *Agents* menu, click *Add New Agent,* and create account credentials. For this setup, Jane and John Doe were added as agents.
</p>

<h3>Step 5: Add Users</h3>
<p>
    <img src="https://i.imgur.com/pI1Cf3Q.png" height="80%" width="80%" alt="Add Users"/>
</p>
<p>
Create users who will submit tickets. In the Agent panel, open the *Users* menu, click *Add User,* and set up accounts. Karen and Ken were added in this case.
</p>

<h3>Step 6: Configure Service Level Agreements (SLAs)</h3>
<p>
    <img src="https://i.imgur.com/v3zTkfy.png" height="80%" width="80%" alt="Add SLAs"/>
</p>
<p>
Define SLAs to prioritize ticket resolution times. In the Admin panel, go to the *Manage* menu, click *SLA,* and set up SLAs. For example, SEV-A (1 hour), SEV-B (4 hours), and SEV-C (8 hours) were created.
</p>

<h3>Step 7: Add Help Topics</h3>
<p>
    <img src="https://i.imgur.com/v3zTkfy.png" height="80%" width="80%" alt="Add Help Topics"/>
</p>
<p>
Set up Help Topics to categorize user issues. In the Admin panel, open the *Manage* menu, click *Help Topics,* and add new topics such as "Business Critical Outage," "Personal Computer Issues," "Equipment Reset," and "Password Request."
</p>

<h2>Configuration Complete</h2>
With these configurations, osTicket is ready to function as a fully operational ticketing system. Tickets can now be created, managed, and triaged effectively, simulating a real-world environment.
