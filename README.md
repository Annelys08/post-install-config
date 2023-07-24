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

<h2>Post-Install Configuration Objectives</h2>

- Make sure you are still logged into the URL link
- Understand the difference between the Admin and Agent Panel
- Adding Roles, Departments, Agents, and Teams and providing access
- Give access to users to create tickets and provide Common Help topics to resolve their issues
- Develop SLA Plans 
<h2>Configuration Steps</h2>

![admin_agent_login](https://github.com/Annelys08/post-install-config/assets/139095349/4696ac41-27be-4476-943a-dd2556cb61f1)

<p>
Please make sure you know which portal you are working with before continuing. You can access either the admin or agent portal just by clicking it. It is located next to the arrow in the picture above.
</p>
<br />

![image](https://github.com/Annelys08/post-install-config/assets/139095349/6912ceb7-2a63-4dab-a288-d1364419bdbf) ![image](https://github.com/Annelys08/post-install-config/assets/139095349/83ef3feb-d5b5-4d2b-ac4d-a91018c66822)


<p>
When adding a role, you can set up its permissions and the task they are allowed to do. You can also give access to different departments as well.
</p>
<br />

![image](https://github.com/Annelys08/post-install-config/assets/139095349/bcd54f02-4328-4cee-a813-dd33bc4cc0ae)


<p>
To access who can create tickets, select under the settings bar the word user. Make sure the highlighted section is not selected to give everyone access to create tickets.
</p>
<br />

![image](https://github.com/Annelys08/post-install-config/assets/139095349/165384eb-d4eb-4f3f-b112-4dbde1793b3a)

When you need to add agents, make sure you are in the admin panel and click on agents and select Add a new agent. This will give them access to the portal and allow them to work on any tickets assigned to them.

![image](https://github.com/Annelys08/post-install-config/assets/139095349/aba87545-8223-4160-b72d-4da7c38b0f96)

Need to add a new SLA plan? In the Admin panel select Manage and SLA. You should then see the option to create a new SLA plan and set up the grace period/schedule time in which tickets should be prioritized.


![image](https://github.com/Annelys08/post-install-config/assets/139095349/5b39d2ff-1402-4fe6-8651-b4e8b79ce7fc)

Create Common Help Topics that users can select to submit tickets. To do so, you must select Manage in the Admin portal. Then you go to Help Topics and add a new Help Topic. This will provide users the ability to identify the issue they need assistance with. 
