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

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>

1) Login to osTicket and switch the diplay from **_Agent Panel_** to **_Admin Panel_**.

![Screenshot (35)](https://github.com/nickcaviness/post-install-config/assets/137835904/ce8c8c0e-e983-4bf7-83b2-3934f4e412ff)

![Screenshot (38)](https://github.com/nickcaviness/post-install-config/assets/137835904/16780cdb-67f6-4cc1-82c5-034a891540e7)


2) Create a new role on the **_Admin Panel_**. Go to **_Agents_** -> **_Roles_** -> **_Add New Role_**. Give the new role a name and assign all permissions to the new role.

![Screenshot (39)](https://github.com/nickcaviness/post-install-config/assets/137835904/21b0cd09-b1e1-4e98-8b13-5bb5996e6a52)

![Screenshot (40)](https://github.com/nickcaviness/post-install-config/assets/137835904/2f52bd2d-142e-4579-b85f-ecd9a2308a5a)

![Screenshot (41)](https://github.com/nickcaviness/post-install-config/assets/137835904/a9baa0f4-3121-4238-928a-d6a254b62bc9)

![Screenshot (42)](https://github.com/nickcaviness/post-install-config/assets/137835904/d2900d22-6d21-45b2-bd04-9bb1f9daef32)

![Screenshot (43)](https://github.com/nickcaviness/post-install-config/assets/137835904/ee5c30bf-3c09-4f90-8839-251ba50b33ad)

![Screenshot (44)](https://github.com/nickcaviness/post-install-config/assets/137835904/a44ac597-6f06-4b56-bf09-620de08454fe)


3) Create a new Department on the **_Admin Panel_**. Go to **_Agents_** -> **_Department_** -> **_Add New Department_**. Give the new department a name.

![Screenshot (45)](https://github.com/nickcaviness/post-install-config/assets/137835904/e1e380a7-e8c2-4cf9-94ff-f35e44d0a406)

![Screenshot (46)](https://github.com/nickcaviness/post-install-config/assets/137835904/3a26db28-53e2-4e9d-9733-0f50c7ea1af6)


4) Create a new team on the **_Admin Panel_**. Go to **_Agents_** -> **_Teams_** -> **_Add New Team_**. Give the new team a name. 

![Screenshot (47)](https://github.com/nickcaviness/post-install-config/assets/137835904/128507a2-48c0-456a-8916-01f9455df87b)

![Screenshot (48)](https://github.com/nickcaviness/post-install-config/assets/137835904/513f8695-7a55-44f4-9872-e4c6b6e1698e)


5) Create a few agents on the **_Admin Panel_**. Go to **_Agents_** -> **_Add New Agents_**. Fill out the information for a new agent(s) created. Assign the new agent to a department and a team and any permissions the agent should have for the exercise.  

![Screenshot (49)](https://github.com/nickcaviness/post-install-config/assets/137835904/d7e340ff-35f9-45ec-86fc-ca6868780c57)

![Screenshot (50)](https://github.com/nickcaviness/post-install-config/assets/137835904/411fe3af-55b0-46b7-899a-9e8fb4121c3a)

![Screenshot (51)](https://github.com/nickcaviness/post-install-config/assets/137835904/0e49d4a5-f8cd-405a-a97d-7a6868c35395)

![Screenshot (52)](https://github.com/nickcaviness/post-install-config/assets/137835904/d04061d5-8dba-4f6a-b718-c94337eaf861)

![Screenshot (53)](https://github.com/nickcaviness/post-install-config/assets/137835904/4cc60f3d-1a89-4e26-a7eb-237e6bdef49b)

![Screenshot (54)](https://github.com/nickcaviness/post-install-config/assets/137835904/25105f7b-a81d-440c-852f-402d8241adaa)

![Screenshot (55)](https://github.com/nickcaviness/post-install-config/assets/137835904/1684f940-5ea4-44e5-b4a1-3fe3bdcdd34f)


6) Create users (customers) that will put in a ticket and request help from the agent. Switch to the **_Agent Panel_** and go to **_Users_** -> **_Add User_**. Fill out the new information for the new user. 

![Screenshot (56)](https://github.com/nickcaviness/post-install-config/assets/137835904/3b2e5351-110a-485d-b940-a8a2be2a61fd)

![Screenshot (57)](https://github.com/nickcaviness/post-install-config/assets/137835904/eaf62294-8452-4b60-980c-f11da96db59a)

![Screenshot (58)](https://github.com/nickcaviness/post-install-config/assets/137835904/44452c9a-94ea-40c0-9917-4d440762f4b6)


7) Create Service Level Agreements (or SLA) to give an approximate time for a ticket to be completed. Switch to the **_Admin Panel_**. Go to **_Manage_** -> **_SLA_**. Create three different SLAs with different names, grace periods, and the schedule.  

![Screenshot (59)](https://github.com/nickcaviness/post-install-config/assets/137835904/7b40a851-b561-4031-a696-15447a30298a)

![Screenshot (60)](https://github.com/nickcaviness/post-install-config/assets/137835904/1d27ad0f-efbf-4791-bab8-5c3bfac19d12)

![Screenshot (61)](https://github.com/nickcaviness/post-install-config/assets/137835904/7ee0249d-5115-46c4-ba46-d22e2fa1dfc0)

![Screenshot (62)](https://github.com/nickcaviness/post-install-config/assets/137835904/359fc8b5-9d2d-4f4e-89b3-1c661a78b3d2)

![Screenshot (63)](https://github.com/nickcaviness/post-install-config/assets/137835904/12b19490-5c4e-475d-b216-28d396bc4cea)

![Screenshot (64)](https://github.com/nickcaviness/post-install-config/assets/137835904/33d50903-a214-4358-85ff-9acfdf892129)


8) Create some help topics that users and agents may refer to. From **_Admin Panel_**, go to **_Manage_** -> **_Help Topics_** -> **_Add New Help Topic_**. Add topics that an agent or user may need to know when encountering a problem. 

![Screenshot (65)](https://github.com/nickcaviness/post-install-config/assets/137835904/ae419ee5-d6bf-46d0-b01d-9106f5a657b7)

![Screenshot (66)](https://github.com/nickcaviness/post-install-config/assets/137835904/8c19ba3d-e0e8-4911-83e0-62cb500eedce)

![Screenshot (67)](https://github.com/nickcaviness/post-install-config/assets/137835904/6ed49c15-0a8e-45c6-bdaa-71066d0f01a0)

![Screenshot (68)](https://github.com/nickcaviness/post-install-config/assets/137835904/8ce61b90-3a47-402b-8f8d-e3b6ee9639c6)

![Screenshot (69)](https://github.com/nickcaviness/post-install-config/assets/137835904/ea496100-0057-4f4b-ac75-0afe0ec161d8)


9) This completes the Post Install Configuration for osTicket.




