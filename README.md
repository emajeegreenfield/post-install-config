<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />





<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Windows App (MacOS)
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 11</b> (25H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics





<p align="center">
  <h1>Configure Roles</h1>
</p>



<strong>Admin Panel > Agents > Roles. Click Add new role > Name it Supreme Admin > Check every box under Permissions tab > Click Add role. </strong>
<p>
</p>
<p>
</p>
<br />
<p>
<img <<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/137f953c-dfae-4eb3-be3d-cf4df4d33d70" />
</p>
<img <img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/5bba1944-0f66-4a1f-bcfe-de888d957e35" />

 <img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/82ccf5df-22fa-459d-9fe6-e4dceb531462" />

 <img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/2911c291-72ba-433e-89f7-9af6e5977d7e" />

 <img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/7f46e506-950a-45cd-9c05-2a4675219545" />





<p>
</p>
<br />



<p align="center">
  <h1>Configure Departments</h1>
</p>



<strong>Admin Panel > Agents > Departments. Click Add new department > Choose Top Level Department > Name it SysAdmins > Click Create Dept.</strong>
<p>
System Administrators:
</p>
<p>
</p>
<br />
<p>
<img <img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/b38caf29-8dd5-422c-8315-efe63047efbe" />
</p>
<p>
</p>
<br />






<p align="center">
  <h1>Configure Teams</h1>
</p>



<strong>Admin Panel > Agents > Teams. Click Add New Team > Name it Online Banking > Click Create Team.</strong>
<p>
Online Banking:
</p>
<p>
</p>
<br />
<p>
<img <img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/93134116-5c25-49e5-94b7-e43db05d1988" />
</p>
<p>
</p>
<br />




<p align="center">
  <h1>Allow anyone to create a ticket</h1>
</p>



<strong>Admin Panel > Settings > User Settings.</strong>
<p>
Make sure "Require registration and login to create tickets" is NOT selected:
</p>
<p>
</p>
<br />
<p>
<img <img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/b114b74b-92e4-4823-b9ff-050e7dac37f5" />
</p>
<p>
</p>
<br />



<p align="center">
  <h1>Configure Agents (workers)</h1>
</p>



<strong>Admin Panel > Agents > Add New.</strong>
<p>
Jane Doe:
</p>
<p>
</p>
<br />
<p>
<img <img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/9e2f9c4e-d75c-4290-8c36-f8ca003cadeb" />
</p>
<p>
<img <img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/9d90ca42-5686-49ee-9c79-d9f18adaf820" />
</p>
John Doe: 
<img <img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/4cd9bab7-9756-4a83-8f6d-c4d3434d605d" />

 <img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/fb5b2be4-21ab-442c-bac2-90084ed7ee0c" />




Both agents have all access to the Support Department
</p>
<br />




<p align="center">
  <h1>Configure End Users (customers)</h1>
</p>



<strong>Admin Panel > Users > Add New.</strong>
<p>
Karen (end user):
</p>
<p>
</p>
<br />
<p>
<img <img width="1286" height="786" alt="image" src="https://github.com/user-attachments/assets/fef27a79-706f-41bb-afd0-abf8d8cd6e66" />
</p>

Repeat this step for any internal end users.
<p>
</p>
<br />



<p align="center">
  <h1>Configure SLA (Service Level Agreement)</h1>
</p>



<strong>Admin Panel > Manage > SLA.</strong>
<p>
Sev-A (1 hour, 24/7).
Sev-B (4 hours, 24/7).
Sev-C (8 hours, business hours).
</p>
<p>
</p>
<br />
<p>
<img <img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/577f1d13-285b-47b6-840f-8179bbf17720" />

 <img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/ed67d20a-83cd-43e0-837a-6a09ae64398c" />

 <img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/69d14b30-5a8a-4ed3-972b-8b492e0277eb" />
</p>
<p>
</p>
<br />



<p align="center">
  <h1>Configure Help Topics</h1>
</p>



<strong>Admin Panel > Manage > Help Topics.</strong>
<p>
 Business Critical Outage.
 Personal Computer Issues.
 Equipment Request.
Password Reset.
</p>
<p>
</p>
<br />
<p>
<img <img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/b025a850-24c9-44f0-b5c7-f38f6dda51cc" />

 <img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/ac8415f3-6d7d-4671-b344-0f6afd7a5c4e" />

 <img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/7c834300-6d23-4374-96ad-580ba8d2e76c" />

 <img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/25da69e4-367d-497e-956a-e38783271704" />

</p>
<p>
Hope this will helpful with all the configurations to have a smooth osTicket experience!
</p>
<br />





