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

<h2>Post-Install Configuration Objectives</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Project Walkthrough</h2>

With osTicket open navigate to the Admin Panel by clicking "Admin Panel" located in orange at the top right of the page:

![image](https://github.com/user-attachments/assets/f49af089-f61d-4c9f-9ef2-12662698ca34)

To start configuring Roles Navigate to the "Agents" tab and click on "Roles" underneath the "Agents" tab. Enter a role name:

![image](https://github.com/user-attachments/assets/b6c38dc8-1be6-4181-8790-cd93a3896c5c)

In the "Permissions" tab of this role, give this role all permissions in "Tickets", "Tasks", and "Knowledgebase". This will be our "Supreme Admin" Role:

![image](https://github.com/user-attachments/assets/14389aed-0419-448e-af65-83acacd96b79)

![image](https://github.com/user-attachments/assets/2d380601-39ed-4141-9196-d4db43f5c279)

![image](https://github.com/user-attachments/assets/8b4eec01-25e0-4f45-a169-6291c062fba4)

To set up departments, while still in the "Agents" tab, click on "Departments" located just below the "Agents" tab. Name the department "Sysadmins" and create the Department:

![image](https://github.com/user-attachments/assets/67019276-bf36-4cf3-98a1-a85f7e9199d0)

Next, create a team by selecting the "Teams" tab, while still in the "Agents" tab. Then, name the team "Online Banking" and create team:

![image](https://github.com/user-attachments/assets/4c8320c9-b9c2-4d11-85ee-fe47db7a19d6)

Now, to allow anyone to create tickets, go to the "Settings" Tab, and under "Authentication Settings" make sure that "Require registration and login to create tickets" is unchecked:

![image](https://github.com/user-attachments/assets/1c67d8d0-34e7-4795-99e6-6d67eb445928)

To create agents (the help desk workers) navigate back to the "Agents" tab and select "Agents" and fill out the name, email, and username:

![image](https://github.com/user-attachments/assets/2a20bd45-554e-4ae6-a5ec-1f6dbfad052f)

Next to the username click "Set Password" set the password. Uncheck the "Send the agent a password reset email" and "Require password change at next login" options:

![image](https://github.com/user-attachments/assets/84b50ebe-c589-40d1-9dc7-65560c0fa1f9)

On the "Access" tab for this user select the "System Administrators" department and the "Supreme Admin" role created earlier:

![image](https://github.com/user-attachments/assets/30f5c936-52d9-4e98-8895-57847a683ea4)

Keep Permission settings as is:

![image](https://github.com/user-attachments/assets/33fcd568-8c37-4366-b96e-520c3fe6cbdf)

Under the "Teams" tab select "Online Banking" for this agent:

![image](https://github.com/user-attachments/assets/c8d53625-c46e-4523-9502-647ed0b57ac2)

Create one more agent as done previously, the only difference is in the "Access" tab select "Support" for the department:

![image](https://github.com/user-attachments/assets/a556437f-b5e5-44ce-97fd-8e426257df09)

![image](https://github.com/user-attachments/assets/737312d6-2f1c-40d0-9e1f-d72fab542ed1)

Keep Permission and Team settings as is:

![image](https://github.com/user-attachments/assets/70b605c9-f14c-4e65-93dd-c162c258b7ea)

![image](https://github.com/user-attachments/assets/43b49de2-d2c2-4372-846f-e47afbf1c3ee)

Next, to create a user (the customers) switch to the "Agent Panel" in orange in the top right> Users> Add User and put an email and name, then create.

![image](https://github.com/user-attachments/assets/16b9e1f4-d0cd-4764-b928-6ffa294a19ea)

Configuring an SLA plan navigate back to Admin Panel> Manage> SLA create three SLAs with different severities, grace periods, and schedules like so:

![image](https://github.com/user-attachments/assets/606cff05-64dd-43b9-8fc6-613204870754)

![image](https://github.com/user-attachments/assets/5e030d0b-472d-4e30-b039-288d391d3020)

![image](https://github.com/user-attachments/assets/78d09872-6e39-4363-8bbc-960db6ab0ee0)

![image](https://github.com/user-attachments/assets/1590004e-d467-4c62-a5ef-eb7104ee0cef)

Under the same "Manage" tab go to the "Help Topics" tab and create five help topics named, "Business Critical Outage", "Personal Computer Issues", "Equipment Request", "Password Reset", and "Other":

![image](https://github.com/user-attachments/assets/4fa01a49-1e8b-491e-bf98-a08129db8701)


<h2>osTicket Setup Complete!</h2>

<b> We've successfully set up multiple agents along with their departments, roles, and permissions. As well as, configured SLAs (Service Level Agreements), help topics, and users! osTicket is now setup for the next project where I will create and work different tickets using multiple agents and users!  </b>
<br />
