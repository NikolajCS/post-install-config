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

- Windows 11 Pro (24H2)


<h2>Configuration Steps</h2>

In this tutorial, I will go over some basic configuration options you can do within osTicket.



Creating a Supreme Admin with all access > Admin Panel > Roles > Add New Role > Go to "Permmissions" and check everthing in both the Tickets and Tasks menu, it should look like this 

![image](https://github.com/user-attachments/assets/0af62618-5096-470f-bfe3-45accb73e52a) ![image](https://github.com/user-attachments/assets/e023a023-9e2e-4c37-967a-dd77c3b875d7)


You can add and configure Departments > Admin Panel > Agents > Departments > Add New Department > For this tutorial I will make a "Top Level Department and name it SysAdmins
![image](https://github.com/user-attachments/assets/9c9d6a24-67e2-412e-9614-6e1446ea8c86)

We can configure teams, > Admin Panel > Agents > Teams > Add New Team > You can assign certain agents to the team if you wish
![image](https://github.com/user-attachments/assets/f6aa1e52-5742-4e92-b18b-8b6195e9423a)

For this tutorial I will allow anyone to create tickets within my osTicket system. But if you want better security and only want to allow registered users to create tickets,  We can change it in > Admin Panel > Settings > User Settings > Check the box "Registration Required" 

![image](https://github.com/user-attachments/assets/eabb5c55-77a1-4a24-9f9d-f166fef067f6)

Configuring Help Desk Agents: Creating an Agent profile > Admin Panel > Agents > Add New > For this tutorial I will create an Agent named Mads

![image](https://github.com/user-attachments/assets/4607a7a7-f104-4c0e-89a9-63320fe34622)

We can assign Department, role and team:
![image](https://github.com/user-attachments/assets/685a0c4d-1980-4d64-b27c-67429dbc7a00)

![image](https://github.com/user-attachments/assets/b102c74e-5e61-408e-b9be-28ac3a88e772)

Configure Users (End users who might create tickets) > Agent Panel > Users > Add User > Fill in the information of the user

![image](https://github.com/user-attachments/assets/15ee5ea7-1a82-4a70-99aa-d66f6b4b0a1f)

Configure SLA's (Services Level Agreement) > Admin Panel > Manage > SLA > ADD New SLA Plan > We can configure how important the SLA is. For this tutorial I will create 3 different SLA's. Sev-A, Sev-B and Sev-C. Which are 3 different SLA's that could be used in a company to determine how important a ticket is, so in this case A being the most important and Sev-C being the least important. 
![image](https://github.com/user-attachments/assets/ca708700-1c95-41ff-881b-01ebbbea814d)
![image](https://github.com/user-attachments/assets/dbf858c3-de75-4c0a-9406-9a2da7b4aa6f)
![image](https://github.com/user-attachments/assets/ebdee2c2-0de5-4b48-ad43-de7de3b92e23)

Configure Help Topics (problems end users can assign to their tickets) > Admin Panel > Manage > Help Topic > Add New Help Topic > Some general issues could be "Password Reset", "Equipment Request", "Other" and so on.
![image](https://github.com/user-attachments/assets/c10f3f69-3877-4063-ac6f-9238f098c141)

This is the end of the osTicket basic configuartion tutorial. 







