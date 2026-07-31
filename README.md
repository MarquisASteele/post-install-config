<p align="center">
    <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Installation Configuration Guide</h1>
This guide demonstrates the essential post-installation configuration steps required to prepare osTicket for use in a simulated enterprise help desk environment. It covers configuring administrative roles, departments, teams, users, Service Level Agreements (SLAs), and Help Topics to support efficient ticket management.

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

<h3>Step 1: Establish administrative roles
<p>
   <img width="3024" height="1964" alt="image" src="https://github.com/user-attachments/assets/158f5058-aa29-454c-96b6-e4fec34a260c" />
</p>
<p>
Configure a Supreme Admin role with full permissions to manage the osTicket environment. In the Admin Panel, navigate to Agents → Roles, then create a new role and assign the necessary permissions. This role provides administrators with complete access to manage tickets, users, agents, and system configurations.
</p>

<h3>Step 2: Assign agent permissions
<p>
  <img width="3024" height="1964" alt="image" src="https://github.com/user-attachments/assets/5e33f1d7-a7f7-4ded-b952-57bd4cecbbef" />
</p>
<p>
Configure a System Administrators department to organize agents responsible for managing technical support requests and system-related issues. In the Admin Panel, navigate to Agents → Departments, then create a new department. This department helps organize ticket assignments and ensures requests are routed to the appropriate support team.
</p>

<h3>Step 3: Create support teams
<p><img width="3024" height="1964" alt="image" src="https://github.com/user-attachments/assets/f88d4173-358f-4793-801d-8ed4262682d4" />
    <img width="3024" height="1964" alt="image" src="https://github.com/user-attachments/assets/e3aad02b-0f0e-499a-b7e8-dbf2e7102ff6" />
</p>
<p>

Configure support teams to organize agents with shared responsibilities. Teams provide flexibility by allowing agents from multiple departments to collaborate on and resolve tickets while maintaining their departmental assignments.
</p>

<h3>Step 4: Organize departments
<p>
    
</p>
<p>
Add agents to handle incoming tickets. In the Admin panel, go to the *Agents* menu, click *Add New Agent,* and create account credentials. For this setup, Jane and John Doe were added as agents.
</p>

<h3>Step 5: Add end-user accounts
<p><img width="3024" height="1964" alt="image" src="https://github.com/user-attachments/assets/abdf77fe-ad78-4e42-bbaf-d49621c7d675" />
  
</p>
<p>
Create user accounts for individuals who will submit support requests. In the Agent Panel, navigate to Users, select Add User, and create the necessary user accounts. In this example, two users—Karen and Mark—were added to simulate end users in the help desk environment.
</p>

<h3>Step 6: Define Service Level Agreements
<p>
   <img width="3024" height="1964" alt="image" src="https://github.com/user-attachments/assets/8e1dc424-b400-4bac-981f-edf50c748811" />

</p>
<p>
Configure Service Level Agreements (SLAs) to define ticket response and resolution priorities based on severity. In the Admin Panel, navigate to Manage → SLA, then create the appropriate SLA plans. In this example, three SLAs were configured: SEV-A (1 hour), SEV-B (4 hours), and SEV-C (8 hours) to simulate different levels of support urgency.
</p>

<h3>Step 7: Add Help Topics</h3>
<p><img width="3024" height="1964" alt="image" src="https://github.com/user-attachments/assets/df36370c-fc79-4719-8020-4e0b23b80c5e" />
</p>
<p>
Configure Help Topics to categorize incoming support requests and streamline ticket routing. In the Admin Panel, navigate to Manage → Help Topics, then create the appropriate categories. In this example, the following Help Topics were added: Business Critical Outage, Personal Computer Issues, Equipment Reset, Password Request, and Other.
</p>

<h2>Configuration Complete</h2>
With these configurations complete, the osTicket environment is fully prepared to support ticket creation, routing, prioritization, and resolution. Administrative roles, departments, teams, users, Service Level Agreements (SLAs), and Help Topics have been configured to simulate a real-world enterprise help desk environment.
