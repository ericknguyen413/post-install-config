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

<h2>Project Walkthrough</h2>

With osTicket open navigate to the Admin Panel by clicking "Admin Panel" located in orange at the top right of the page:

![image](https://github.com/user-attachments/assets/0a6bf025-fe31-4640-83ce-f7410f37f427)

To start configuring Roles Navigate to the "Agents" tab and click on "Roles" underneath the "Agents" tab. Enter a role name:

![image](https://github.com/user-attachments/assets/dcada870-1d9c-4eaa-92bc-cab99dd1e7a1)

In the "Permissions" tab of this role, give this role all permissions in "Tickets", "Tasks", and "Knowledgebase". This will be our "Supreme Admin" Role:

![image](https://github.com/user-attachments/assets/bbe5eef1-ef22-4aaa-9ebf-4940e6c53507)

![image](https://github.com/user-attachments/assets/32ec6173-a7ce-4e93-b397-f57b348fcf4d)

![image](https://github.com/user-attachments/assets/251d0983-274f-4942-819e-19c1f2dd602b)

To set up departments, while still in the "Agents" tab, click on "Departments" located just below the "Agents" tab. Name the department "Sysadmins" and create the Department:

![image](https://github.com/user-attachments/assets/67019276-bf36-4cf3-98a1-a85f7e9199d0)

Next, create a team by selecting the "Teams" tab, while still in the "Agents" tab. Then, name the team "Online Banking" and create team:

![image](https://github.com/user-attachments/assets/0e6438fb-b86a-4134-a51e-6822673e7344)

Now, to allow anyone to create tickets, go to the "Settings" Tab, and under "Authentication Settings" make sure that "Require registration and login to create tickets" is unchecked:

![image](https://github.com/user-attachments/assets/179c5f68-3999-412c-85fd-3aee9d4a411c)

To create agents (the help desk workers) navigate back to the "Agents" tab and select "Agents" and fill out the name, email, and username:

![image](https://github.com/user-attachments/assets/2a20bd45-554e-4ae6-a5ec-1f6dbfad052f)

Next to the username click "Set Password" set the password. Uncheck the "Send the agent a password reset email" and "Require password change at next login" options:

![image](https://github.com/user-attachments/assets/1a02f73b-d055-47a8-8628-67276bb213e2)

On the "Access" tab for this user select the "System Administrators" department and the "Supreme Admin" role created earlier:

![image](https://github.com/user-attachments/assets/69bd25ba-5520-491b-ad42-bdd7c6be63da)

Keep Permission settings as is:

![image](https://github.com/user-attachments/assets/e22afc02-ecc8-4bbc-8d0a-7a506e317f43)

Under the "Teams" tab select "Online Banking" for this agent:

![image](https://github.com/user-attachments/assets/be5efda6-2f2b-4e45-90c6-0a50adaafb7e)

Create one more agent as done previously, the only difference is in the "Access" tab select "Support" for the department:

![image](https://github.com/user-attachments/assets/cd3c0c2e-0744-4ed8-8832-726ef36d211e)

![image](https://github.com/user-attachments/assets/6c08976b-1096-4585-b52e-f846676371c7)

Keep Permission and Team settings as is:

![image](https://github.com/user-attachments/assets/f86a2f37-5a9b-40aa-8c40-3da8e1a750f4)

![image](https://github.com/user-attachments/assets/4079dd78-b8e7-4497-a6ec-628a3d9168a8)

Next, to create a user (the customers) switch to the "Agent Panel" in orange in the top right> Users> Add User and put an email and name, then create.

![image](https://github.com/user-attachments/assets/16b9e1f4-d0cd-4764-b928-6ffa294a19ea)

Configuring an SLA plan navigate back to Admin Panel> Manage> SLA create three SLAs with different severities, grace periods, and schedules like so:

![image](https://github.com/user-attachments/assets/f27cf3b3-8e5e-4441-8d40-dc5dd73057ef)

![image](https://github.com/user-attachments/assets/f43f5018-8a4b-410a-a34f-41e5958d5663)

![image](https://github.com/user-attachments/assets/2750b928-6568-4b17-ba02-44d756842caa)

![image](https://github.com/user-attachments/assets/3a389d75-2233-4c05-b58c-6e90d14559a1)

Under the same "Manage" tab go to the "Help Topics" tab and create five help topics named, "Business Critical Outage", "Personal Computer Issues", "Equipment Request", "Password Reset", and "Other":

![image](https://github.com/user-attachments/assets/199a3a3d-b822-4501-9c97-469331242f58)

<h2>osTicket Setup Complete!</h2>

<b> We've successfully set up multiple agents along with their departments, roles, and permissions. As well as, configured SLAs (Service Level Agreements), help topics, and users! osTicket is now setup for the next project where I will create and work different tickets using multiple agents and users!  </b>
<br />
