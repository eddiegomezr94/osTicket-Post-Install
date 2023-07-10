<p align="center">
  <img src=https://i.imgur.com/CYzlgsS.png>
</p>

<Div align="center">
  <H1> osTicket Post Install</H1>
</Div>

</div>
This tutorial outlines how to manage osTicket system as an administrator which encompasses creating and/or eliminating new agents, accounts, departments, help topics, roles, teams, SLA's, etc.  

<h2> Environments and Technologies Used</h2>
 
  - Microsoft Azure 
  - Remote Desktop
  - Internet Information Services (IIS)
  - osTicketing System
<h2> Operating System Used</h2> 
  
  - Windows 10 (21H2)

<h2> Post Install Steps </h2>
 
  - Supreme Admin Setup
  - Configure New Department
  - Configure New Team
  - Configure New Account/Agent 
  - Configure New User
  - Configure SLA
  - Configure New Help Topic

  <h2> List of Configurations in osTicket </h2>

  <Div align="center">
  <H1> Supreme Admin Setup </H1>
  </Div>
  <p align="center">
  <img src=https://imgur.com/Epr4VfL.png>
  </p>

  - When completing the osTicket install one of the first things I did was create a Supreme Administrator and assign him Roles.  This admin was given all permissions to execute as an admin in the os Ticket system. The process was to go to Admin Panel -> Agents -> Roles-> Tasks-> Check all the boxes within the Permissions.  

  <Div align="center">
  <H1> New Department Setup </H1>
  </Div>
  <p align="center">
  <img src=https://imgur.com/YZpZAhU.png>
  </p>

  - The next task was to configure a new department specifically for the System Admins. The steps where to go to the Admin Panel -> Agents -> Departments -> Parent Top Level Department -> Name System Admin.

  <Div align="center">
  <H1> New Team  </H1>
  </Div>
  <p align="center">
  <img src=https://imgur.com/g1qyPit.png>
  </p>

  - Within this step I show how to configure a team that is specifically specialized in level 2 technical support. The steps where included, Admin Panel -> Agents -> Teams -> Name Level 2 Support.

  <Div align="center">
  <H1> New Agents Account  </H1>
  </Div>
  <p align="center">
  <img src=https://imgur.com/7cLocHG.png>
  </p>

  - This next step shows how to configure a new account for a new agent joining the company. The steps are, Admin Panel -> Agents -> Add New Agent -> Fill in Agents Info.

  <Div align="center">
  <H1> New Customer Account </H1>
  </Div>
  <p align="center">
  <img src=https://imgur.com/K829Ik7.png>
  </p>

  - After the creation of a new agent I show how to configure a brand new account for a new customer adding them to the system. The steps are, Agent Panel -> User Directory -> Add New -> Input Name , Email, etc.

  <Div align="center">
  <H1> New Surface Level Agreement (SLA) </H1>
  </Div>
  <p align="center">
  <img src=https://imgur.com/Wzeq5C2.png>
  </p>

  - In the following step I demonstrate how to configure a new SLA with a severity level B, which in this case would be a mid level of severity. To do this in osTicket you go to Admin Panel -> Manage -> SLA -> Add New -> Name (SEV-B) -> Set to Active -> Grace Period (4hours) -> Schedule 24/7.

  <Div align="center">
  <H1> Configured SLA's With Varying Severity </H1>
  </Div>
  <p align="center">
  <img src=https://imgur.com/11EX8q9.png>
  </p>

  - The following image demonstrates the different levels of SLA's created, ranging from SEV-A , SEV-B , SEV-C.

 
  <Div align="center">
  <H1> New Help Topic </H1>
  </Div>
  <p align="center">
  <img src=https://imgur.com/CQyOQDn.png>
  </p>

  - This last process shows how to add a Help Topic in the osTciket system. In order to create a help topic you go to Admin Panel -> Manage -> Help Topics -> Help Topic Info -> Input New Help Topic (Business Critical Outage). 

    
    
  




