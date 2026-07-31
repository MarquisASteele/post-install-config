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

<p><img width="3024" height="1964" alt="image" src="https://github.com/user-attachments/assets/c8f8e9cc-1754-4d78-aa4a-d90eab7d5f2d" />
 <img width="3024" height="1964" alt="image" src="https://github.com/user-attachments/assets/da8dc3f6-7b57-4749-b574-02ab862c42bd" />
</p>
<p>
After installing osTicket, the next step is to configure it for efficient ticket management. Switching between the Admin and Agent panels is necessary for specific configurations. The panel in use is indicated in the top-right corner of the osTicket interface. If it says "Agent Panel," the Admin panel is being accessed, and vice versa.
</p>

<h3>Step 1: Create a New Role</h3>
<p>
   <img width="3024" height="1964" alt="image" src="https://github.com/user-attachments/assets/158f5058-aa29-454c-96b6-e4fec34a260c" />
</p>
<p>
Start by creating a "Supreme Admin" role with all permissions. In the Admin panel, navigate to the *Agents* menu, click *Roles,* and create the new role.
</p>

<h3>Step 2: Add a New Department</h3>
<p>
  <img width="3024" height="1964" alt="image" src="https://github.com/user-attachments/assets/5e33f1d7-a7f7-4ded-b952-57bd4cecbbef" />
</p>
<p>
Create a "System Administrators" department. In the Admin panel, open the *Agents* menu, select *Departments,* and add a new department.
</p>

<h3>Step 3: Set Up Teams</h3>
<p><img width="3024" height="1964" alt="image" src="https://github.com/user-attachments/assets/f88d4173-358f-4793-801d-8ed4262682d4" />
    <img width="3024" height="1964" alt="image" src="https://github.com/user-attachments/assets/e3aad02b-0f0e-499a-b7e8-dbf2e7102ff6" />
</p>
<p>

Configure support teams to organize agents with shared responsibilities. Teams provide flexibility by allowing agents from multiple departments to collaborate on and resolve tickets while maintaining their departmental assignments.
</p>

<h3>Step 4: Create New Agents</h3>
<p>
    
</p>
<p>
Add agents to handle incoming tickets. In the Admin panel, go to the *Agents* menu, click *Add New Agent,* and create account credentials. For this setup, Jane and John Doe were added as agents.
</p>

<h3>Step 5: Add Users</h3>
<p><img width="3024" height="1964" alt="image" src="https://github.com/user-attachments/assets/abdf77fe-ad78-4e42-bbaf-d49621c7d675" />
  
</p>
<p>
Create user accounts for individuals who will submit support requests. In the Agent Panel, navigate to Users, select Add User, and create the necessary user accounts. In this example, two users—Karen and Mark—were added to simulate end users in the help desk environment.
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
